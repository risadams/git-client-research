---
title: Data or ML practitioner
persona_id: P11
status: approved
payer: "Self or company"
chooser: "Self"
total_weight: 24
tags: [persona, personas]
---

# P11: Data or ML practitioner

Status: **approved** (suggested by Claude, approved by you 2026-11-09)

Someone versioning notebooks, datasets, and models alongside code.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Self or company
- Chooser: Self

## Context

- Large files and notebook JSON diffs.
- API keys often end up in notebooks.
- Frequent experiments on branches.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 24. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC15\|UC15]] | Large and binary files | Must | 3 | Large files and LFS. |
| [[Use Case Catalog#UC33\|UC33]] | Preview non-code files | Must | 3 | Notebook and data diffs. |
| [[Use Case Catalog#UC02\|UC02]] | Daily commit loop | Must | 3 | Core loop. |
| [[Use Case Catalog#UC05\|UC05]] | Recover from mistakes | Must | 3 | Experiments go wrong. |
| [[Use Case Catalog#UC13\|UC13]] | Avoid leaking secrets | Must | 3 | Keys in notebooks. |
| [[Use Case Catalog#UC14\|UC14]] | Work in a large repository | Should | 2 | Big repositories. |
| [[Use Case Catalog#UC03\|UC03]] | Understand history visually | Should | 2 | Experiment branches. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Should | 2 | Notebook conflicts. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Should | 2 | Linux or macOS. |
| [[Use Case Catalog#UC21\|UC21]] | AI assistance | Nice | 1 | Convenience. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G20\|G20]] | No useful diff for notebooks or large files | Cannot show a useful diff of notebooks or large files |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
