---
title: Commit Graph
group: History and investigation
client_count: 24
tags: [feature, feature-group/history-and-investigation, feature/commit-graph]
---
# Commit Graph

**Group:** History and investigation  
**Clients with this feature in my notes:** 24 of 66

## What it does
A visual map of commits, branches and merges drawn as lines.

## Why it matters
Makes branching and merge structure obvious at a glance, which is the main reason people pick a GUI.

## Git equivalent
`git log --graph --oneline --all`

## What to check when evaluating
How does it handle thousands of branches or 100k+ commits? Can you filter by author, branch, path?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[BeeBranch|BeeBranch]] (V): Virtualized history graph (maker claims 200k commits)
- [[Git Extensions|Git Extensions]] (L): Commit graph, stash, rebase, submodules
- [[git-cola|git-cola]] (L): Staging, DAG history viewer (git-dag), keyboard shortcuts
- [[git-gui and gitk|git-gui and gitk]] (B): gitk: history browser with search
- [[GitAhead|GitAhead]] (L): Commit graph, staging, blame, 3-way merge
- [[Gitember|Gitember]] (V): Visual commit graph and an option to show the equivalent Git command for each action
- [[GitFiend|GitFiend]] (L): Visual history and staging
- [[gitg|gitg]] (L): Commit history browser, staging
- [[GitKraken Desktop|GitKraken Desktop]] (V): Interactive commit graph
- [[GitLens (VS Code)|GitLens (VS Code)]] (B): Commit graph (Pro), AI explain commit
- [[Gitnuro|Gitnuro]] (L): Graph, staging, branch operations
- [[GitQlient|GitQlient]] (S): Visual history, hunk staging, rebase
- [[GitUp|GitUp]] (L): Live, always-updating repository map
- [[Guitar|Guitar]] (L): Qt-based graphical Git client
- [[JetBrains IDE Git|JetBrains IDE Git]] (B): Commit tool window, shelves, interactive rebase, log with graph
- [[rgitui|rgitui]] (V): Commit graph, blame, file history, reflog, global search
- [[SmartGit|SmartGit]] (V): Graph and log with powerful filters
- [[SourceGit|SourceGit]] (L): Graph, interactive rebase, LFS, worktrees, submodules
- [[Sourcetree|Sourcetree]] (V): Visual branch and commit views
- [[tig|tig]] (L): ncurses history browser
- [[TortoiseGit|TortoiseGit]] (V): Commit, log viewer, revision graph, diff, blame
- [[Tower|Tower]] (V): Pro: Stacked Branches, Custom Workflows, Graphite support, Branch Cleanup, Self-Hosted repositories, Merge Detection
- [[ungit|ungit]] (L): Visual commit graph
- [[VS Code built-in Git|VS Code built-in Git]] (B): Source control graph view

Back to [[Features Index]] | [[00 Index]]
