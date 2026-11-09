---
title: Open source solo maintainer
persona_id: P3
status: requested
payer: "Self; open-source status may qualify for free licenses (verify per vendor)"
chooser: "Self"
total_weight: 37
tags: [persona, personas]
---

# P3: Open source solo maintainer

Status: **requested** (requested by you)

One person maintaining a public project with contributors who send pull requests.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Self; open-source status may qualify for free licenses (verify per vendor)
- Chooser: Self

## Context

- Work is mostly reviewing and integrating other people's changes.
- Releases and tags matter; the maintainer signs them.
- Time is the scarce resource, so triage speed counts.
- Often on Linux or macOS.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 37. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC09\|UC09]] | Triage outside contributions | Must | 3 | Check out contributor branches, apply patches, and merge with attribution. |
| [[Use Case Catalog#UC08\|UC08]] | Pull requests from the client | Must | 3 | Review and merge pull requests quickly. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Must | 3 | Resolve conflicts in contributed code. |
| [[Use Case Catalog#UC07\|UC07]] | Clean history before sharing | Must | 3 | Squash and reword before merging. |
| [[Use Case Catalog#UC19\|UC19]] | Releases, tags, and project stats | Must | 3 | Tag releases and view contributor stats. |
| [[Use Case Catalog#UC12\|UC12]] | Signed commits and tags | Must | 3 | Signed releases are common. |
| [[Use Case Catalog#UC18\|UC18]] | Investigate regressions | Must | 3 | Find which change broke a release. |
| [[Use Case Catalog#UC30\|UC30]] | Cost fits the persona | Must | 3 | Free or free for open source. |
| [[Use Case Catalog#UC20\|UC20]] | Issue tracker linking | Should | 2 | Link to GitHub Issues. |
| [[Use Case Catalog#UC11\|UC11]] | Multiple identities and accounts | Should | 2 | Personal and project identities. |
| [[Use Case Catalog#UC10\|UC10]] | Manage many repositories | Should | 2 | Several related repositories. |
| [[Use Case Catalog#UC13\|UC13]] | Avoid leaking secrets | Should | 2 | Public repository raises the stakes. |
| [[Use Case Catalog#UC21\|UC21]] | AI assistance | Should | 2 | Triage and summarization. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Should | 2 | Linux support is a frequent need. |
| [[Use Case Catalog#UC17\|UC17]] | Stacked branches | Nice | 1 | Large contributions broken into steps. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G06\|G06]] | No pull request checkout or patch apply | No way to check out a pull request or apply a patch |
| [[Dealbreaker Gates#G01\|G01]] | No free, education, or open-source path | Closed source tool required for public project work with no OSS license |
| [[Dealbreaker Gates#G07\|G07]] | Commit signing unsupported or bypassed | No signing support |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
