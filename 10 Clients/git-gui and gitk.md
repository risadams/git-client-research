---
title: git-gui and gitk
category: Bundled with Git
platforms: "Linux, macOS, Windows (ship with Git)"
license: "GPL-2.0"
ease_of_use: 2
status: Active
confidence: B
features: [partial-staging, commit-graph, history-search]
audience_tier: Simple
learning_fit: 2
solo_fit: 3
team_fit: 1
website: https://git-scm.com/docs/git-gui
tags: [git-client, bundled-with-git, feature/partial-staging, feature/commit-graph, feature/history-search]
---
# git-gui and gitk

> [!info] Data quality
> background knowledge, not re-verified. See [[Methodology and Gaps]].

| Field | Value |
|---|---|
| Category | Bundled with Git |
| Platforms | Linux, macOS, Windows (ship with Git) |
| Cost | Free |
| License | GPL-2.0 |
| Ease of use (my estimate) | ★★☆☆☆ (2/5) |
| Status | Active |
| Website | https://git-scm.com/docs/git-gui |

## Installation
Included with Git (Git for Windows includes both). Run `git gui` and `gitk`.

## Features
- git-gui: commit crafting, hunk and line staging
- gitk: history browser with search

## Feature tags
> [!warning] Not listed does not mean unsupported
> Tags come only from the feature text in this note. A missing tag means I have no evidence either way.

**Staging and commits:** [[Partial Staging|Partial Staging]]  
**History and investigation:** [[Commit Graph|Commit Graph]], [[History Search|History Search]]  

## Ease of use
Functional but very dated Tk UI.

## Audience fit
> [!info] My judgment, not user-tested. See [[Audience Guide]] for scales.

| Dimension | Rating |
|---|---|
| Tier | Simple |
| Good for learning Git | 2/5 |
| Solo developer fit | 3/5 |
| Team fit | 1/5 |

Zero-install fallback with a dated Tk UI. Fine for staging and browsing history.

## Best for
Zero-install fallback.

## Caveats
Dated, limited.

Back to [[00 Index]] | [[01 Comparison Table]]
