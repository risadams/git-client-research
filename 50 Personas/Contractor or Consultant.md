---
title: Contractor or consultant
persona_id: P7
status: approved
payer: "Self; may be billable"
chooser: "Self, constrained by each client's rules"
total_weight: 32
tags: [persona, personas]
---

# P7: Contractor or consultant

Status: **approved** (suggested by Claude, approved by you 2026-11-09)

An independent developer working across several client codebases, each with its own host, rules, and credentials.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Self; may be billable
- Chooser: Self, constrained by each client's rules

## Context

- Many client accounts and identities on one machine.
- Client code must stay isolated; privacy matters.
- Pays personally; wants one tool that adapts to each client.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 32. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC11\|UC11]] | Multiple identities and accounts | Must | 3 | Per-client accounts, emails, and keys. |
| [[Use Case Catalog#UC10\|UC10]] | Manage many repositories | Must | 3 | Many repositories across clients. |
| [[Use Case Catalog#UC24\|UC24]] | Respect repository and corporate conventions | Must | 3 | Each client has its own hooks and policy. |
| [[Use Case Catalog#UC27\|UC27]] | Privacy, telemetry, and offline use | Must | 3 | Client code confidentiality. |
| [[Use Case Catalog#UC26\|UC26]] | Individual purchase logistics | Must | 3 | Multi-machine license, receipts. |
| [[Use Case Catalog#UC02\|UC02]] | Daily commit loop | Must | 3 | Core loop. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Must | 3 | Conflicts in unfamiliar code. |
| [[Use Case Catalog#UC12\|UC12]] | Signed commits and tags | Should | 2 | Some clients require it. |
| [[Use Case Catalog#UC08\|UC08]] | Pull requests from the client | Should | 2 | Several hosts. |
| [[Use Case Catalog#UC20\|UC20]] | Issue tracker linking | Should | 2 | Client trackers. |
| [[Use Case Catalog#UC13\|UC13]] | Avoid leaking secrets | Should | 2 | Liability. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Should | 2 | Own OS. |
| [[Use Case Catalog#UC21\|UC21]] | AI assistance | Nice | 1 | May be prohibited by client contracts. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G14\|G14]] | No per-repository identity separation | Cannot separate identities per repository |
| [[Dealbreaker Gates#G10\|G10]] | Data leaves the machine with no user control | Sends code to a third party with no way to turn it off |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
