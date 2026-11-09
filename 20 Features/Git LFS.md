---
title: Git LFS
group: Staging and commits
client_count: 9
tags: [feature, feature-group/staging-and-commits, feature/git-lfs]
---
# Git LFS

**Group:** Staging and commits  
**Clients with this feature in my notes:** 9 of 66

## What it does
Support for Git Large File Storage: big binaries stored outside the normal object database.

## Why it matters
Essential for game art, design files, datasets. Without support, pointers look like corrupt text files.

## Git equivalent
`git lfs install`, `git lfs track`

## What to check when evaluating
Does it show LFS file status and support locking? Is the LFS binary bundled?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[Anchorpoint|Anchorpoint]] (L): Git LFS and file locking friendly
- [[Fork|Fork]] (V): Reflog recovery, submodules, git-flow, LFS
- [[Gitember|Gitember]] (V): LFS, repo statistics, Jira and Linear linking (3.6)
- [[GitFourchette|GitFourchette]] (S): Git LFS awareness
- [[GitKraken Desktop|GitKraken Desktop]] (V): Built-in terminal, GitFlow support, LFS
- [[SmartGit|SmartGit]] (V): Git-flow, submodules, LFS, SVN bridge, Mercurial history
- [[SourceGit|SourceGit]] (L): Graph, interactive rebase, LFS, worktrees, submodules
- [[Sourcetree|Sourcetree]] (V): Git-flow, LFS, submodules
- [[Tower|Tower]] (V): Interactive rebase UI, conflict solver, submodules, LFS

Back to [[Features Index]] | [[00 Index]]
