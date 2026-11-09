---
title: Parallel Branches
group: Branching models and history rewriting
client_count: 1
tags: [feature, feature-group/branching-models-and-history-rewriting, feature/parallel-branches]
---
# Parallel Branches

**Group:** Branching models and history rewriting  
**Clients with this feature in my notes:** 1 of 66

## What it does
Work on several branches at once in the same working directory, assigning changes to each, without switching.

## Why it matters
Avoids stash-and-checkout churn when juggling multiple tasks.

## Git equivalent
No direct equivalent; approximated with worktrees

## What to check when evaluating
How does it behave with overlapping edits to the same file? Is it compatible with other tools touching the repo?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[GitButler|GitButler]] (V): Parallel branches: work on several branches at once without switching

Back to [[Features Index]] | [[00 Index]]
