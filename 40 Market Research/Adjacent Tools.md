---
title: Adjacent Tools
description: "Jujutsu GUIs and TUIs, Sapling, Graphite, git-branchless: the layer where pro-level gaps are being solved first."
retrieved: 2026-11-09
tags: [market-research, adjacent, jujutsu, stacked-prs]
---

# Adjacent Tools

These are not Git GUIs in the usual sense. They are alternative version control systems or workflow layers that sit on top of Git, plus the interfaces people build for them. They matter because the pro-level gaps in [[Trends]] (operation log, stacked branches, non-blocking conflicts) are solved here first. Snapshot 2026-11-09; GitHub counts are abbreviated on the page.

## Systems

| Tool | What it is | Stars | Forks | Open issues | License | Backed by |
|---|---|---|---|---|---|---|
| Jujutsu (jj) | Git-compatible VCS with operation log, no staging area, conflicts stored in commits | 32.3k | 1.3k | 810 | Apache-2.0 | Started at Google by Martin von Zweigbergk (secondary source) |
| Sapling | Meta's Git-compatible client with Smartlog and a web UI (ISL) | 7.0k | 400 | 240 | GPL-2.0 (ISL and site MIT) | Meta; open sourced 2022-11-15 |
| git-branchless | Git extension adding undo, smartlog, restacking | 4.1k | 117 | 72 | Apache-2.0 and MIT | Individual (arxanas); README says alpha |
| Graphite | Stacked PRs, `gt` CLI, merge queue, AI reviewer, on GitHub | closed source | n/a | n/a | Proprietary | Acquired by Cursor (agreement signed 2025-12-19); price undisclosed |

Notes:

- Jujutsu has 1.5 times the stars of GitHub Desktop (32.3k vs 21.9k) despite being a different VCS front end. It has no official GUI; the ecosystem builds them.
- Sapling's server pieces (Mononoke, EdenFS) are documented as not supported for external use. The client and ISL are usable.
- A Jujutsu developer wrote on Hacker News that ISL is a significant advantage over Jujutsu itself for rebasing and restacking, so the strongest GUI in this layer belongs to a competitor system.
- Graphite had raised about $52M shortly before the deal (Tessl) and a figure of $72M to $81M in total across sources; its last valuation was reported at $290M. Treat these as secondary.
- A third-party page claims Cursor is building a Git hosting product called Origin, waitlist only. I could not confirm that from a primary source.

## Interfaces for Jujutsu

| Interface | Type | Stars | Forks | Issues | License | Notes |
|---|---|---|---|---|---|---|
| jjui | Terminal UI (Go) | 2.2k | 119 | 39 | MIT | Revset completion, operation log view with restore, requires jj 0.36+ |
| lazyjj | Terminal UI (Rust) | 1.2k | 44 | 39 | Apache-2.0 | Inspired by lazygit |
| GG | Desktop GUI (Tauri, Rust and Svelte) | 866 | 51 | 12 | Apache-2.0 | Installable by brew and winget; created 2024-02 |
| JayJay | macOS native GUI | not retrieved | | | | Listed on jj's community tools page |
| LightJJ | Browser UI | not retrieved | | | | Listed on jj's community tools page |
| JJ View | VS Code extension | not retrieved | | | | Listed on jj's community tools page |
| Selvejj | JetBrains plugin | not retrieved | | | | Listed on jj's community tools page |
| VisualJJ | Editor integration | not retrieved | | | | Listed on jj's community tools page |

## What this layer tells the market

1. **The pro-level feature wishlist has a working prototype.** An operation log with restore, conflicts that do not block, and automatic restacking exist today in Jujutsu and Sapling. See [[Trends]].
2. **GUIs for the new systems are small.** The largest Jujutsu GUI (GG, 866 stars) has about 4% of the stars of GitHub Desktop. The commercial GUI vendors have no visible jj product in my records. I did not check whether Tower, GitKraken, Fork, or Sublime Merge have announced jj support.
3. **Graphite sits between Git and a new forge.** Its stacked workflow is built into Tower, per Tower's docs, and into GitButler. Cursor's purchase signals that review and stacking are now part of AI-editor strategy, not only Git tooling.
4. **Risks.** Jujutsu is described by its own community as experimental; one user said GitHub PR sync for stacks is a top pain point. Sapling's licensing is GPL-2.0 with parts MIT.

Related: [[GitButler|GitButler]] (parallel branches), [[LazyGit|LazyGit]] (the model lazyjj copies), [[Market Overview]].


Back to [[Market Research Hub]] | [[00 Index]] | [[Data Reliability]]
