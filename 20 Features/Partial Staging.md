---
title: Partial Staging
group: Staging and commits
client_count: 13
tags: [feature, feature-group/staging-and-commits, feature/partial-staging]
---
# Partial Staging

**Group:** Staging and commits  
**Clients with this feature in my notes:** 13 of 66

## What it does
Choose individual hunks or single lines of a file to put in the next commit, instead of the whole file.

## Why it matters
Lets you split one messy working tree into several clean, focused commits.

## Git equivalent
`git add -p` (hunks), `git add -e` (line level)

## What to check when evaluating
Is line-level selection supported, or only hunk-level? Can you unstage a single line? Does it work with new (untracked) files?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[BeeBranch|BeeBranch]] (V): Staging by file, hunk, line; commit, amend, stash, tags, worktrees, submodules, patches
- [[Fork|Fork]] (V): Line-level staging, side-by-side diff, image diffs
- [[Git Revenge|Git Revenge]] (V): Staging by file, hunk, or line; commit, stash, branch, merge, rebase, cherry-pick, reset, revert, with undo
- [[git-gui and gitk|git-gui and gitk]] (B): git-gui: commit crafting, hunk and line staging
- [[GitFourchette|GitFourchette]] (S): Hunk and line staging, commits, branch management
- [[GitHub Desktop|GitHub Desktop]] (V): Visual staged and unstaged change review, partial-file staging
- [[GitQlient|GitQlient]] (S): Visual history, hunk staging, rebase
- [[LazyGit|LazyGit]] (L): Stage by line, interactive rebase, cherry-pick, bisect
- [[Magit|Magit]] (L): Hunk, region, and line-level staging
- [[Sourcetree|Sourcetree]] (V): Stage or discard at file, hunk, or line level
- [[Stage|Stage]] (S): Stage and unstage files or hunks
- [[Sublime Merge|Sublime Merge]] (L): Line-level staging, commit editing, blame, interactive rebase
- [[tig|tig]] (L): Blame, diff, stage hunks, log views

Back to [[Features Index]] | [[00 Index]]
