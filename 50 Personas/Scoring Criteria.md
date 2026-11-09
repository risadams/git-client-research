---
title: Scoring Criteria
description: "What earns 0u, 0, 1, 2, or 3 for each of the 33 use cases, with the rules the pilot scoring used."
tags: [personas, rubric, criteria]
---

# Scoring Criteria

Part of the rubric in [[Scoring Rubric]]. Use cases are defined in [[Use Case Catalog]]. Scores for the pilot set are in [[Score Matrix]] and results by persona in [[Persona Results]].

## Method

Each score is derived from what the vault documents, using a fixed rule, so another pass gives the same answer. Judgment enters only through the override list in [[Score Matrix]].

| Score | Meaning for feature-based use cases |
|---|---|
| 0u | None of the relevant features are documented. Unknown, not "unsupported" |
| 0 | Evidence the client does not support it (used only where a rule can show absence, such as a missing operating system) |
| 1 | Some relevant features are documented, but not all core features |
| 2 | All core features documented |
| 3 | All core and all extended features documented, **or** an override with a tested or explicit standout |

**Consequences to keep in mind.**
- A use case with no extended features can reach 3 only by override.
- Thin notes (confidence L, B, S) under-report features, so their scores are floors. That is the reason the rubric also reports a ceiling and an unknown count ([[Scoring Rubric]]).
- A 2 means "documented", not "tested and good". Quality needs hands-on testing (grade T).
- The evidence grade in each cell is the client's confidence letter ([[Confidence Levels]]). For grade L the feature text is unverified.

## Feature-based and special rules

| ID | Use case | Rule type | Rule | 3 requires |
|---|---|---|---|---|
| UC01 | First-run setup without the CLI | category and tags | 1 = GUI-style category (desktop, IDE, shell, bundled, mobile). 2 = GUI category and `hosting-integrations`. 0 = Terminal UI (launched from a terminal). 3 = override only (needs a first-run test). | override only |
| UC02 | Daily commit loop | feature tags | Core: `partial-staging`, `diff-viewer`. Extended: `commit-amend`, `stash`. | core + all extended |
| UC03 | Understand history visually | feature tags | Core: `commit-graph`. Extended: `history-search`. | core + all extended |
| UC04 | See the commands being run | feature tags | Core: `command-transparency`. Extended: `cli-companion`, `built-in-terminal`. | core + all extended |
| UC05 | Recover from mistakes | feature tags | Core: `undo-and-redo`. Extended: `reflog`. | core + all extended |
| UC06 | Branch, merge, and resolve conflicts | feature tags | Core: `merge-conflict-resolver`. Extended: `drag-and-drop`. | core + all extended |
| UC07 | Clean history before sharing | feature tags | Core: `interactive-rebase`. Extended: `history-editing`, `cherry-pick`. | core + all extended |
| UC08 | Pull requests from the client | feature tags | Core: `pull-requests`. Extended: `hosting-integrations`. | core + all extended |
| UC09 | Triage outside contributions | feature tags | Core: `pull-requests`, `cherry-pick`. Extended: `patches`. | core + all extended |
| UC10 | Manage many repositories | feature tags | Core: `multi-repo-workspaces`. Extended: none. | override only |
| UC11 | Multiple identities and accounts | feature tags | Core: `multi-account`. Extended: `git-config-respect`. | core + all extended |
| UC12 | Signed commits and tags | feature tags | Core: `commit-signing`. Extended: none. | override only |
| UC13 | Avoid leaking secrets | feature tags | Core: `secret-detection`. Extended: none. | override only |
| UC14 | Work in a large repository | feature tags | Core: `large-repo-performance`. Extended: none. | override only |
| UC15 | Large and binary files | feature tags | Core: `git-lfs`, `image-diff`. Extended: `rich-file-preview`. | core + all extended |
| UC16 | Worktrees and submodules | feature tags | Core: `worktrees`, `submodules`. Extended: `parallel-branches`. | core + all extended |
| UC17 | Stacked branches | feature tags | Core: `stacked-branches`. Extended: none. | override only |
| UC18 | Investigate regressions | feature tags | Core: `blame`, `file-history`. Extended: `history-search`, `bisect`. | core + all extended |
| UC19 | Releases, tags, and project stats | feature tags | Core: `repository-statistics`. Extended: none. | override only |
| UC20 | Issue tracker linking | feature tags | Core: `issue-tracker-links`. Extended: none. | override only |
| UC21 | AI assistance | feature tags | Core: `ai-commit-messages`. Extended: `ai-review-and-explain`, `local-ai`. | core + all extended |
| UC22 | Working alongside AI coding agents | feature tags | Core: `agent-support`. Extended: none. | override only |
| UC23 | Keyboard-driven speed and editor fit | feature tags | Core: `keyboard-driven`. Extended: `editor-integration`, `shell-integration`. | core + all extended |
| UC24 | Respect repository and corporate conventions | feature tags | Core: `git-config-respect`. Extended: none. | override only |
| UC25 | Central procurement and administration | feature tags | Core: `enterprise-controls`. Extended: none. | override only |
| UC26 | Individual purchase logistics | cost class | 3 = free. 2 = free but unverified. Otherwise 0u: license terms (machines, receipts, cancellation) are not retrieved. | override only |
| UC27 | Privacy, telemetry, and offline use | feature tags | Core: `no-telemetry`. Extended: `local-ai`. | core + all extended |
| UC28 | Support, training, and onboarding | manual | Not scorable from the vault. 0u until vendor support terms or a hands-on test exist. | override only |
| UC29 | Vendor and project viability | status and vendor page | 0 = discontinued. 0u = too new. 1 = maintained. 2 = maintained and a company or organization appears on [[Vendors and Companies]]. | override only |
| UC30 | Cost fits the persona | cost class x persona | See cost table below. Scored per persona, not per client. | see table |
| UC31 | Runs on the persona's operating system | platforms x persona | See platform rules below. Scored per persona, not per client. | see table |
| UC32 | Read-only observation | manual | Not scorable from the vault. 0u until a hands-on test exists. | override only |
| UC33 | Preview non-code files | feature tags | Core: `image-diff`, `rich-file-preview`. Extended: `folder-compare`. | core + all extended |

