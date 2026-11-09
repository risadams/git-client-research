---
title: GitHub Desktop
category: Desktop GUI
platforms: "Windows, macOS (Linux only via community fork)"
license: "MIT"
ease_of_use: 5
status: Active
confidence: V
features: [partial-staging, commit-amend, stash, cherry-pick, drag-and-drop, history-editing, diff-viewer, syntax-highlighting, image-diff, pull-requests, hosting-integrations, ai-commit-messages]
audience_tier: Simple
learning_fit: 4
solo_fit: 5
team_fit: 3
website: https://desktop.github.com
tags: [git-client, desktop-gui, required, feature/partial-staging, feature/commit-amend, feature/stash, feature/cherry-pick, feature/drag-and-drop, feature/history-editing, feature/diff-viewer, feature/syntax-highlighting, feature/image-diff, feature/pull-requests, feature/hosting-integrations, feature/ai-commit-messages]
---
# GitHub Desktop

> [!info] Data quality
> verified on official page, 2026-11-09. See [[Methodology and Gaps]].

| Field | Value |
|---|---|
| Category | Desktop GUI |
| Platforms | Windows, macOS (Linux only via community fork) |
| Cost | Free |
| License | MIT |
| Ease of use (my estimate) | ★★★★★ (5/5) |
| Status | Active |
| Website | https://desktop.github.com |

## Installation
Download from desktop.github.com. Windows: `winget install GitHub.GitHubDesktop`. macOS: `brew install --cask github`.

## Features
- Visual staged and unstaged change review, partial-file staging
- Drag and drop to cherry-pick, squash, reorder commits
- Stash, amend, revert, branch switching
- Pull request creation and checks status for GitHub
- Syntax-highlighted and image diffs
- Co-author commits
- Copilot-assisted commit messages (needs an eligible Copilot plan)
- Release 3.6 reportedly added worktrees (single secondary source, verify)

## Feature tags
> [!warning] Not listed does not mean unsupported
> Tags come only from the feature text in this note. A missing tag means I have no evidence either way.

**Staging and commits:** [[Partial Staging|Partial Staging]], [[Commit Amend|Commit Amend]], [[Stash|Stash]]  
**Branching models and history rewriting:** [[Cherry-Pick|Cherry-Pick]], [[Drag and Drop|Drag and Drop]], [[History Editing|History Editing]]  
**Diff, compare and merge:** [[Diff Viewer|Diff Viewer]], [[Syntax Highlighting|Syntax Highlighting]], [[Image Diff|Image Diff]]  
**Hosting and workflow integrations:** [[Pull Requests|Pull Requests]], [[Hosting Integrations|Hosting Integrations]]  
**AI assistance:** [[AI Commit Messages|AI Commit Messages]]  

## Ease of use
Smallest surface area of any client here. Collapses fetch/pull/push/rebase into one Sync flow.

## Audience fit
> [!info] My judgment, not user-tested. See [[Audience Guide]] for scales.

| Dimension | Rating |
|---|---|
| Tier | Simple |
| Good for learning Git | 4/5 |
| Solo developer fit | 5/5 |
| Team fit | 3/5 |

Smallest surface area and free. The Sync button hides fetch, pull, and rebase, so it teaches the workflow but not Git internals. Fine for GitHub teams; thin once you need history surgery.

## Best for
Beginners, GitHub-first teams, open-source contributors.

## Caveats
GitHub-centric; weaker for GitLab/Bitbucket. No official Linux build. Limited advanced history editing (no full interactive rebase UI).

Back to [[00 Index]] | [[01 Comparison Table]]

## Market data

- Vendor: GitHub (Microsoft)
- Ownership: Microsoft subsidiary
- HQ: San Francisco, US
- Founded: GitHub 2007; Desktop open-sourced
- Team: Large (Microsoft)
- Funding: None needed: free funnel into GitHub
- Revenue model: Free; drives GitHub platform adoption
- User claims: none stated
- Grade: B (see [[Data Reliability]])
- GitHub: desktop/desktop, 21.9k stars, 10.6k forks, about 1k open issues, license MIT (snapshot 2026-11-09)

More in [[Vendors and Companies]] and [[Popularity Metrics]].
