---
title: Corporate user (self-purchased)
persona_id: P5
status: requested
payer: "The individual, sometimes reimbursed"
chooser: "The individual; each teammate may choose differently"
total_weight: 40
tags: [persona, personas]
---

# P5: Corporate user (self-purchased)

Status: **requested** (requested by you)

An employee at a company with no mandated client. The company standardizes git and the host, not the GUI.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: The individual, sometimes reimbursed
- Chooser: The individual; each teammate may choose differently

## Context

- Employer repositories have hooks, SSO to the host, and sometimes a proxy.
- Personal budget or reimbursement decides what is affordable.
- Uses a work account and often a personal account on the same machine.
- May be a long-term user who values depth.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 40. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC24\|UC24]] | Respect repository and corporate conventions | Must | 3 | Hooks, proxies, and credential helpers must work. |
| [[Use Case Catalog#UC02\|UC02]] | Daily commit loop | Must | 3 | Fast, reliable loop. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Must | 3 | Daily conflicts. |
| [[Use Case Catalog#UC07\|UC07]] | Clean history before sharing | Must | 3 | Clean up before review. |
| [[Use Case Catalog#UC08\|UC08]] | Pull requests from the client | Must | 3 | Work PRs on the corporate host. |
| [[Use Case Catalog#UC11\|UC11]] | Multiple identities and accounts | Must | 3 | Work and personal accounts. |
| [[Use Case Catalog#UC26\|UC26]] | Individual purchase logistics | Must | 3 | Receipts, multi-machine license, cancellation. |
| [[Use Case Catalog#UC30\|UC30]] | Cost fits the persona | Must | 3 | Within personal budget. |
| [[Use Case Catalog#UC20\|UC20]] | Issue tracker linking | Should | 2 | Jira or similar links. |
| [[Use Case Catalog#UC12\|UC12]] | Signed commits and tags | Should | 2 | Company signing policy may apply. |
| [[Use Case Catalog#UC18\|UC18]] | Investigate regressions | Should | 2 | Blame and history. |
| [[Use Case Catalog#UC10\|UC10]] | Manage many repositories | Should | 2 | Several repositories. |
| [[Use Case Catalog#UC23\|UC23]] | Keyboard-driven speed and editor fit | Should | 2 | Productivity. |
| [[Use Case Catalog#UC21\|UC21]] | AI assistance | Should | 2 | Productivity, within company policy. |
| [[Use Case Catalog#UC27\|UC27]] | Privacy, telemetry, and offline use | Should | 2 | Code leaving the machine may breach policy. |
| [[Use Case Catalog#UC14\|UC14]] | Work in a large repository | Should | 2 | Depends on the employer. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G09\|G09]] | Cannot authenticate to enterprise or self-hosted hosts | Cannot authenticate to the corporate host (SSO, enterprise Git hosting) |
| [[Dealbreaker Gates#G10\|G10]] | Data leaves the machine with no user control | AI features send code to a third party with no way to disable them |
| [[Dealbreaker Gates#G05\|G05]] | License tied to one machine | License tied to one machine |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
