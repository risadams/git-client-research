---
title: Undo and Redo
group: Branching models and history rewriting
client_count: 5
tags: [feature, feature-group/branching-models-and-history-rewriting, feature/undo-and-redo]
---
# Undo and Redo

**Group:** Branching models and history rewriting  
**Clients with this feature in my notes:** 5 of 66

## What it does
Reverts the effect of a Git operation (commit, merge, branch delete) with a button, often with redo.

## Why it matters
Lowers the fear of experimenting with rebases and merges.

## Git equivalent
`git reflog` plus `git reset`, done by hand

## What to check when evaluating
How far back does undo go? Does it cover remote operations (it generally cannot)?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[BeeBranch|BeeBranch]] (V): Merge and rebase with intermediate states, undo and redo limited to reversible Git operations, crash-recovery journal
- [[Git Revenge|Git Revenge]] (V): Staging by file, hunk, or line; commit, stash, branch, merge, rebase, cherry-pick, reset, revert, with undo
- [[GitButler|GitButler]] (V): Unlimited undo and redo, including after commits
- [[GitUp|GitUp]] (L): Unlimited undo and redo of Git operations
- [[Tower|Tower]] (V): Undo Anything (undo most operations incl. commits, merges, branch deletes)

Back to [[Features Index]] | [[00 Index]]
