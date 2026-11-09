---
title: TortoiseGit
category: Shell / file manager integration
platforms: "Windows"
license: "GNU GPL"
ease_of_use: 3
status: Active
confidence: V
features: [stash, submodules, commit-graph, blame, bisect, interactive-rebase, diff-viewer, merge-conflict-resolver, shell-integration]
audience_tier: Intermediate
learning_fit: 2
solo_fit: 4
team_fit: 3
website: https://tortoisegit.org
tags: [git-client, shell-file-manager-integration, required, feature/stash, feature/submodules, feature/commit-graph, feature/blame, feature/bisect, feature/interactive-rebase, feature/diff-viewer, feature/merge-conflict-resolver, feature/shell-integration]
---
# TortoiseGit

> [!info] Data quality
> verified on official page, 2026-11-09. See [[Methodology and Gaps]].

| Field | Value |
|---|---|
| Category | Shell / file manager integration |
| Platforms | Windows |
| Cost | Free |
| License | GNU GPL |
| Ease of use (my estimate) | ★★★☆☆ (3/5) |
| Status | Active |
| Website | https://tortoisegit.org |

## Installation
Installer and language packs from tortoisegit.org/download. Needs Git for Windows installed separately (general knowledge; site home page did not state it). `winget install TortoiseGit.TortoiseGit`. Latest per site news: 2.19.1 (2026-06-27).

## Features
- Explorer context-menu integration for Git
- Overlay icons showing file status in Explorer
- Commit, log viewer, revision graph, diff, blame
- Rebase, stash, bisect, submodules
- Merge conflict editor (TortoiseGitMerge)

## Feature tags
> [!warning] Not listed does not mean unsupported
> Tags come only from the feature text in this note. A missing tag means I have no evidence either way.

**Staging and commits:** [[Stash|Stash]], [[Submodules|Submodules]]  
**History and investigation:** [[Commit Graph|Commit Graph]], [[Blame|Blame]], [[Bisect|Bisect]]  
**Branching models and history rewriting:** [[Interactive Rebase|Interactive Rebase]]  
**Diff, compare and merge:** [[Diff Viewer|Diff Viewer]], [[Merge Conflict Resolver|Merge Conflict Resolver]]  
**Interface and ergonomics:** [[Shell Integration|Shell Integration]]  

## Ease of use
Instantly familiar if you know TortoiseSVN. Dialog-heavy, not a single window.

## Audience fit
> [!info] My judgment, not user-tested. See [[Audience Guide]] for scales.

| Dimension | Rating |
|---|---|
| Tier | Intermediate |
| Good for learning Git | 2/5 |
| Solo developer fit | 4/5 |
| Team fit | 3/5 |

Dialog-heavy and assumes Git vocabulary. Free and Explorer-native, but Windows only, which limits mixed-OS teams.

## Best for
Windows users who live in Explorer.

## Caveats
Windows only. Many windows and dialogs; weak branch visualization versus graph-first clients.

Back to [[00 Index]] | [[01 Comparison Table]]
