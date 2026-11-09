---
title: Benchmarks
description: Hands-on timing and memory test of gitui against raw git on the git/git repository (82,725 commits).
retrieved: 2026-11-09
tags: [market-research, benchmark, confidence-T]
---

# Benchmarks

Grade: **T** (tested hands-on in a sandbox). See [[Data Reliability]] and [[Confidence Levels]].

Part of [[Market Research Hub]]. Related: [[Open Questions]].

## What this is and is not

- One open-source terminal client, [[GitUI|GitUI]], measured against raw `git` on one large repository.
- It is not a ranking of Git clients. Only one client was measured.
- The desktop GUI clients (Fork, Tower, GitKraken, Sublime Merge, SourceGit, GitHub Desktop and others) could not be run in a headless Linux sandbox, so there are no numbers for them.
- [[LazyGit|LazyGit]] was not measured. The Go module proxy was unreachable from the sandbox. A retry that would have disabled checksum verification was blocked, and I did not work around the block.

## Test setup

| Item | Value |
|---|---|
| Repository | github.com/git/git, full clone |
| Commits | 82,725 |
| Tracked files | 4,864 |
| `.git` size | 323 MB |
| Git version | 2.43.0 |
| GitUI version | gitui 0.28.1-nightly 2026-11-09 (built with cargo) |
| CPU | Intel(R) Xeon(R) Processor @ 2.10GHz, 2 cores |
| Environment | Linux sandbox, no GPU, 200x50 terminal over a pty |
| Clean case | Fresh clone, no local changes |
| Dirty case | Every tracked file (4,860 files) had one newline appended |
| Runs | 6 per scenario; the first (cold file cache) was dropped; median of the remaining 5 reported |

## Raw git baselines (seconds, median)

| Command | Repo state | Time |
|---|---|---|
| `git status` | clean | 0.011 |
| `git status` | dirty (4,860 modified) | 0.018 |
| `git log --graph` (5,000 commits) | clean | 0.852 |
| `git diff --stat` | dirty | 0.818 |

The dirty `git status` is fast because the appended newline changes every file's size, so git detects the change from stat data without hashing contents. A same-size edit would take longer.

## GitUI results (seconds unless noted, median of 5, range in brackets)

| Metric | Clean repo | Dirty repo |
|---|---|---|
| Time to first frame (tab bar drawn) | 0.035 [0.026 to 0.046] | 0.03 [0.029 to 0.038] |
| Status tab ready, measured from launch | 0.065 [0.057 to 0.075] | 0.108 [0.104 to 0.142] |
| Log tab: first commit rows after pressing `2` | 0.125 [0.081 to 0.162] | 0.115 [0.084 to 1.102] |
| Log tab: full history counter reaches 82,725/82,725 | 1.472 [1.234 to 1.531] | 1.414 [1.262 to 2.408] |
| Resident memory after Status tab loads (MB) | 56.1 [52.0 to 62.8] | 38.1 [36.6 to 67.7] |
| Peak resident memory after full log load (MB) | 75.9 [75.5 to 76.3] | 79.0 [78.5 to 79.5] |

## What the numbers say

- On a repository with 82,725 commits and 4,864 files, GitUI draws its first screen in about 30 ms and shows a populated Status tab in roughly 0.07 to 0.11 s from launch, including with 4,860 modified files.
- The first screen of commits appears in about 0.12 s. Loading the entire history takes about 1.4 to 1.5 s and the interface stays responsive while the counter climbs.
- Peak memory is about 76 to 79 MB after the full history is loaded.
- The Log tab loads history in the background, so the time to the first rows is the number that matches what a user sees.

## Caveats

- Single machine, single run session, 5 samples per cell. Ranges are shown because variance is real (one dirty-case log run took 1.1 s to first rows).
- The pty-based timings include terminal emulation in the harness (pyte), which adds a small and unmeasured overhead.
- The harness uses content markers on the rendered screen: the `Unstaged Changes` panel with the first file row, a commit row, and the `Commit N/N` title counter.
- GitUI restores the last used tab, so the harness always presses `1` and then `2` explicitly. History may already be loading in the background when `2` is pressed, which makes the log timings slightly optimistic.
- An earlier version of the harness waited for output to go quiet. GitUI redraws a spinner about every 40 ms until loading finishes, so that method gave invalid results. Those results were discarded and the harness was rewritten.
- These are performance numbers only. They say nothing about usability, features or fit. See [[Audience Guide]].

## What would make this stronger

- Run the same scenarios for LazyGit, Sublime Merge, Fork, Tower and GitKraken on a real desktop with a screen-capture or UI-automation method.
- Add a monorepo-scale case (hundreds of thousands of files) and a large-binary-file case.
- Repeat on macOS and Windows, where file-system speed differs widely.
- Measure idle CPU and battery draw.
