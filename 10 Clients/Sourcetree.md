---
title: Sourcetree
category: Desktop GUI
platforms: "macOS, Windows (Windows Enterprise build available)"
license: "Proprietary (Atlassian)"
ease_of_use: 3
status: Active
confidence: V
features: [partial-staging, stash, submodules, git-lfs, commit-graph, history-search, interactive-rebase, cherry-pick, git-flow, mercurial-and-svn]
audience_tier: Intermediate
learning_fit: 3
solo_fit: 5
team_fit: 4
website: https://www.sourcetreeapp.com
tags: [git-client, desktop-gui, required, feature/partial-staging, feature/stash, feature/submodules, feature/git-lfs, feature/commit-graph, feature/history-search, feature/interactive-rebase, feature/cherry-pick, feature/git-flow, feature/mercurial-and-svn]
---
# Sourcetree

> [!info] Data quality
> verified on official page, 2026-11-09. See [[Methodology and Gaps]].

| Field | Value |
|---|---|
| Category | Desktop GUI |
| Platforms | macOS, Windows (Windows Enterprise build available) |
| Cost | Free |
| License | Proprietary (Atlassian) |
| Ease of use (my estimate) | ★★★☆☆ (3/5) |
| Status | Active |
| Website | https://www.sourcetreeapp.com |

## Installation
Download from sourcetreeapp.com. Windows: `winget install Atlassian.Sourcetree`. macOS: `brew install --cask sourcetree`.

## Features
- Git and Mercurial support
- Visual branch and commit views
- Stage or discard at file, hunk, or line level
- Git-flow, LFS, submodules
- Interactive rebase, stash, cherry-pick
- Local search for commits, file changes, branches
- Search and clone remotes from within the app

## Feature tags
> [!warning] Not listed does not mean unsupported
> Tags come only from the feature text in this note. A missing tag means I have no evidence either way.

**Staging and commits:** [[Partial Staging|Partial Staging]], [[Stash|Stash]], [[Submodules|Submodules]], [[Git LFS|Git LFS]]  
**History and investigation:** [[Commit Graph|Commit Graph]], [[History Search|History Search]]  
**Branching models and history rewriting:** [[Interactive Rebase|Interactive Rebase]], [[Cherry-Pick|Cherry-Pick]], [[Git-Flow|Git-Flow]]  
**Scale and compatibility:** [[Mercurial and SVN|Mercurial and SVN]]  

## Ease of use
Capable and free, but UI is dense and dated; can feel slow on big repos.

## Audience fit
> [!info] My judgment, not user-tested. See [[Audience Guide]] for scales.

| Dimension | Rating |
|---|---|
| Tier | Intermediate |
| Good for learning Git | 3/5 |
| Solo developer fit | 5/5 |
| Team fit | 4/5 |

Free, with git-flow, LFS, and Bitbucket and Jira ties. The dense UI slows beginners. A Windows Enterprise build helps managed rollouts.

## Best for
Bitbucket and Jira teams, Git-flow users, anyone wanting a free full-featured client.

## Caveats
No Linux. Atlassian account sign-in has historically been part of first run (the home page did not mention it; verify). Mac and Windows builds are on different version tracks (Mac 4.2.x, Windows 3.4.x).

Back to [[00 Index]] | [[01 Comparison Table]]

## Market data

- Vendor: Atlassian
- Ownership: Atlassian Corporation Plc (public)
- HQ: Sydney, AU / San Francisco, US
- Founded: Atlassian 2002
- Team: Large (public company)
- Funding: Public; Atlassian ~$6.2B trailing-twelve-month revenue per getpanto (secondary)
- Revenue model: Free; funnel into Bitbucket and Jira
- User claims: none stated
- Grade: S (see [[Data Reliability]])

More in [[Vendors and Companies]] and [[Popularity Metrics]].
