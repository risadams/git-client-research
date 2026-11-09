---
title: Use Case Catalog
description: Shared list of git client use cases, each with an ID, related feature pages, and the personas that need it.
tags: [personas, use-cases, rubric-input]
---

# Use Case Catalog

Every persona in [[Persona Index]] draws from this list, and the rubric will score each client against it. Use cases marked non-feature (cost, platform, procurement, support) depend on pricing, licensing, and vendor facts rather than on a feature page.

Evidence grades from [[Confidence Levels]] apply to the client facts used to score each use case.

| ID | Use case | Group | What it means | Related features | Evidence note |
|---|---|---|---|---|---|
| UC01 | First-run setup without the CLI | Core | Install, sign in to the host, and clone the first repository using only the GUI. | [[Hosting Integrations\|Hosting Integrations]] | Install steps and host sign-in flows are in each client note. |
| UC02 | Daily commit loop | Core | Review changes, stage selected hunks, commit, amend, push, pull. | [[Partial Staging\|Partial Staging]], [[Commit Amend\|Commit Amend]], [[Diff Viewer\|Diff Viewer]] | Nearly universal; differences are in speed and partial staging quality. |
| UC03 | Understand history visually | Core | Read branches, merges, and tags as a graph. | [[Commit Graph\|Commit Graph]] |   |
| UC04 | See the commands being run | Learning | See or copy the exact git command behind each action, or drop to a terminal from the app. | [[Command Transparency\|Command Transparency]], [[CLI Companion\|CLI Companion]], [[Built-in Terminal\|Built-in Terminal]] | Few clients document this. Grade L or B for most. |
| UC05 | Recover from mistakes | Safety | Undo a bad merge, reset, or rebase; find lost commits. | [[Undo and Redo\|Undo and Redo]], [[Reflog\|Reflog]], [[Stash\|Stash]] | Unlimited undo is rare. Reflog UIs are more common. |
| UC06 | Branch, merge, and resolve conflicts | Core | Create branches, merge, and resolve conflicts with a usable 3-way view. | [[Merge Conflict Resolver\|Merge Conflict Resolver]], [[Parallel Branches\|Parallel Branches]] |   |
| UC07 | Clean history before sharing | Pro | Interactive rebase, squash, reword, and fixup before opening a pull request. | [[Interactive Rebase\|Interactive Rebase]], [[History Editing\|History Editing]], [[Cherry-Pick\|Cherry-Pick]] |   |
| UC08 | Pull requests from the client | Collaboration | Create, view, check out, and review pull requests without leaving the app. | [[Pull Requests\|Pull Requests]], [[Hosting Integrations\|Hosting Integrations]] | Host coverage varies: GitHub, GitLab, Bitbucket, Azure DevOps. |
| UC09 | Triage outside contributions | Collaboration | Check out a contributor's branch, apply patches, cherry-pick, and merge with attribution. | [[Patches\|Patches]], [[Cherry-Pick\|Cherry-Pick]], [[Pull Requests\|Pull Requests]] |   |
| UC10 | Manage many repositories | Scale | Switch quickly between repositories or act across several at once. | [[Multi-Repo Workspaces\|Multi-Repo Workspaces]] |   |
| UC11 | Multiple identities and accounts | Scale | Use personal and work accounts, emails, and signing keys without mixing them up. | [[Multi-Account\|Multi-Account]], [[Git Config Respect\|Git Config Respect]] | Per-repo identity handling is a common pain point; see Open Questions. |
| UC12 | Signed commits and tags | Security | Sign with GPG or SSH keys and see verification status. | [[Commit Signing\|Commit Signing]] |   |
| UC13 | Avoid leaking secrets | Security | Warn before committing keys or tokens. | [[Secret Detection\|Secret Detection]] | Rare as a built-in feature. |
| UC14 | Work in a large repository | Scale | Stay responsive with tens of thousands of files or hundreds of thousands of commits. | [[Large Repo Performance\|Large Repo Performance]] | Only GitUI has measured numbers; see [[Benchmarks]]. |
| UC15 | Large and binary files | Scale | Use LFS, preview binary diffs, and avoid bloating the repository. | [[Git LFS\|Git LFS]], [[Image Diff\|Image Diff]], [[Rich File Preview\|Rich File Preview]] |   |
| UC16 | Worktrees and submodules | Pro | Work on several branches at once and handle nested repositories. | [[Worktrees\|Worktrees]], [[Submodules\|Submodules]] |   |
| UC17 | Stacked branches | Pro | Manage dependent branches as a stack and keep them rebased. | [[Stacked Branches\|Stacked Branches]] | Niche; few clients support it. |
| UC18 | Investigate regressions | Pro | Blame, file history, search, and bisect to find when a bug arrived. | [[Blame\|Blame]], [[File History\|File History]], [[History Search\|History Search]], [[Bisect\|Bisect]] |   |
| UC19 | Releases, tags, and project stats | Collaboration | Tag releases and view contributor and repository statistics. | [[Repository Statistics\|Repository Statistics]] | Weakly covered in the vault. |
| UC20 | Issue tracker linking | Collaboration | Link commits and branches to Jira, GitHub Issues, or similar. | [[Issue Tracker Links\|Issue Tracker Links]] | See [[Issue Tracker Traceability]]. |
| UC21 | AI assistance | Emerging | Generate commit messages, explain changes, and assist review. | [[AI Commit Messages\|AI Commit Messages]], [[AI Review and Explain\|AI Review and Explain]], [[Local AI\|Local AI]] | Whether AI helps or harms a learner is contested; treat as neutral for students. |
| UC22 | Working alongside AI coding agents | Emerging | Review, stage, and revert changes made by an agent in the same repository. | [[Agent Support\|Agent Support]] | Fast-moving; vendor claims need checking. |
| UC23 | Keyboard-driven speed and editor fit | Pro | Operate without a mouse and integrate with the editor or shell. | [[Keyboard Driven\|Keyboard Driven]], [[Editor Integration\|Editor Integration]], [[Shell Integration\|Shell Integration]] |   |
| UC24 | Respect repository and corporate conventions | Policy | Honor hooks, commit templates, git config, proxies, and credential helpers. | [[Git Config Respect\|Git Config Respect]] | A client that ignores hooks or config is a hazard on shared repositories. |
| UC25 | Central procurement and administration | Policy | Seat management, SSO, license server, audit trail, invoicing, and security review. | [[Enterprise Controls\|Enterprise Controls]] | See [[Enterprise Buying Checklist]]. |
| UC26 | Individual purchase logistics | Policy | Receipts, expense-friendly pricing, license usable on several machines, easy cancellation. | none (non-feature) | Pricing page and licence terms; see [[Pricing Landscape]]. |
| UC27 | Privacy, telemetry, and offline use | Policy | Control telemetry, run offline, keep code and prompts local. | [[No Telemetry\|No Telemetry]], [[Local AI\|Local AI]] |   |
| UC28 | Support, training, and onboarding | Policy | Vendor support, documentation, and the effort to onboard a new teammate. | none (non-feature) | Support terms are mostly not retrieved. |
| UC29 | Vendor and project viability | Policy | Likelihood the tool is maintained for several years. | none (non-feature) | See [[Vendors and Companies]] and [[Trends]]. |
| UC30 | Cost fits the persona | Fit | Free tier or price is acceptable for this persona's budget, including private repositories. | none (non-feature) | See [[Pricing Landscape]]. |
| UC31 | Runs on the persona's operating system | Fit | Native support for the persona's OS, including Linux where needed. | none (non-feature) | Platforms are in client frontmatter. |
| UC32 | Read-only observation | Fit | Follow branches, history, and activity without risking changes. | [[Commit Graph\|Commit Graph]], [[Repository Statistics\|Repository Statistics]] | Mostly met by the host website; a client adds little unless it has a safe read-only mode. |
| UC33 | Preview non-code files | Fit | Compare images, documents, and design files across versions. | [[Image Diff\|Image Diff]], [[Rich File Preview\|Rich File Preview]], [[Folder Compare\|Folder Compare]] | See [[Creative and Non-Developer Segment]]. |

