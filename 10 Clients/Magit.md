---
title: Magit
category: Editor or IDE integrated
platforms: "Linux, macOS, Windows (needs Emacs)"
license: "GNU GPL"
ease_of_use: 2
status: Active
confidence: L
features: [partial-staging, submodules, worktrees, interactive-rebase, hosting-integrations, editor-integration, keyboard-driven]
audience_tier: Pro
learning_fit: 2
solo_fit: 3
team_fit: 1
website: https://magit.vc
tags: [git-client, editor-or-ide-integrated, feature/partial-staging, feature/submodules, feature/worktrees, feature/interactive-rebase, feature/hosting-integrations, feature/editor-integration, feature/keyboard-driven]
---
# Magit

> [!info] Data quality
> price, platform, license from git-scm.com listing; rest unverified. See [[Methodology and Gaps]].

| Field | Value |
|---|---|
| Category | Editor or IDE integrated |
| Platforms | Linux, macOS, Windows (needs Emacs) |
| Cost | Free |
| License | GNU GPL |
| Ease of use (my estimate) | ★★☆☆☆ (2/5) |
| Status | Active |
| Website | https://magit.vc |

## Installation
Install inside Emacs via MELPA: `M-x package-install RET magit`.

## Features
- Keyboard-driven Git porcelain inside Emacs
- Transient popup menus expose most of Git's flags
- Hunk, region, and line-level staging
- Interactive rebase, worktrees, submodules, forge integration via Forge package

## Feature tags
> [!warning] Not listed does not mean unsupported
> Tags come only from the feature text in this note. A missing tag means I have no evidence either way.

**Staging and commits:** [[Partial Staging|Partial Staging]], [[Submodules|Submodules]], [[Worktrees|Worktrees]]  
**Branching models and history rewriting:** [[Interactive Rebase|Interactive Rebase]]  
**Hosting and workflow integrations:** [[Hosting Integrations|Hosting Integrations]]  
**Interface and ergonomics:** [[Editor Integration|Editor Integration]], [[Keyboard Driven|Keyboard Driven]]  

## Ease of use
Excellent, but requires Emacs fluency. Often cited as best-in-class Git UI by its users.

## Audience fit
> [!info] My judgment, not user-tested. See [[Audience Guide]] for scales.

| Dimension | Rating |
|---|---|
| Tier | Pro |
| Good for learning Git | 2/5 |
| Solo developer fit | 3/5 |
| Team fit | 1/5 |

Excellent if you already live in Emacs. Steep prerequisite.

## Best for
Emacs users.

## Caveats
Useless outside Emacs; steep learning curve.

Back to [[00 Index]] | [[01 Comparison Table]]
