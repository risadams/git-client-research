---
title: History Search and Filtering
group: History and investigation
client_count: 6
tags: [feature, feature-group/history-and-investigation, feature/history-search]
---
# History Search and Filtering

**Group:** History and investigation  
**Clients with this feature in my notes:** 6 of 66

## What it does
Search commits by message, author, content, file, or date, often with filters.

## Why it matters
Finding the change that introduced a behavior is a daily job.

## Git equivalent
`git log --grep`, `git log -S`, `git log -- path`

## What to check when evaluating
Does search cover commit content (pickaxe) or only messages? Is it indexed or live?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[git-gui and gitk|git-gui and gitk]] (B): gitk: history browser with search
- [[Gitember|Gitember]] (V): Full-text search (Lucene) across commits, branches, tags, file contents including PDFs and Office files
- [[Gittyup|Gittyup]] (L): Commit filtering, tag and commit message templates
- [[rgitui|rgitui]] (V): Commit graph, blame, file history, reflog, global search
- [[SmartGit|SmartGit]] (V): Graph and log with powerful filters
- [[Sourcetree|Sourcetree]] (V): Local search for commits, file changes, branches

Back to [[Features Index]] | [[00 Index]]