## Personas by use case

| ID | Use case | Personas that need it |
|---|---|---|
| UC01 | First-run setup without the CLI | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Creative or Non-Developer\|P10]], [[Non-Coding Observer\|P12]] |
| UC02 | Daily commit loop | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Corporate User (Self-Purchased)\|P5]], [[Contractor or Consultant\|P7]], [[Monorepo Engineer\|P9]], [[Creative or Non-Developer\|P10]], [[Data or ML Practitioner\|P11]] |
| UC03 | Understand history visually | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Creative or Non-Developer\|P10]], [[Data or ML Practitioner\|P11]], [[Non-Coding Observer\|P12]] |
| UC04 | See the commands being run | [[Student Learning Git\|P1]], [[DevOps or SRE\|P8]] |
| UC05 | Recover from mistakes | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Creative or Non-Developer\|P10]], [[Data or ML Practitioner\|P11]] |
| UC06 | Branch, merge, and resolve conflicts | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]], [[Monorepo Engineer\|P9]], [[Creative or Non-Developer\|P10]], [[Data or ML Practitioner\|P11]] |
| UC07 | Clean history before sharing | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[DevOps or SRE\|P8]], [[Monorepo Engineer\|P9]] |
| UC08 | Pull requests from the client | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]] |
| UC09 | Triage outside contributions | [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]] |
| UC10 | Manage many repositories | [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]], [[DevOps or SRE\|P8]], [[Monorepo Engineer\|P9]] |
| UC11 | Multiple identities and accounts | [[Student Learning Git\|P1]], [[Open Source Solo Maintainer\|P3]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]] |
| UC12 | Signed commits and tags | [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]], [[DevOps or SRE\|P8]] |
| UC13 | Avoid leaking secrets | [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]], [[DevOps or SRE\|P8]], [[Data or ML Practitioner\|P11]] |
| UC14 | Work in a large repository | [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[DevOps or SRE\|P8]], [[Monorepo Engineer\|P9]], [[Data or ML Practitioner\|P11]] |
| UC15 | Large and binary files | [[Hobby Solo Developer\|P2]], [[Monorepo Engineer\|P9]], [[Creative or Non-Developer\|P10]], [[Data or ML Practitioner\|P11]] |
| UC16 | Worktrees and submodules | [[Open Source Team\|P4]], [[DevOps or SRE\|P8]], [[Monorepo Engineer\|P9]] |
| UC17 | Stacked branches | [[Open Source Solo Maintainer\|P3]], [[Monorepo Engineer\|P9]] |
| UC18 | Investigate regressions | [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Self-Purchased)\|P5]], [[DevOps or SRE\|P8]], [[Monorepo Engineer\|P9]], [[Non-Coding Observer\|P12]] |
| UC19 | Releases, tags, and project stats | [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Non-Coding Observer\|P12]] |
| UC20 | Issue tracker linking | [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]], [[Non-Coding Observer\|P12]] |
| UC21 | AI assistance | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Open Source Solo Maintainer\|P3]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]], [[DevOps or SRE\|P8]], [[Data or ML Practitioner\|P11]] |
| UC22 | Working alongside AI coding agents | [[DevOps or SRE\|P8]] |
| UC23 | Keyboard-driven speed and editor fit | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Corporate User (Self-Purchased)\|P5]], [[DevOps or SRE\|P8]], [[Monorepo Engineer\|P9]] |
| UC24 | Respect repository and corporate conventions | [[Open Source Team\|P4]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]], [[DevOps or SRE\|P8]], [[Monorepo Engineer\|P9]] |
| UC25 | Central procurement and administration | [[Corporate User (Mandated and Funded)\|P6]], [[Monorepo Engineer\|P9]] |
| UC26 | Individual purchase logistics | [[Corporate User (Self-Purchased)\|P5]], [[Contractor or Consultant\|P7]] |
| UC27 | Privacy, telemetry, and offline use | [[Hobby Solo Developer\|P2]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]] |
| UC28 | Support, training, and onboarding | [[Open Source Team\|P4]], [[Corporate User (Mandated and Funded)\|P6]] |
| UC29 | Vendor and project viability | [[Corporate User (Mandated and Funded)\|P6]] |
| UC30 | Cost fits the persona | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Self-Purchased)\|P5]], [[Corporate User (Mandated and Funded)\|P6]], [[Creative or Non-Developer\|P10]], [[Non-Coding Observer\|P12]] |
| UC31 | Runs on the persona's operating system | [[Student Learning Git\|P1]], [[Hobby Solo Developer\|P2]], [[Open Source Solo Maintainer\|P3]], [[Open Source Team\|P4]], [[Corporate User (Mandated and Funded)\|P6]], [[Contractor or Consultant\|P7]], [[DevOps or SRE\|P8]], [[Creative or Non-Developer\|P10]], [[Data or ML Practitioner\|P11]], [[Non-Coding Observer\|P12]] |
| UC32 | Read-only observation | [[Non-Coding Observer\|P12]] |
| UC33 | Preview non-code files | [[Creative or Non-Developer\|P10]], [[Data or ML Practitioner\|P11]] |

