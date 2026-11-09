---
title: Open source team
persona_id: P4
status: requested
payer: "Each member, or none (members use free tools)"
chooser: "Each member individually"
total_weight: 35
tags: [persona, personas]
---

# P4: Open source team

Status: **requested** (requested by you)

Several maintainers sharing a public project, with conventions written down but no enforced client.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Each member, or none (members use free tools)
- Chooser: Each member individually

## Context

- No one can mandate a client. Tools are chosen by individuals.
- The project's conventions (commit format, hooks, signing) must work in any client.
- Contributors span all operating systems.
- Reviews happen mostly on the host website.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 35. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC24\|UC24]] | Respect repository and corporate conventions | Must | 3 | Hooks, templates, and signing must work in whatever client a member picks. |
| [[Use Case Catalog#UC08\|UC08]] | Pull requests from the client | Must | 3 | Review and merge on the host. |
| [[Use Case Catalog#UC09\|UC09]] | Triage outside contributions | Must | 3 | Handle contributions from many people. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Must | 3 | Conflicts across maintainers. |
| [[Use Case Catalog#UC12\|UC12]] | Signed commits and tags | Must | 3 | Release signing shared across maintainers. |
| [[Use Case Catalog#UC30\|UC30]] | Cost fits the persona | Must | 3 | Free, since no one will pay for a shared tool. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Must | 3 | Linux, macOS, and Windows among members. |
| [[Use Case Catalog#UC07\|UC07]] | Clean history before sharing | Should | 2 | Clean history policy. |
| [[Use Case Catalog#UC20\|UC20]] | Issue tracker linking | Should | 2 | Link to issues. |
| [[Use Case Catalog#UC18\|UC18]] | Investigate regressions | Should | 2 | Bisect and blame in a long-lived project. |
| [[Use Case Catalog#UC19\|UC19]] | Releases, tags, and project stats | Should | 2 | Tagging and stats. |
| [[Use Case Catalog#UC28\|UC28]] | Support, training, and onboarding | Should | 2 | Docs good enough to point newcomers to. |
| [[Use Case Catalog#UC13\|UC13]] | Avoid leaking secrets | Should | 2 | Shared risk. |
| [[Use Case Catalog#UC10\|UC10]] | Manage many repositories | Nice | 1 | Several repositories. |
| [[Use Case Catalog#UC16\|UC16]] | Worktrees and submodules | Nice | 1 | Backport branches. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G07\|G07]] | Commit signing unsupported or bypassed | Ignores hooks, templates, or signing configuration |
| [[Dealbreaker Gates#G08\|G08]] | Ignores repository hooks, templates, or git configuration | Ignores hooks, templates, or signing configuration |
| [[Dealbreaker Gates#G01\|G01]] | No free, education, or open-source path | Paid only, so the team cannot recommend it |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
