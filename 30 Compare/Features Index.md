---
title: Features Index
tags: [feature, moc]
---
# Features Index

51 features, normalized from the free-text feature lists in each client note. Each client note has a `features` property and `feature/...` tags, so you can click a tag in Obsidian to list every client with that feature.

> [!warning] Evidence, not a test report
> A feature is attached to a client only if that client's note mentions it. Thin notes (confidence L) will under-report. Treat counts as lower bounds. See [[#Verified-client matrix|verified-client matrix]] for the best-documented clients.

## Staging and commits
- [[Partial Staging|Partial Staging]] (13): Choose individual hunks or single lines of a file to put in the next commit, instead of the whole file.
- [[Commit Amend|Commit Amend]] (4): Fold new changes or a new message into the most recent commit from a button or menu.
- [[Stash|Stash]] (11): Park uncommitted changes on a shelf so you can switch context, then restore them later.
- [[Patches|Patches]] (2): Create, apply, or view patch files from within the app.
- [[Submodules|Submodules]] (11): Shows and manages repositories nested inside other repositories.
- [[Worktrees|Worktrees]] (6): Check out multiple branches at the same time into separate folders that share one repository.
- [[Git LFS|Git LFS]] (9): Support for Git Large File Storage: big binaries stored outside the normal object database.

## History and investigation
- [[Commit Graph|Commit Graph]] (24): A visual map of commits, branches and merges drawn as lines.
- [[History Search|History Search and Filtering]] (6): Search commits by message, author, content, file, or date, often with filters.
- [[Blame|Blame]] (10): Shows which commit and author last changed each line of a file.
- [[File History|File History]] (4): Lists the commits that touched a given file or folder and lets you diff across them.
- [[Reflog|Reflog and Recovery]] (3): Browse where branch tips used to point, so you can recover lost commits after a bad reset or deleted branch.
- [[Bisect|Bisect]] (3): Guided binary search through history to find the commit that introduced a bug.
- [[Repository Statistics|Repository Statistics and Visualizations]] (2): Charts and summaries such as contributor heatmaps, repository size, branch/tag counts, code statistics.

## Branching models and history rewriting
- [[Interactive Rebase|Rebase and Interactive Rebase]] (17): Replay commits onto a new base, and optionally reorder, squash, edit, or drop them using a visual editor.
- [[Cherry-Pick|Cherry-Pick]] (5): Copy specific commits from one branch onto another.
- [[Undo and Redo|Undo and Redo]] (5): Reverts the effect of a Git operation (commit, merge, branch delete) with a button, often with redo.
- [[Drag and Drop|Drag and Drop Operations]] (3): Perform merges, rebases, cherry-picks, or reorders by dragging branches or commits onto each other.
- [[Stacked Branches|Stacked Branches]] (2): Manage a chain of dependent branches (each built on the previous) and keep them in sync when the base changes.
- [[Parallel Branches|Parallel Branches]] (1): Work on several branches at once in the same working directory, assigning changes to each, without switching.
- [[History Editing|Commit Editing and History Surgery]] (3): Move changes between commits, split, squash, absorb, or reorder without a manual rebase.
- [[Git-Flow|Git-Flow Support]] (4): Built-in helpers for the git-flow branching model (feature, release, hotfix branches).

## Diff, compare and merge
- [[Diff Viewer|Diff Viewer]] (17): Shows what changed in a file, either inline or side by side.
- [[Syntax Highlighting|Syntax Highlighting in Diffs]] (2): Colors code in diffs by language.
- [[Image Diff|Image and Binary Diff]] (4): Visual comparison of images (swipe, fade, side by side) and sometimes binary or hex views.
- [[Merge Conflict Resolver|Merge Conflict Resolver (3-way)]] (16): A dedicated view showing your side, their side, and the result, with controls to pick or edit lines.
- [[Folder Compare|Folder and Directory Compare]] (2): Compare two folders, including folders that are not Git repositories.
- [[Rich File Preview|Rich File Preview]] (2): Renders Markdown, PDF, CSV, JSON, Mermaid, or similar next to the raw diff.

## Hosting and workflow integrations
- [[Pull Requests|Pull and Merge Request Integration]] (8): Create, review, comment on, and merge pull or merge requests without leaving the app.
- [[Hosting Integrations|Hosting Service Integrations]] (15): Sign in to GitHub, GitLab, Bitbucket, Azure DevOps, or Gitea to clone, list repos, and see status.
- [[Issue Tracker Links|Issue Tracker Integration]] (3): Link commits and branches to Jira, Linear, Trello, or similar issues.
- [[Multi-Repo Workspaces|Multi-Repository Management]] (4): Open, group, and act on many repositories at once (tabs, workspaces, dashboards).
- [[Multi-Account|Multiple Accounts]] (1): Sign in with more than one account for the same host (for example personal and work GitHub).