## Use case details

### UC01
First-run setup without the CLI: Install, sign in to the host, and clone the first repository using only the GUI.

### UC02
Daily commit loop: Review changes, stage selected hunks, commit, amend, push, pull.

### UC03
Understand history visually: Read branches, merges, and tags as a graph.

### UC04
See the commands being run: See or copy the exact git command behind each action, or drop to a terminal from the app.

### UC05
Recover from mistakes: Undo a bad merge, reset, or rebase; find lost commits.

### UC06
Branch, merge, and resolve conflicts: Create branches, merge, and resolve conflicts with a usable 3-way view.

### UC07
Clean history before sharing: Interactive rebase, squash, reword, and fixup before opening a pull request.

### UC08
Pull requests from the client: Create, view, check out, and review pull requests without leaving the app.

### UC09
Triage outside contributions: Check out a contributor's branch, apply patches, cherry-pick, and merge with attribution.

### UC10
Manage many repositories: Switch quickly between repositories or act across several at once.

### UC11
Multiple identities and accounts: Use personal and work accounts, emails, and signing keys without mixing them up.

### UC12
Signed commits and tags: Sign with GPG or SSH keys and see verification status.

### UC13
Avoid leaking secrets: Warn before committing keys or tokens.

### UC14
Work in a large repository: Stay responsive with tens of thousands of files or hundreds of thousands of commits.

