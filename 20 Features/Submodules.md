---
title: Submodules
group: Staging and commits
client_count: 11
tags: [feature, feature-group/staging-and-commits, feature/submodules]
---
# Submodules

**Group:** Staging and commits  
**Clients with this feature in my notes:** 11 of 66

## What it does
Shows and manages repositories nested inside other repositories.

## Why it matters
Projects that vendor other repos otherwise need extra CLI steps to clone, update, and pin them.

## Git equivalent
`git submodule update --init --recursive`

## What to check when evaluating
Does clone fetch submodules automatically? Can you update and see their status in the main view?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[BeeBranch|BeeBranch]] (V): Staging by file, hunk, line; commit, amend, stash, tags, worktrees, submodules, patches
- [[Fork|Fork]] (V): Reflog recovery, submodules, git-flow, LFS
- [[Git Extensions|Git Extensions]] (L): Commit graph, stash, rebase, submodules
- [[LazyGit|LazyGit]] (L): Worktrees, submodules, custom commands
- [[Magit|Magit]] (L): Interactive rebase, worktrees, submodules, forge integration via Forge package
- [[rgitui|rgitui]] (V): Bisect, worktrees, submodules
- [[SmartGit|SmartGit]] (V): Git-flow, submodules, LFS, SVN bridge, Mercurial history
- [[SourceGit|SourceGit]] (L): Graph, interactive rebase, LFS, worktrees, submodules
- [[Sourcetree|Sourcetree]] (V): Git-flow, LFS, submodules
- [[TortoiseGit|TortoiseGit]] (V): Rebase, stash, bisect, submodules
- [[Tower|Tower]] (V): Interactive rebase UI, conflict solver, submodules, LFS

Back to [[Features Index]] | [[00 Index]]
