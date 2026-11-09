---
title: Worktrees
group: Staging and commits
client_count: 6
tags: [feature, feature-group/staging-and-commits, feature/worktrees]
---
# Worktrees

**Group:** Staging and commits  
**Clients with this feature in my notes:** 6 of 66

## What it does
Check out multiple branches at the same time into separate folders that share one repository.

## Why it matters
Work on a hotfix while a long build or review runs on another branch, with no stashing.

## Git equivalent
`git worktree add`

## What to check when evaluating
Can you create, list, switch, and remove worktrees from the UI?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[BeeBranch|BeeBranch]] (V): Staging by file, hunk, line; commit, amend, stash, tags, worktrees, submodules, patches
- [[GitComet|GitComet]] (V): Pull/push, staging, commits, worktrees, branching, full history
- [[LazyGit|LazyGit]] (L): Worktrees, submodules, custom commands
- [[Magit|Magit]] (L): Interactive rebase, worktrees, submodules, forge integration via Forge package
- [[rgitui|rgitui]] (V): Bisect, worktrees, submodules
- [[SourceGit|SourceGit]] (L): Graph, interactive rebase, LFS, worktrees, submodules

Back to [[Features Index]] | [[00 Index]]
