---
title: Rebase and Interactive Rebase
group: Branching models and history rewriting
client_count: 17
tags: [feature, feature-group/branching-models-and-history-rewriting, feature/interactive-rebase]
---
# Rebase and Interactive Rebase

**Group:** Branching models and history rewriting  
**Clients with this feature in my notes:** 17 of 66

## What it does
Replay commits onto a new base, and optionally reorder, squash, edit, or drop them using a visual editor.

## Why it matters
Keeps history clean before sharing; the most error-prone Git task to do by hand.

## Git equivalent
`git rebase`, `git rebase -i`

## What to check when evaluating
Is there a drag-and-drop todo list? How are conflicts mid-rebase presented? Can you abort or continue cleanly?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[BeeBranch|BeeBranch]] (V): Merge and rebase with intermediate states, undo and redo limited to reversible Git operations, crash-recovery journal
- [[Fork|Fork]] (V): Interactive rebase, merge-conflict helper and resolver
- [[Git Extensions|Git Extensions]] (L): Commit graph, stash, rebase, submodules
- [[Git Revenge|Git Revenge]] (V): Staging by file, hunk, or line; commit, stash, branch, merge, rebase, cherry-pick, reset, revert, with undo
- [[Gitember|Gitember]] (V): Clone, commit, push, pull, fetch, branch, merge, rebase, stash, tag over SSH or HTTPS
- [[GitLens (VS Code)|GitLens (VS Code)]] (B): Interactive rebase editor
- [[GitQlient|GitQlient]] (S): Visual history, hunk staging, rebase
- [[Gitu|Gitu]] (S): Commit, push, pull, fetch, rebase, stash
- [[JetBrains IDE Git|JetBrains IDE Git]] (B): Commit tool window, shelves, interactive rebase, log with graph
- [[LazyGit|LazyGit]] (L): Stage by line, interactive rebase, cherry-pick, bisect
- [[Magit|Magit]] (L): Interactive rebase, worktrees, submodules, forge integration via Forge package
- [[rgitui|rgitui]] (V): Staging, commit, branch, tag, stash, remotes, interactive rebase, conflict resolution
- [[SourceGit|SourceGit]] (L): Graph, interactive rebase, LFS, worktrees, submodules
- [[Sourcetree|Sourcetree]] (V): Interactive rebase, stash, cherry-pick
- [[Sublime Merge|Sublime Merge]] (L): Line-level staging, commit editing, blame, interactive rebase
- [[TortoiseGit|TortoiseGit]] (V): Rebase, stash, bisect, submodules
- [[Tower|Tower]] (V): Drag and drop everywhere (merge, rebase, cherry-pick)

Back to [[Features Index]] | [[00 Index]]
