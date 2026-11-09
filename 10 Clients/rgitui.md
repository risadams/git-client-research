---
title: rgitui
category: Desktop GUI
platforms: "Windows, Linux, macOS (macOS experimental)"
license: "MIT"
ease_of_use: 3
status: Active (early)
confidence: V
features: [stash, submodules, worktrees, commit-graph, history-search, blame, file-history, reflog, bisect, interactive-rebase, merge-conflict-resolver, pull-requests, hosting-integrations, issue-tracker-links, multi-repo-workspaces, keyboard-driven, themes, ai-commit-messages]
audience_tier: Intermediate
learning_fit: 3
solo_fit: 3
team_fit: 2
website: https://github.com/noahbclarkson/rgitui
tags: [git-client, desktop-gui, feature/stash, feature/submodules, feature/worktrees, feature/commit-graph, feature/history-search, feature/blame, feature/file-history, feature/reflog, feature/bisect, feature/interactive-rebase, feature/merge-conflict-resolver, feature/pull-requests, feature/hosting-integrations, feature/issue-tracker-links, feature/multi-repo-workspaces, feature/keyboard-driven, feature/themes, feature/ai-commit-messages]
---
# rgitui

> [!info] Data quality
> verified on official page, 2026-11-09. See [[Methodology and Gaps]].

| Field | Value |
|---|---|
| Category | Desktop GUI |
| Platforms | Windows, Linux, macOS (macOS experimental) |
| Cost | Free (no price stated) |
| License | MIT |
| Ease of use (my estimate) | ★★★☆☆ (3/5) |
| Status | Active (early) |
| Website | https://github.com/noahbclarkson/rgitui |

## Installation
Prebuilt: Windows .zip or .exe, Linux .AppImage or .tar.gz, macOS .dmg (Apple Silicon). Binaries are not code-signed, so expect security warnings. Or build with `cargo build --release` (recommended on macOS).

## Features
- Rust with GPUI (Zed's UI framework), GPU-accelerated rendering
- Staging, commit, branch, tag, stash, remotes, interactive rebase, conflict resolution
- Bisect, worktrees, submodules
- Commit graph, blame, file history, reflog, global search
- GitHub device-flow login, PR creation, issue and PR browsing
- Multi-repo tabs, command palette, themes
- Optional AI commit messages via Google Gemini

## Feature tags
> [!warning] Not listed does not mean unsupported
> Tags come only from the feature text in this note. A missing tag means I have no evidence either way.

**Staging and commits:** [[Stash|Stash]], [[Submodules|Submodules]], [[Worktrees|Worktrees]]  
**History and investigation:** [[Commit Graph|Commit Graph]], [[History Search|History Search]], [[Blame|Blame]], [[File History|File History]], [[Reflog|Reflog]], [[Bisect|Bisect]]  
**Branching models and history rewriting:** [[Interactive Rebase|Interactive Rebase]]  
**Diff, compare and merge:** [[Merge Conflict Resolver|Merge Conflict Resolver]]  
**Hosting and workflow integrations:** [[Pull Requests|Pull Requests]], [[Hosting Integrations|Hosting Integrations]], [[Issue Tracker Links|Issue Tracker Links]], [[Multi-Repo Workspaces|Multi-Repo Workspaces]]  
**Interface and ergonomics:** [[Keyboard Driven|Keyboard Driven]], [[Themes|Themes]]  
**AI assistance:** [[AI Commit Messages|AI Commit Messages]]  

## Ease of use
Command palette and tabs feel editor-like; not assessed hands-on.

## Audience fit
> [!info] My judgment, not user-tested. See [[Audience Guide]] for scales.

| Dimension | Rating |
|---|---|
| Tier | Intermediate |
| Good for learning Git | 3/5 |
| Solo developer fit | 3/5 |
| Team fit | 2/5 |

Early development by its own README, with unsigned binaries. Command palette and tabs suit solo power users.

## Best for
Rust and Zed users who want a GPU-rendered open-source client.

## Caveats
The README itself says 'still in early, active development' with bugs and breaking changes expected. Unsigned binaries. macOS builds experimental. Install table and feature list disagree on Intel Mac support.

Back to [[00 Index]] | [[01 Comparison Table]]
