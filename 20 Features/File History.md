---
title: File History
group: History and investigation
client_count: 4
tags: [feature, feature-group/history-and-investigation, feature/file-history]
---
# File History

**Group:** History and investigation  
**Clients with this feature in my notes:** 4 of 66

## What it does
Lists the commits that touched a given file or folder and lets you diff across them.

## Why it matters
Answers 'when did this file change and why' without scanning the whole log.

## Git equivalent
`git log --follow -- path`

## What to check when evaluating
Does it follow renames? Can you browse the tree at any commit?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[Fork|Fork]] (V): Blame, file and directory history, tree browser at any commit
- [[Git Revenge|Git Revenge]] (V): Interactive rebase, three-pane conflict tool, file history, blame, reflog, git notes, signature badges
- [[QGit|QGit]] (B): Qt viewer showing branches, patches, file history, archive trees
- [[rgitui|rgitui]] (V): Commit graph, blame, file history, reflog, global search

Back to [[Features Index]] | [[00 Index]]