## Interface and ergonomics
- [[Shell Integration|Shell and File Manager Integration]] (3): Adds Git actions and status icons to the operating system file manager (Explorer, Finder).
- [[Editor Integration|Editor and IDE Integration]] (9): Git features embedded in an editor or IDE rather than a standalone window.
- [[Keyboard Driven|Keyboard-Driven Workflow]] (11): Operate the app with shortcuts, a command palette, or Magit-style mnemonics instead of the mouse.
- [[Built-in Terminal|Built-in Terminal]] (1): A terminal pane inside the GUI that opens in the repo directory.
- [[CLI Companion|CLI Companion]] (6): A command-line tool shipped with the GUI so both operate on the same repos.
- [[Themes|Themes and Dark Mode]] (4): Light, dark, and custom color themes.
- [[Command Transparency|Shows Equivalent Git Commands]] (1): Displays the actual Git command behind each GUI action or provides a command log.

## AI assistance
- [[AI Commit Messages|AI Commit Messages]] (5): Generates a commit message from the staged diff.
- [[AI Review and Explain|AI Review, Explain, and Summaries]] (5): AI features that explain commits and branches, summarize differences, review code, or help resolve conflicts.
- [[Agent Support|AI Coding Agent Support]] (3): Tooling aimed at AI coding agents, such as scriptable JSON output, agent skills, or integrations with agent CLIs.
- [[Local AI|Local-Only AI]] (1): AI features that run on your machine (for example via Ollama) so code is not sent to a cloud service.

## Privacy, security and enterprise
- [[Commit Signing|Commit Signature Verification]] (2): Shows whether commits are GPG, SSH, or S/MIME signed and verified.
- [[No Telemetry|No Account, No Telemetry]] (2): Works without a vendor account and sends no usage analytics.
- [[Secret Detection|Secret and Leak Detection]] (1): Scans staged changes for passwords, tokens and keys before you commit.
- [[Enterprise Controls|Enterprise, SSO, and License Management]] (2): Single sign-on, centralized license servers, managed deployment, invoicing.
- [[Git Config Respect|Respects Existing Git Config, Hooks, and Credentials]] (3): Uses your installed git and its configuration, hooks, credential helpers, and SSH agent instead of reimplementing them.

## Scale and compatibility
- [[Large Repo Performance|Large-Repository Performance]] (3): Designed or optimized to stay responsive on huge histories or working trees.
- [[Mercurial and SVN|Mercurial and SVN Support]] (2): Can work with non-Git version control systems alongside Git.

## Verified-client matrix

Columns are the clients whose official pages I checked on 2026-11-09 (confidence V). A tick means the page or my verified notes mention the feature. A blank means not mentioned, not 'unsupported'. Only features with at least one tick are shown.

