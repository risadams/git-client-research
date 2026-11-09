---
title: Cherry-Pick
group: Branching models and history rewriting
client_count: 5
tags: [feature, feature-group/branching-models-and-history-rewriting, feature/cherry-pick]
---
# Cherry-Pick

**Group:** Branching models and history rewriting  
**Clients with this feature in my notes:** 5 of 66

## What it does
Copy specific commits from one branch onto another.

## Why it matters
Backporting fixes to release branches.

## Git equivalent
`git cherry-pick <sha>`

## What to check when evaluating
Can you pick multiple commits at once and handle conflicts in the UI?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[Git Revenge|Git Revenge]] (V): Staging by file, hunk, or line; commit, stash, branch, merge, rebase, cherry-pick, reset, revert, with undo
- [[GitHub Desktop|GitHub Desktop]] (V): Drag and drop to cherry-pick, squash, reorder commits
- [[LazyGit|LazyGit]] (L): Stage by line, interactive rebase, cherry-pick, bisect
- [[Sourcetree|Sourcetree]] (V): Interactive rebase, stash, cherry-pick
- [[Tower|Tower]] (V): Drag and drop everywhere (merge, rebase, cherry-pick)

Back to [[Features Index]] | [[00 Index]]
