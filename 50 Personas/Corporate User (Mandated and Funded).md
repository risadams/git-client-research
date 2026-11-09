---
title: Corporate user (mandated and funded)
persona_id: P6
status: requested
payer: "The company"
chooser: "The company (procurement, IT, security)"
total_weight: 43
tags: [persona, personas]
---

# P6: Corporate user (mandated and funded)

Status: **requested** (requested by you)

A team required to use one approved client, bought and administered centrally.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: The company
- Chooser: The company (procurement, IT, security)

## Context

- Security review, SSO, and audit matter before features.
- Procurement wants invoicing, seat management, and a vendor with support terms.
- Managed devices limit what can be installed.
- Onboarding many people at once makes support and docs important.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 43. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC25\|UC25]] | Central procurement and administration | Must | 3 | SSO, seat management, license server or admin console, invoicing, audit. |
| [[Use Case Catalog#UC24\|UC24]] | Respect repository and corporate conventions | Must | 3 | Must honor corporate git configuration. |
| [[Use Case Catalog#UC27\|UC27]] | Privacy, telemetry, and offline use | Must | 3 | Telemetry and AI data flows must be controllable. |
| [[Use Case Catalog#UC28\|UC28]] | Support, training, and onboarding | Must | 3 | Vendor support, SLAs, and training. |
| [[Use Case Catalog#UC29\|UC29]] | Vendor and project viability | Must | 3 | Vendor must be around for the contract term. |
| [[Use Case Catalog#UC12\|UC12]] | Signed commits and tags | Must | 3 | Policy compliance. |
| [[Use Case Catalog#UC13\|UC13]] | Avoid leaking secrets | Must | 3 | Policy compliance. |
| [[Use Case Catalog#UC08\|UC08]] | Pull requests from the client | Must | 3 | Corporate host integration. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Must | 3 | Supports the managed device fleet. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Should | 2 | Daily conflicts. |
| [[Use Case Catalog#UC20\|UC20]] | Issue tracker linking | Should | 2 | Traceability. |
| [[Use Case Catalog#UC11\|UC11]] | Multiple identities and accounts | Should | 2 | Identity mapping to corporate accounts. |
| [[Use Case Catalog#UC21\|UC21]] | AI assistance | Should | 2 | Policy-controlled AI. |
| [[Use Case Catalog#UC07\|UC07]] | Clean history before sharing | Should | 2 | Review hygiene. |
| [[Use Case Catalog#UC10\|UC10]] | Manage many repositories | Should | 2 | Many repositories. |
| [[Use Case Catalog#UC14\|UC14]] | Work in a large repository | Should | 2 | Depends on the codebase. |
| [[Use Case Catalog#UC30\|UC30]] | Cost fits the persona | Should | 2 | Budget approved, but per-seat cost is scrutinized. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G12\|G12]] | No single sign-on or central administration | No SSO or central administration |
| [[Dealbreaker Gates#G13\|G13]] | No vendor security documentation | No vendor security documentation (SOC 2 or equivalent) available |
| [[Dealbreaker Gates#G11\|G11]] | No central control of telemetry and AI | Telemetry or AI cannot be disabled centrally |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
