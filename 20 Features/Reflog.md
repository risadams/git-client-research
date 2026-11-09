---
title: Reflog and Recovery
group: History and investigation
client_count: 3
tags: [feature, feature-group/history-and-investigation, feature/reflog]
---
# Reflog and Recovery

**Group:** History and investigation  
**Clients with this feature in my notes:** 3 of 66

## What it does
Browse where branch tips used to point, so you can recover lost commits after a bad reset or deleted branch.

## Why it matters
A safety net for the worst mistakes.

## Git equivalent
`git reflog`, `git reset --hard <sha>`

## What to check when evaluating
Is it one click to restore a lost commit, or just a list?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[Fork|Fork]] (V): Reflog recovery, submodules, git-flow, LFS
- [[Git Revenge|Git Revenge]] (V): Interactive rebase, three-pane conflict tool, file history, blame, reflog, git notes, signature badges
- [[rgitui|rgitui]] (V): Commit graph, blame, file history, reflog, global search

Back to [[Features Index]] | [[00 Index]]
