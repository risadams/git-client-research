---
title: Commit Editing and History Surgery
group: Branching models and history rewriting
client_count: 3
tags: [feature, feature-group/branching-models-and-history-rewriting, feature/history-editing]
---
# Commit Editing and History Surgery

**Group:** Branching models and history rewriting  
**Clients with this feature in my notes:** 3 of 66

## What it does
Move changes between commits, split, squash, absorb, or reorder without a manual rebase.

## Why it matters
Cleans up history with fewer steps and less risk than interactive rebase.

## Git equivalent
`git commit --fixup`, `git rebase -i --autosquash`

## What to check when evaluating
Can you split a commit and absorb staged changes into the right ancestor commit?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[GitButler|GitButler]] (V): History editing: move, absorb, reorder, amend changes between commits
- [[GitHub Desktop|GitHub Desktop]] (V): Drag and drop to cherry-pick, squash, reorder commits
- [[Sublime Merge|Sublime Merge]] (L): Line-level staging, commit editing, blame, interactive rebase

Back to [[Features Index]] | [[00 Index]]