### UC15
Large and binary files: Use LFS, preview binary diffs, and avoid bloating the repository.

### UC16
Worktrees and submodules: Work on several branches at once and handle nested repositories.

### UC17
Stacked branches: Manage dependent branches as a stack and keep them rebased.

### UC18
Investigate regressions: Blame, file history, search, and bisect to find when a bug arrived.

### UC19
Releases, tags, and project stats: Tag releases and view contributor and repository statistics.

### UC20
Issue tracker linking: Link commits and branches to Jira, GitHub Issues, or similar.

### UC21
AI assistance: Generate commit messages, explain changes, and assist review.

### UC22
Working alongside AI coding agents: Review, stage, and revert changes made by an agent in the same repository.

### UC23
Keyboard-driven speed and editor fit: Operate without a mouse and integrate with the editor or shell.

### UC24
Respect repository and corporate conventions: Honor hooks, commit templates, git config, proxies, and credential helpers.

### UC25
Central procurement and administration: Seat management, SSO, license server, audit trail, invoicing, and security review.

### UC26
Individual purchase logistics: Receipts, expense-friendly pricing, license usable on several machines, easy cancellation.

### UC27
Privacy, telemetry, and offline use: Control telemetry, run offline, keep code and prompts local.

### UC28
Support, training, and onboarding: Vendor support, documentation, and the effort to onboard a new teammate.

### UC29
Vendor and project viability: Likelihood the tool is maintained for several years.

### UC30
Cost fits the persona: Free tier or price is acceptable for this persona's budget, including private repositories.

### UC31
Runs on the persona's operating system: Native support for the persona's OS, including Linux where needed.

### UC32
Read-only observation: Follow branches, history, and activity without risking changes.

### UC33
Preview non-code files: Compare images, documents, and design files across versions.