| Feature | GitButler | GitHub Desktop | GitKraken Desktop | SmartGit | Sourcetree | TortoiseGit | Tower | BeeBranch | Fork | ForkPlus | Git Revenge | GitComet | Gitember | rgitui |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [[Partial Staging\|Partial Staging]] |  | ✓ |  |  | ✓ |  |  | ✓ | ✓ |  | ✓ |  |  |  |
| [[Commit Amend\|Commit Amend]] | ✓ | ✓ |  |  |  |  |  | ✓ | ✓ |  |  |  |  |  |
| [[Stash\|Stash]] |  | ✓ | ✓ |  | ✓ | ✓ |  | ✓ |  |  | ✓ |  | ✓ | ✓ |
| [[Patches\|Patches]] |  |  |  |  |  |  |  | ✓ |  |  |  |  |  |  |
| [[Submodules\|Submodules]] |  |  |  | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |  |  |  |  | ✓ |
| [[Worktrees\|Worktrees]] |  |  |  |  |  |  |  | ✓ |  |  |  | ✓ |  | ✓ |
| [[Git LFS\|Git LFS]] |  |  | ✓ | ✓ | ✓ |  | ✓ |  | ✓ |  |  |  | ✓ |  |
| [[Commit Graph\|Commit Graph]] |  |  | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |  |  |  |  | ✓ | ✓ |
| [[History Search\|History Search and Filtering]] |  |  |  | ✓ | ✓ |  |  |  |  |  |  |  | ✓ | ✓ |
| [[Blame\|Blame]] |  |  |  |  |  | ✓ |  |  | ✓ |  | ✓ |  |  | ✓ |
| [[File History\|File History]] |  |  |  |  |  |  |  |  | ✓ |  | ✓ |  |  | ✓ |
| [[Reflog\|Reflog and Recovery]] |  |  |  |  |  |  |  |  | ✓ |  | ✓ |  |  | ✓ |
| [[Bisect\|Bisect]] |  |  |  |  |  | ✓ |  |  |  |  |  |  |  | ✓ |
| [[Repository Statistics\|Repository Statistics and Visualizations]] |  |  |  |  |  |  |  |  |  | ✓ |  |  | ✓ |  |
| [[Interactive Rebase\|Rebase and Interactive Rebase]] |  |  |  |  | ✓ | ✓ | ✓ | ✓ | ✓ |  | ✓ |  | ✓ | ✓ |
| [[Cherry-Pick\|Cherry-Pick]] |  | ✓ |  |  | ✓ |  | ✓ |  |  |  | ✓ |  |  |  |
| [[Undo and Redo\|Undo and Redo]] | ✓ |  |  |  |  |  | ✓ | ✓ |  |  | ✓ |  |  |  |
| [[Drag and Drop\|Drag and Drop Operations]] |  | ✓ |  |  |  |  | ✓ |  |  |  |  |  |  |  |
| [[Stacked Branches\|Stacked Branches]] | ✓ |  |  |  |  |  | ✓ |  |  |  |  |  |  |  |
| [[Parallel Branches\|Parallel Branches]] | ✓ |  |  |  |  |  |  |  |  |  |  |  |  |  |
| [[History Editing\|Commit Editing and History Surgery]] | ✓ | ✓ |  |  |  |  |  |  |  |  |  |  |  |  |
| [[Git-Flow\|Git-Flow Support]] |  |  | ✓ | ✓ | ✓ |  |  |  | ✓ |  |  |  |  |  |
| [[Diff Viewer\|Diff Viewer]] |  | ✓ |  |  |  | ✓ |  |  | ✓ | ✓ | ✓ | ✓ | ✓ |  |
| [[Syntax Highlighting\|Syntax Highlighting in Diffs]] |  | ✓ |  |  |  |  |  |  |  |  |  |  |  |  |
| [[Image Diff\|Image and Binary Diff]] |  | ✓ |  |  |  |  |  |  | ✓ | ✓ | ✓ |  |  |  |
| [[Merge Conflict Resolver\|Merge Conflict Resolver (3-way)]] |  |  | ✓ | ✓ |  | ✓ | ✓ |  | ✓ |  | ✓ | ✓ | ✓ | ✓ |
| [[Folder Compare\|Folder and Directory Compare]] |  |  |  |  |  |  |  |  |  |  |  |  | ✓ |  |
| [[Rich File Preview\|Rich File Preview]] |  |  |  |  |  |  |  |  |  |  | ✓ |  |  |  |
| [[Pull Requests\|Pull and Merge Request Integration]] |  | ✓ | ✓ | ✓ |  |  | ✓ |  |  |  |  |  | ✓ | ✓ |
| [[Hosting Integrations\|Hosting Service Integrations]] |  | ✓ | ✓ | ✓ |  |  | ✓ | ✓ | ✓ |  |  | ✓ | ✓ | ✓ |
| [[Issue Tracker Links\|Issue Tracker Integration]] |  |  | ✓ |  |  |  |  |  |  |  |  |  | ✓ | ✓ |
| [[Multi-Repo Workspaces\|Multi-Repository Management]] |  |  | ✓ |  |  |  |  |  |  |  |  | ✓ | ✓ | ✓ |
| [[Shell Integration\|Shell and File Manager Integration]] |  |  |  |  |  | ✓ |  |  |  |  |  |  |  |  |
| [[Keyboard Driven\|Keyboard-Driven Workflow]] |  |  |  |  |  |  |  |  |  |  |  |  |  | ✓ |
| [[Built-in Terminal\|Built-in Terminal]] |  |  | ✓ |  |  |  |  |  |  |  |  |  |  |  |
| [[CLI Companion\|CLI Companion]] | ✓ |  |  |  |  |  |  |  |  |  |  | ✓ |  |  |
| [[Themes\|Themes and Dark Mode]] |  |  |  |  |  |  |  |  |  | ✓ |  | ✓ |  | ✓ |
| [[Command Transparency\|Shows Equivalent Git Commands]] |  |  |  |  |  |  |  |  |  |  |  |  | ✓ |  |
| [[AI Commit Messages\|AI Commit Messages]] |  | ✓ | ✓ |  |  |  |  |  |  | ✓ |  |  | ✓ | ✓ |
| [[AI Review and Explain\|AI Review, Explain, and Summaries]] | ✓ |  | ✓ |  |  |  |  |  |  | ✓ |  |  | ✓ |  |
| [[Agent Support\|AI Coding Agent Support]] | ✓ |  |  |  |  |  |  |  |  |  | ✓ | ✓ |  |  |
| [[Local AI\|Local-Only AI]] |  |  |  |  |  |  |  |  |  |  |  |  | ✓ |  |
| [[Commit Signing\|Commit Signature Verification]] |  |  |  |  |  |  |  |  |  |  | ✓ | ✓ |  |  |
| [[No Telemetry\|No Account, No Telemetry]] |  |  |  |  |  |  |  | ✓ |  |  | ✓ |  |  |  |
| [[Secret Detection\|Secret and Leak Detection]] |  |  |  |  |  |  |  |  |  |  |  |  | ✓ |  |
| [[Enterprise Controls\|Enterprise, SSO, and License Management]] |  |  |  |  |  |  | ✓ | ✓ |  |  |  |  |  |  |
| [[Git Config Respect\|Respects Existing Git Config, Hooks, and Credentials]] |  |  |  | ✓ |  |  |  | ✓ |  |  | ✓ |  |  |  |
| [[Large Repo Performance\|Large-Repository Performance]] |  |  |  |  |  |  |  | ✓ |  |  | ✓ |  |  |  |
| [[Mercurial and SVN\|Mercurial and SVN Support]] |  |  |  | ✓ | ✓ |  |  |  |  |  |  |  |  |  |

Back to [[Home]] | [[00 Index]]
