---
title: Observer (Scrum Master, PM, reviewer)
persona_id: P12
status: approved
payer: "Rarely purchases"
chooser: "Self"
total_weight: 18
tags: [persona, personas]
---

# P12: Observer (Scrum Master, PM, reviewer)

Status: **approved** (suggested by Claude, approved by you 2026-11-09)

Someone who follows repository activity without writing code, for example a Scrum Master or project manager.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Rarely purchases
- Chooser: Self

## Context

- Needs status, not a full toolset.
- Wants a safe way to look without breaking things.
- The host website is often enough.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 18. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC32\|UC32]] | Read-only observation | Must | 3 | Read-only view of activity. |
| [[Use Case Catalog#UC03\|UC03]] | Understand history visually | Must | 3 | See what shipped. |
| [[Use Case Catalog#UC01\|UC01]] | First-run setup without the CLI | Must | 3 | Simple start. |
| [[Use Case Catalog#UC20\|UC20]] | Issue tracker linking | Should | 2 | Link work items to commits. |
| [[Use Case Catalog#UC19\|UC19]] | Releases, tags, and project stats | Should | 2 | Stats and releases. |
| [[Use Case Catalog#UC30\|UC30]] | Cost fits the persona | Should | 2 | Free. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Should | 2 | Managed laptop. |
| [[Use Case Catalog#UC18\|UC18]] | Investigate regressions | Nice | 1 | Occasional history search. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G24\|G24]] | No safe read-only mode | Risk of accidental writes with no read-only mode |
| [[Dealbreaker Gates#G25\|G25]] | Needs developer concepts to get started | Needs developer concepts to get started |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
