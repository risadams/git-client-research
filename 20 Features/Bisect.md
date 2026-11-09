---
title: Bisect
group: History and investigation
client_count: 3
tags: [feature, feature-group/history-and-investigation, feature/bisect]
---
# Bisect

**Group:** History and investigation  
**Clients with this feature in my notes:** 3 of 66

## What it does
Guided binary search through history to find the commit that introduced a bug.

## Why it matters
Turns an unknown regression into roughly log2(n) test runs.

## Git equivalent
`git bisect start/good/bad`

## What to check when evaluating
Is it a guided UI, or does it just wrap the commands?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[LazyGit|LazyGit]] (L): Stage by line, interactive rebase, cherry-pick, bisect
- [[rgitui|rgitui]] (V): Bisect, worktrees, submodules
- [[TortoiseGit|TortoiseGit]] (V): Rebase, stash, bisect, submodules

Back to [[Features Index]] | [[00 Index]]