Tag slugs match the pages in `20 Features`.

## Cost (UC30), scored per persona

Each client has a cost class, read from the Cost row of its note.

| Class | Meaning |
|---|---|
| F | Free, stated |
| FU | Free but unverified (no price stated, or "presumably free") |
| FL | Free tier with limits, plus paid tiers |
| O | One-time purchase |
| S | Subscription (per user, per year or month) |
| U | Unknown or conditional |

Budget profile by persona: **free** (P1, P2, P3, P4, P12), **personal** (P5, P7, P8, P10, P11), **company** (P6, P9).

| Class | Free profile | Personal profile | Company profile |
|---|---|---|---|
| F | 3 | 3 | 3 |
| FU | 2 | 2 | 2 |
| FL | 2 (1 for P2 if the free tier excludes private repos) | 1 | 2 |
| O | 1 (2 for P2) | 2 | 3 |
| S | 1 | 2 | 2 |
| U | 0u | 0u | 0u |

A client with a free path that covers the persona scores 3 in the free profile. Qualifying free paths: students and education (P1), non-commercial (P2), open source (P3, P4). Source: each client note; see [[Pricing Landscape]].

## Platform (UC31), scored per persona

Operating systems counted: Windows, macOS, Linux. Exclusions: "no Linux" and "Linux only via community fork" do not count as Linux, and experimental macOS does not count as macOS.

| Persona | Rule |
|---|---|
| P8 | Linux required. 0 without Linux. With Linux: 3 if all three OSes, otherwise 2 |
| P10 | macOS or Windows required. 3 for both, 2 for one, 0 for neither |
| P6 | Managed fleet. 3 for macOS and Windows, 1 for one, 0 for neither |
| All others | Number of the three OSes supported (0 to 3) |

## Gate states used in the pilot

Only gates that the vault can evaluate are Triggered or Clear. The rest are Unknown. Rules follow [[Dealbreaker Gates]].

| Gate | Clear when | Triggered when |
|---|---|---|
| G01 | Free or free-tier class, or a qualifying free path covers the persona | Paid-only class (O or S) with no qualifying free path |
| G02 | Class F, O, or S | Free tier limited to public repos (GitKraken Community) |
| G03 | Class F, O, or FL, or a non-commercial path covers P2 | Subscription class with no qualifying path |
| G06 | `pull-requests` or `patches` tag | never by rule |
| G07 | `commit-signing` tag | never by rule |
| G08 | `git-config-respect` tag | never by rule |
| G10 | `no-telemetry` tag | never by rule |
| G12 | `enterprise-controls` tag | never by rule |
| G13 | GitKraken Desktop (SOC 2 Type II under NDA) | never by rule |
| G14 | `multi-account` or `git-config-respect` tag | never by rule |
| G15 | OS requirement met | Required OS missing |
| G16 | Terminal UI, or `cli-companion`, `shell-integration`, or `built-in-terminal` tag | never by rule |
| G17 | GitUI (tested) | never by rule |
| G19 | `git-lfs`, `image-diff`, or `rich-file-preview` tag | never by rule |
| G20 | `rich-file-preview` tag | never by rule |
| G22 | `command-transparency` or `commit-graph` tag | never by rule |
| G23 | `undo-and-redo` or `reflog` tag | never by rule |
| Others | never by rule | never by rule |

## Limits of the pilot

- 27 clients only: those with audience ratings in [[Audience Guide]].
- Features come from tags that a regex attached to each note's feature text ([[Methodology and Gaps]]).
- Judgment-heavy use cases (support, observe, first-run quality) are all 0u until someone tests them.
- Several Must use cases for P6 (procurement, support) depend on vendor facts not yet retrieved ([[Enterprise Buying Checklist]]).
