---
title: Creative or non-developer
persona_id: P10
status: approved
payer: "Self or employer"
chooser: "Self"
total_weight: 22
tags: [persona, personas]
---

# P10: Creative or non-developer

Status: **approved** (suggested by Claude, approved by you 2026-11-09)

Designers, writers, and others who version documents or assets with git.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Self or employer
- Chooser: Self

## Context

- Binary files dominate: images, design files, documents.
- Little interest in git concepts; wants save and share.
- Mostly macOS or Windows.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 22. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC33\|UC33]] | Preview non-code files | Must | 3 | See what changed in a design or document. |
| [[Use Case Catalog#UC15\|UC15]] | Large and binary files | Must | 3 | LFS and large file handling. |
| [[Use Case Catalog#UC01\|UC01]] | First-run setup without the CLI | Must | 3 | Install and first clone without terminal. |
| [[Use Case Catalog#UC02\|UC02]] | Daily commit loop | Must | 3 | Save and publish. |
| [[Use Case Catalog#UC05\|UC05]] | Recover from mistakes | Must | 3 | Undo is essential. |
| [[Use Case Catalog#UC03\|UC03]] | Understand history visually | Should | 2 | Simple history. |
| [[Use Case Catalog#UC30\|UC30]] | Cost fits the persona | Should | 2 | Affordable. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Should | 2 | macOS and Windows. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Nice | 1 | Binary conflicts rarely resolvable. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G19\|G19]] | Cannot handle binary files | Cannot handle binary files well |
| [[Dealbreaker Gates#G21\|G21]] | Needs the command line for ordinary tasks | Requires the CLI for ordinary tasks |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
