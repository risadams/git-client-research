---
title: Stacked Branches
group: Branching models and history rewriting
client_count: 2
tags: [feature, feature-group/branching-models-and-history-rewriting, feature/stacked-branches]
---
# Stacked Branches

**Group:** Branching models and history rewriting  
**Clients with this feature in my notes:** 2 of 66

## What it does
Manage a chain of dependent branches (each built on the previous) and keep them in sync when the base changes.

## Why it matters
Enables small, reviewable pull requests for large features.

## Git equivalent
`git rebase --update-refs` plus scripts, or tools like Graphite

## What to check when evaluating
Does it rebase the whole stack when a lower branch changes? Does it open one PR per layer?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[GitButler|GitButler]] (V): Stacked branches with independent review and landing
- [[Tower|Tower]] (V): Pro: Stacked Branches, Custom Workflows, Graphite support, Branch Cleanup, Self-Hosted repositories, Merge Detection

Back to [[Features Index]] | [[00 Index]]
