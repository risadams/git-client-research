---
title: DevOps or SRE engineer
persona_id: P8
status: approved
payer: "Self or company"
chooser: "Self"
total_weight: 30
tags: [persona, personas]
---

# P8: DevOps or SRE engineer

Status: **approved** (suggested by Claude, approved by you 2026-11-09)

An engineer who manages infrastructure-as-code, config repositories, and scripts, often over SSH and in the terminal.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Self or company
- Chooser: Self

## Context

- Terminal-first; the GUI must complement, not replace, the CLI.
- Many small repositories and submodules.
- Often works on Linux and over remote shells.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 30. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC23\|UC23]] | Keyboard-driven speed and editor fit | Must | 3 | Keyboard-driven and shell-friendly. |
| [[Use Case Catalog#UC04\|UC04]] | See the commands being run | Must | 3 | Needs to trust that the tool does what the CLI would. |
| [[Use Case Catalog#UC24\|UC24]] | Respect repository and corporate conventions | Must | 3 | Hooks and config. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Must | 3 | Linux support. |
| [[Use Case Catalog#UC10\|UC10]] | Manage many repositories | Must | 3 | Many repositories. |
| [[Use Case Catalog#UC16\|UC16]] | Worktrees and submodules | Must | 3 | Submodules and worktrees. |
| [[Use Case Catalog#UC07\|UC07]] | Clean history before sharing | Should | 2 | Clean history. |
| [[Use Case Catalog#UC18\|UC18]] | Investigate regressions | Should | 2 | Who changed this config. |
| [[Use Case Catalog#UC12\|UC12]] | Signed commits and tags | Should | 2 | Common in infrastructure repositories. |
| [[Use Case Catalog#UC13\|UC13]] | Avoid leaking secrets | Should | 2 | Credentials in config files. |
| [[Use Case Catalog#UC22\|UC22]] | Working alongside AI coding agents | Should | 2 | Agent-driven changes. |
| [[Use Case Catalog#UC14\|UC14]] | Work in a large repository | Nice | 1 | Occasional. |
| [[Use Case Catalog#UC21\|UC21]] | AI assistance | Nice | 1 | Convenience. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G15\|G15]] | No native build for the persona's operating system | No Linux build |
| [[Dealbreaker Gates#G16\|G16]] | Not usable from a terminal or remote session | Cannot be driven from a terminal or remote session |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
