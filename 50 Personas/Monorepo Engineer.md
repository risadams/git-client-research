---
title: Large repository engineer
persona_id: P9
status: approved
payer: "Company"
chooser: "Company or team"
total_weight: 30
tags: [persona, personas]
---

# P9: Large repository engineer

Status: **approved** (suggested by Claude, approved by you 2026-11-09)

A developer in a very large repository where speed is the main differentiator.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Company
- Chooser: Company or team

## Context

- Tens of thousands of files and long histories.
- Partial clone, sparse checkout, and fsmonitor may be involved.
- Sluggish tools get abandoned for the CLI.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 30. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC14\|UC14]] | Work in a large repository | Must | 3 | Responsiveness at scale. |
| [[Use Case Catalog#UC24\|UC24]] | Respect repository and corporate conventions | Must | 3 | Hooks and sparse or partial clone config. |
| [[Use Case Catalog#UC18\|UC18]] | Investigate regressions | Must | 3 | Blame and search at scale. |
| [[Use Case Catalog#UC02\|UC02]] | Daily commit loop | Must | 3 | Core loop. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Must | 3 | Conflicts. |
| [[Use Case Catalog#UC07\|UC07]] | Clean history before sharing | Must | 3 | Review hygiene. |
| [[Use Case Catalog#UC16\|UC16]] | Worktrees and submodules | Must | 3 | Parallel branches. |
| [[Use Case Catalog#UC17\|UC17]] | Stacked branches | Should | 2 | Stacked changes are common here. |
| [[Use Case Catalog#UC23\|UC23]] | Keyboard-driven speed and editor fit | Should | 2 | Speed. |
| [[Use Case Catalog#UC25\|UC25]] | Central procurement and administration | Should | 2 | If corporate. |
| [[Use Case Catalog#UC15\|UC15]] | Large and binary files | Should | 2 | LFS. |
| [[Use Case Catalog#UC10\|UC10]] | Manage many repositories | Nice | 1 | Few repositories. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G17\|G17]] | Unusable on large repositories | Hangs or high memory use on large repositories |
| [[Dealbreaker Gates#G18\|G18]] | Ignores sparse checkout or partial clone | Ignores sparse or partial clone |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
