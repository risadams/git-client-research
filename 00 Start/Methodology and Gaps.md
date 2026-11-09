---
title: Methodology and Gaps
tags: [git-client, research-log]
aliases: [Gaps and Next Steps]
---
# Methodology and Gaps

How the research was done, what it does not yet answer, and what to do next. Effort: S under an hour, M a few hours, L a day or more.

# Part 1: Method

## Sources (accessed 2026-11-09)
- git-scm.com/tools/guis: 45 clients with platforms, price, license. Used as backbone.
- Official pages fetched: git-tower.com/pricing, gitkraken.com/pricing, gitbutler.com, smartgit.dev/pricing, sourcetreeapp.com, tortoisegit.org, github.com/apps/desktop, git-fork.com.
- Round 2 (GitHub READMEs and Product Hunt): Git Revenge, GitComet, rgitui, ForkPlus, Gitember, BeeBranch. Secondary-only (LinuxLinks, Flathub, AUR, package indexes): GitFourchette, GitQlient, Desktop Plus, Stage, Gitu.
- Roundups used for cross-checking only: SourceForge, Hostinger, Toolradar, OpenReplay, Guideflow.

## Confidence counts
Full definitions: [[Confidence Levels]].
- V (verified on official page): 14
- L (git-scm.com listing only for price, platform, license): 39
- B (background knowledge): 8
- S (secondary sources only): 5

## Feature tagging
- 51 features defined by hand, grouped into 9 groups. A client gets a feature tag when a regex over its feature text matches. Each feature page shows the matching line as evidence.
- Tags are conservative: no match means no evidence, not 'unsupported'. Thin notes under-report.
- Feature lines that I flagged 'verify' are excluded from tagging.
- Regex matching can mislabel. Example to double-check: Fork's 'Hosting Integrations' comes from a GitHub notifications mention.

# Part 2: Gaps

## What is weakest today
- **Thin notes:** 39 of 66 clients are at confidence L (price, platform, license only). They under-report features and have placeholder install and ease notes.
- **No hands-on testing:** every ease-of-use star and every audience rating is my estimate.
- **No independent evidence:** vendor claims about speed, privacy, and features are unchecked. Git Revenge, BeeBranch, GitComet, and rgitui have no third-party reviews in my searches.
- **Dated facts:** pricing and versions were read on 2026-11-09.
- **Regex feature tags** can mislabel and under-report (see [[#Feature tagging]]).

## Known gaps
- GitKraken per-seat dollar amounts were not on the fetched page text. git-scm.com says $48+/user/yr.
- Sublime Merge buy page failed to load. Price is from git-scm.com and Toolradar.
- Git Revenge: rated from its own website only; no independent reviews found.
- GitHub Desktop page fetch showed only a macOS download. Windows support is well established, but confirm. The Linux build is community-maintained, not official.
- GitHub Desktop 3.6 worktrees/Copilot claim comes from a single low-quality secondary article.
- Package manager IDs (winget, brew) are from memory. Verify with `winget search` or `brew search`.
- Features and ease-of-use notes for lesser-known clients (Glint, GitBreeze, GitFiend, GitVine, RelaGit, Retcon, Changes, Guitar, SnailGit, NitroGit, Aurees) are thin. Listed for completeness.
- Ease-of-use stars are my judgment, not user-study data. Hands-on testing is the next step.

# Part 3: Next steps

## Done so far
Batch 2 (market research), 2026-11-09:

Added: [[Adjacent Tools]], [[Creative and Non-Developer Segment]], [[Vendor Claims vs Evidence]], [[Enterprise Buying Checklist]], [[Issue Tracker Traceability]], [[Switching Stories]], [[Dashboard]], [[Benchmarks]]. Remaining items are in [[Open Questions]].

Personas:

Personas and use cases added: [[Persona Index]]. The scoring rubric is the next step.

## Do now (Claude, no input needed)
| # | Gap | Why it matters | Effort |
|---|---|---|---|
| 1 | Upgrade L-level notes to V by reading each official site | Biggest quality jump: real features, install, and pricing | L |
| 2 | Maintenance signals: last release date, release cadence, open issues, stars for each open-source client | Separates alive from abandoned (GitAhead, Aurees already flagged) | M |
| 3 | Hosting support matrix: GitHub, GitLab, Bitbucket, Azure DevOps, Gitea, self-hosted | Hosting often decides the choice | M |
| 4 | OS matrix with detail: Windows ARM, Apple Silicon only vs Intel, Linux package formats | GitButler and BeeBranch are Apple Silicon only; others unknown | S |
| 5 | Cost table for 1, 5, and 25 users per year, from pricing pages | Turns pricing strings into a comparable number | S |
| 6 | Candidates not yet added: Gitte, GitPulsar, GitForce, gitonic, Thermal, giggle (seen on a LinuxLinks list), edamagit and Git Graph (VS Code extensions), Jujutsu UIs, Graphite and git-branchless for stacked workflows | The list is large but not exhaustive | M |

## Do next (needs your input)
| # | Gap | Owner | Why it matters |
|---|---|---|---|
| 7 | Your requirements: primary OS, hosting, repo size, solo or team, learning vs speed, must-haves such as stacked branches, local-only AI, no account | Ris | Lets me cut the 66 to a shortlist of 5 to 8 |
| 8 | Hands-on trial of the shortlist on a real repository, scoring staging, rebase, conflict resolution, startup time, large-repo behavior | Ris runs, Claude supplies a scorecard | Replaces estimates with observations; add a `T` confidence level |
| 9 | Decide which client families to exclude (mobile, discontinued, Mac-only) | Ris | Shrinks the work |

## Do later
| # | Gap | Owner | Why it matters |
|---|---|---|---|
| 10 | User sentiment from Reddit, Hacker News, G2, with links | Claude | Adds independent evidence; needs careful sourcing |
| 11 | Accessibility: screen reader support, keyboard-only use, animation, density, contrast, theming | Claude then Ris | Rarely documented by vendors; often decides daily comfort |
| 12 | Security and privacy review: telemetry, account requirements, signed binaries, update channel, credential storage, supply chain | Claude | rgitui ships unsigned binaries; others unknown |
| 13 | AI feature deep dive: cloud vs local, bring-your-own-key, what leaves your machine, cost | Claude | AI is a growing differentiator and a data-flow risk |
| 14 | Lock-in and compatibility: does the tool keep standard Git state, or add its own (GitButler branches, workspace files)? | Claude | Affects switching cost and CLI interop |
| 15 | Scenario scoring: monorepo, game assets with LFS, stacked PRs, air-gapped, Windows Explorer workflow | Claude then Ris | Fits tools to use cases rather than generic ratings |

Back to [[00 Index]] | [[Audience Guide]] | [[Confidence Levels]]

Back to [[Home]] | [[00 Index]] | [[Audience Guide]] | [[Confidence Levels]]
