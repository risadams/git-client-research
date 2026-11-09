---
title: Dealbreaker Gates
description: Definitions of the 25 gates that flag a client for a persona, with tri-state rules and evidence requirements.
tags: [personas, rubric, gates]
---

# Dealbreaker Gates

Decided 2026-11-09: gates **flag** a client for a persona. They never exclude it and never change its score. See [[Scoring Rubric]] for how flags are reported. Persona context is in [[Persona Index]].

## Rules

1. **Three states per client and gate.** Triggered (evidence shows the condition), Clear (evidence shows it does not apply), Unknown (no evidence).
2. **Absence of evidence is Unknown, not Triggered.** The vault already treats a missing feature tag as "no evidence", not "unsupported" (see [[Methodology and Gaps]]). A feature-based gate is Triggered only on an explicit statement of the limitation, or a test.
3. **Evidence grades apply.** Each state records its grade (V, L, B, S, T from [[Confidence Levels]]). A Triggered state from a grade S or B source is marked provisional.
4. **Thresholds are provisional.** G17 uses numbers I chose (10 s, 2 GB). Edit them on this page.
5. **A gate belongs to a persona, not to a client.** The same client can be flagged for P2 and Clear for P6.

## Gate list

| ID | Gate | Personas |
|---|---|---|
| [[Dealbreaker Gates#G01\|G01]] | No free, education, or open-source path | P1, P3, P4 |
| [[Dealbreaker Gates#G02\|G02]] | Free tier excludes private repositories | P2 |
| [[Dealbreaker Gates#G03\|G03]] | Subscription-only licensing | P2 |
| [[Dealbreaker Gates#G04\|G04]] | Mandatory account for local use | P2 |
| [[Dealbreaker Gates#G05\|G05]] | License tied to one machine | P5, P7 |
| [[Dealbreaker Gates#G06\|G06]] | No pull request checkout or patch apply | P3 |
| [[Dealbreaker Gates#G07\|G07]] | Commit signing unsupported or bypassed | P3, P4 |
| [[Dealbreaker Gates#G08\|G08]] | Ignores repository hooks, templates, or git configuration | P4 |
| [[Dealbreaker Gates#G09\|G09]] | Cannot authenticate to enterprise or self-hosted hosts | P5, P6 |
| [[Dealbreaker Gates#G10\|G10]] | Data leaves the machine with no user control | P5, P7 |
| [[Dealbreaker Gates#G11\|G11]] | No central control of telemetry and AI | P6 |
| [[Dealbreaker Gates#G12\|G12]] | No single sign-on or central administration | P6 |
| [[Dealbreaker Gates#G13\|G13]] | No vendor security documentation | P6 |
| [[Dealbreaker Gates#G14\|G14]] | No per-repository identity separation | P7 |
| [[Dealbreaker Gates#G15\|G15]] | No native build for the persona's operating system | P8, P10 |
| [[Dealbreaker Gates#G16\|G16]] | Not usable from a terminal or remote session | P8 |
| [[Dealbreaker Gates#G17\|G17]] | Unusable on large repositories | P9 |
| [[Dealbreaker Gates#G18\|G18]] | Ignores sparse checkout or partial clone | P9 |
| [[Dealbreaker Gates#G19\|G19]] | Cannot handle binary files | P10 |
| [[Dealbreaker Gates#G20\|G20]] | No useful diff for notebooks or large files | P11 |
| [[Dealbreaker Gates#G21\|G21]] | Needs the command line for ordinary tasks | P10 |
| [[Dealbreaker Gates#G22\|G22]] | Hides concepts with no way to see more | P1 |
| [[Dealbreaker Gates#G23\|G23]] | No undo and no warning before destructive actions | P1 |
| [[Dealbreaker Gates#G24\|G24]] | No safe read-only mode | P12 |
| [[Dealbreaker Gates#G25\|G25]] | Needs developer concepts to get started | P12 |

## Gates by persona

| Persona | Gates |
|---|---|
| P1 | G01, G22, G23 |
| P2 | G02, G03, G04 |
| P3 | G01, G06, G07 |
| P4 | G01, G07, G08 |
| P5 | G05, G09, G10 |
| P6 | G11, G12, G13 |
| P7 | G10, G14 |
| P8 | G15, G16 |
| P9 | G17, G18 |
| P10 | G19, G21 |
| P11 | G20 |
| P12 | G24, G25 |

## Gate definitions

### G01
**No free, education, or open-source path**

- Test: The persona cannot use the client without paying, and no free tier, education license, or open-source license applies.
- Triggered when: The official pricing or license page shows no free tier, and no education or open-source program covers the persona.
- Clear when: A free tier covers the persona's use, or a documented education or open-source program applies.
- Evidence: Pricing page (V), git-scm.com listing (L), [[Pricing Landscape]]. Open-source and education terms are not verified for most vendors, so expect Unknown.
- Personas: P1, P3, P4

### G02
**Free tier excludes private repositories**

- Test: The free tier works only with public remotes or public repositories.
- Triggered when: The vendor states the free tier is limited to public repositories (for example GitKraken Community: local repositories and public remotes only).
- Clear when: Free tier supports private repositories, or the client is free without that limit.
- Evidence: Pricing page (V), [[Pricing Landscape]].
- Personas: P2

### G03
**Subscription-only licensing**

- Test: The only way to use the client beyond a trial is a recurring subscription.
- Triggered when: No free tier and no one-time purchase is offered.
- Clear when: A free tier or one-time purchase exists.
- Evidence: Pricing page (V), [[Pricing Landscape]].
- Personas: P2

### G04
**Mandatory account for local use**

- Test: Core local work (open, commit, branch) requires creating or signing in to a vendor account.
- Triggered when: The vendor states or demonstrates that sign-in is required before local use.
- Clear when: Local use works without a vendor account.
- Evidence: Install flow and vendor docs. Test (T) is the best evidence; reports (S) are provisional.
- Personas: P2

### G05
**License tied to one machine**

- Test: The license cannot be used on the persona's several machines without extra cost.
- Triggered when: License terms limit use to one device or charge per device.
- Clear when: License allows use on several of the owner's machines.
- Evidence: License terms and EULA (V). Mostly not retrieved.
- Personas: P5, P7

### G06
**No pull request checkout or patch apply**

- Test: The client cannot check out a contributor's branch or pull request, and cannot apply a patch.
- Triggered when: The client has no such function (stated limitation or tested).
- Clear when: Either function is present and documented.
- Evidence: Feature pages [[Pull Requests]] and [[Patches]]. A missing tag is Unknown, not Triggered.
- Personas: P3

### G07
**Commit signing unsupported or bypassed**

- Test: The client cannot sign commits and tags, or ignores the configured signing setup.
- Triggered when: Stated or tested: signing not supported, or configured signing is not used.
- Clear when: Signing works with the user's configured GPG or SSH setup.
- Evidence: Feature page [[Commit Signing]]; test (T) is best.
- Personas: P3, P4

### G08
**Ignores repository hooks, templates, or git configuration**

- Test: Hooks, commit templates, or `.gitconfig` settings are not honored, so conventions fail silently.
- Triggered when: Stated or tested: the client bypasses hooks or ignores config it should honor.
- Clear when: Hooks, templates, and config are honored.
- Evidence: Feature page [[Git Config Respect]]; test (T) is best.
- Personas: P4

### G09
**Cannot authenticate to enterprise or self-hosted hosts**

- Test: The client cannot sign in to the persona's host (SSO, enterprise hosting, self-hosted servers).
- Triggered when: Stated: the persona's host type is not supported.
- Clear when: The host type is supported or credentials flow through standard git credential helpers.
- Evidence: Feature page [[Hosting Integrations]] and vendor docs.
- Personas: P5, P6

### G10
**Data leaves the machine with no user control**

- Test: Code, prompts, or usage data are sent to a third party and the user cannot turn it off.
- Triggered when: Stated: AI features or telemetry cannot be disabled by the user.
- Clear when: AI and telemetry can be disabled by the user, or do not exist.
- Evidence: Feature pages [[No Telemetry]] and [[Local AI]]; vendor privacy docs.
- Personas: P5, P7

### G11
**No central control of telemetry and AI**

- Test: An administrator cannot disable telemetry or AI for all users.
- Triggered when: Stated: no organization-level control.
- Clear when: Organization-level control exists.
- Evidence: Feature page [[Enterprise Controls]]; [[Enterprise Buying Checklist]].
- Personas: P6

### G12
**No single sign-on or central administration**

- Test: No SSO, seat management, or license administration for an organization.
- Triggered when: Stated: SSO or central administration unavailable.
- Clear when: SSO and seat or license administration exist.
- Evidence: [[Enterprise Controls]], [[Enterprise Buying Checklist]]. Most vendors are not retrieved.
- Personas: P6

### G13
**No vendor security documentation**

- Test: No security report, attestation, or review package is available to a buyer.
- Triggered when: Vendor states none exists or declines to provide one.
- Clear when: A report such as SOC 2 Type II is available, possibly under NDA.
- Evidence: Vendor trust page; [[Enterprise Buying Checklist]].
- Personas: P6

### G14
**No per-repository identity separation**

- Test: The user cannot set a different name, email, account, or signing key per repository.
- Triggered when: Stated or tested: only one global identity per install.
- Clear when: Per-repository identity is supported, or standard git config per repository is honored.
- Evidence: Feature pages [[Multi-Account]] and [[Git Config Respect]].
- Personas: P7

### G15
**No native build for the persona's operating system**

- Test: The client does not run on the persona's OS. P8 requires Linux; P10 requires macOS or Windows.
- Triggered when: Platform list excludes the required OS.
- Clear when: Platform list includes it.
- Evidence: Client frontmatter `platforms` and the vendor download page (V, L).
- Personas: P8, P10

### G16
**Not usable from a terminal or remote session**

- Test: The client cannot be launched from a shell or used over SSH or a remote session.
- Triggered when: The client is GUI-only with no terminal or remote mode.
- Clear when: A TUI exists, or the client has a CLI launcher and remote support.
- Evidence: Feature pages [[CLI Companion]], [[Shell Integration]], [[Built-in Terminal]].
- Personas: P8

### G17
**Unusable on large repositories**

- Test: The client hangs, crashes, or becomes unresponsive on a large repository. Provisional thresholds: first usable screen over 10 s, peak memory over 2 GB, or a hang on the git/git test clone.
- Triggered when: A test (T) or credible report shows the threshold is crossed.
- Clear when: A test or credible report shows it is not crossed. GitUI is the only client tested so far ([[Benchmarks]]).
- Evidence: [[Benchmarks]] (T), feature page [[Large Repo Performance]].
- Personas: P9

### G18
**Ignores sparse checkout or partial clone**

- Test: The client breaks or expands a sparse or partial clone.
- Triggered when: Stated or tested: it does not respect sparse or partial clone settings.
- Clear when: It respects them.
- Evidence: [[Git Config Respect]], [[Large Repo Performance]]. Mostly unknown.
- Personas: P9

### G19
**Cannot handle binary files**

- Test: No LFS support and no preview or diff for common binary types.
- Triggered when: Stated: neither LFS nor binary preview.
- Clear when: LFS is supported, or binary preview exists.
- Evidence: Feature pages [[Git LFS]], [[Image Diff]], [[Rich File Preview]].
- Personas: P10

### G20
**No useful diff for notebooks or large files**

- Test: Notebooks and large data files appear as unreadable diffs or are refused.
- Triggered when: Stated or tested: no readable notebook or large-file diff.
- Clear when: A readable diff or preview exists.
- Evidence: [[Rich File Preview]], [[Diff Viewer]]. Mostly unknown.
- Personas: P11

### G21
**Needs the command line for ordinary tasks**

- Test: Everyday tasks (commit, branch, push, undo) require the CLI.
- Triggered when: Ordinary tasks are not available in the GUI.
- Clear when: Ordinary tasks work in the GUI.
- Evidence: Client note and feature pages.
- Personas: P10

### G22
**Hides concepts with no way to see more**

- Test: Actions are hidden behind one-button operations with no way to see what happens or what the commands are.
- Triggered when: No history view, command view, or detail view exists.
- Clear when: History, a command log, or detail views are available.
- Evidence: [[Command Transparency]], [[Commit Graph]].
- Personas: P1

### G23
**No undo and no warning before destructive actions**

- Test: A learner can destroy work with no undo, no reflog access, and no confirmation.
- Triggered when: Stated or tested: no undo and no warning.
- Clear when: Undo, a reflog view, or confirmations exist.
- Evidence: [[Undo and Redo]], [[Reflog]].
- Personas: P1

### G24
**No safe read-only mode**

- Test: An observer risks accidental writes because the client has no read-only mode.
- Triggered when: Stated or tested: no read-only mode or protection.
- Clear when: A read-only mode exists, or the client cannot write.
- Evidence: Vendor docs; test (T).
- Personas: P12

### G25
**Needs developer concepts to get started**

- Test: First use requires understanding staging, branches, or remotes before the observer can see activity.
- Triggered when: First-run flow requires git concepts to view history.
- Clear when: Activity can be viewed without writing concepts.
- Evidence: First-run test (T) or vendor docs.
- Personas: P12

## Suggested additions (not applied)

These gates already exist but are not yet attached to a persona that probably cares. They need your approval before I attach them.

- G08 (ignores hooks, templates, config) for P5, P6, and P9: all three work in repositories with enforced conventions.
- G10 (data leaves the machine) for P6 and P11: P6 under corporate policy, P11 because API keys and datasets pass through notebooks.
- G15 (OS support) for P6: managed device fleets often include Windows and macOS only.
- G09 for P7: client hosts vary and may be self-hosted.
