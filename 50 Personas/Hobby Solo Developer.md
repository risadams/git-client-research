---
title: Solo developer (hobby)
persona_id: P2
status: requested
payer: "Self; sensitive to subscriptions"
chooser: "Self"
total_weight: 28
tags: [persona, personas]
---

# P2: Solo developer (hobby)

Status: **requested** (requested by you)

A person with personal projects, a few private repositories, and no collaborators.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Self; sensitive to subscriptions
- Chooser: Self

## Context

- Wants something quick and pleasant, not a process.
- Private repositories are common; free tiers that exclude them fail.
- One machine or two, often mixed OS.
- Rarely needs team features.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 28. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC02\|UC02]] | Daily commit loop | Must | 3 | Fast commit loop. |
| [[Use Case Catalog#UC05\|UC05]] | Recover from mistakes | Must | 3 | Safety net for experiments. |
| [[Use Case Catalog#UC03\|UC03]] | Understand history visually | Must | 3 | Quick view of what changed. |
| [[Use Case Catalog#UC30\|UC30]] | Cost fits the persona | Must | 3 | Free or one-time price; subscription is a hard sell. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Must | 3 | Works on the user's OS. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Should | 2 | Occasional branches and merges. |
| [[Use Case Catalog#UC01\|UC01]] | First-run setup without the CLI | Should | 2 | Painless. |
| [[Use Case Catalog#UC08\|UC08]] | Pull requests from the client | Should | 2 | If the project is on GitHub. |
| [[Use Case Catalog#UC23\|UC23]] | Keyboard-driven speed and editor fit | Should | 2 | Comfort and speed. |
| [[Use Case Catalog#UC21\|UC21]] | AI assistance | Should | 2 | Convenience for commit messages. |
| [[Use Case Catalog#UC07\|UC07]] | Clean history before sharing | Nice | 1 | Occasional. |
| [[Use Case Catalog#UC15\|UC15]] | Large and binary files | Nice | 1 | Assets for games or media. |
| [[Use Case Catalog#UC27\|UC27]] | Privacy, telemetry, and offline use | Nice | 1 | Preference, not requirement. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G02\|G02]] | Free tier excludes private repositories | Free tier excludes private repositories |
| [[Dealbreaker Gates#G03\|G03]] | Subscription-only licensing | Recurring subscription as the only option |
| [[Dealbreaker Gates#G04\|G04]] | Mandatory account for local use | Heavy account or sign-up requirements |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
