---
title: Persona Index
description: Personas for evaluating git clients, with defined use cases and a path to a scoring rubric.
tags: [personas, hub]
---

# Persona Index

Part of [[Market Research Hub]]. Each persona has a set of use cases from the [[Use Case Catalog]], with a priority (Must, Should, Nice) and a weight.

> [!note] How these relate to existing pages
> [[Audience Guide]] rates clients on solo versus team, learning, and simple versus pro. Personas replace those broad splits with specific situations and a shared list of use cases. [[Market Segments]] covers market size and segment shape; personas cover what each person needs.

## Personas

| ID | Persona | Status | Who pays | Who chooses | Use cases |
|---|---|---|---|---|---|
| P1 | [[Student Learning Git\|Student learning git]] | requested | Usually the student; often free or discounted | The student, or an instructor or course | 13 |
| P2 | [[Hobby Solo Developer\|Solo developer (hobby)]] | requested | Self; sensitive to subscriptions | Self | 13 |
| P3 | [[Open Source Solo Maintainer\|Open source solo maintainer]] | requested | Self; open-source status may qualify for free licenses (verify per vendor) | Self | 15 |
| P4 | [[Open Source Team\|Open source team]] | requested | Each member, or none (members use free tools) | Each member individually | 15 |
| P5 | [[Corporate User (Self-Purchased)\|Corporate user (self-purchased)]] | requested | The individual, sometimes reimbursed | The individual; each teammate may choose differently | 16 |
| P6 | [[Corporate User (Mandated and Funded)\|Corporate user (mandated and funded)]] | requested | The company | The company (procurement, IT, security) | 17 |
| P7 | [[Contractor or Consultant\|Contractor or consultant]] | approved | Self; may be billable | Self, constrained by each client's rules | 13 |
| P8 | [[DevOps or SRE\|DevOps or SRE engineer]] | approved | Self or company | Self | 13 |
| P9 | [[Monorepo Engineer\|Large repository engineer]] | approved | Company | Company or team | 12 |
| P10 | [[Creative or Non-Developer\|Creative or non-developer]] | approved | Self or employer | Self | 9 |
| P11 | [[Data or ML Practitioner\|Data or ML practitioner]] | approved | Self or company | Self | 10 |
| P12 | [[Non-Coding Observer\|Observer (Scrum Master, PM, reviewer)]] | approved | Rarely purchases | Self | 8 |

Status "requested" means you asked for it. "Approved" means I suggested it and you approved it on 2026-11-09. All 12 personas are in scope.

## Answer to "anything else?"

Six personas were proposed and are now approved. Each differs from the six you listed on at least one dimension that changes the scoring:

- **P7 Contractor or consultant:** many identities and client rules on one machine. Differs from P5 because identity separation and privacy become Must.
- **P8 DevOps or SRE:** terminal-first, Linux, many small repositories. Differs because the GUI must complement the CLI.
- **P9 Large repository engineer:** performance at scale decides everything. See [[Benchmarks]] for the only measured data so far.
- **P10 Creative or non-developer:** binary files and previews. See [[Creative and Non-Developer Segment]].
- **P11 Data or ML practitioner:** notebooks, large files, keys in notebooks.
- **P12 Observer:** Scrum Master, PM, or reviewer who reads and does not write. Often better served by the host website, which is itself a finding.

Considered and not added:

- Educator choosing a client for a class (covered by P1 plus a procurement angle).
- AI-agent-heavy developer (a use case, UC22, rather than a distinct persona for now).
- Air-gapped or regulated environments (a variant of P6 where privacy is a gate).

## Ambiguities to settle

- **P5 versus P6:** a P5 user whose employer later mandates a tool becomes P6. The same person can move between these, so scores should be read per situation, not per person.
- **P3 versus P4:** the client choice is individual in both. The difference is who handles releases and signing.
- **"Corporate funded" versus "mandated":** these are separate. A company can fund a choice without mandating one. P6 assumes both. A funded but unmandated case sits between P5 and P6; tell me if it needs its own persona.
- **Open source licensing:** some vendors offer free licenses for open-source work. I have not verified this per vendor, so P3 and P4 treat cost as a Must but not a gate.

## Rubric

Decided 2026-11-09. Scale, unknown handling, and reporting are in [[Scoring Rubric]]. Gate definitions are in [[Dealbreaker Gates]]. Criteria for each use case are in [[Scoring Criteria]]. Pilot results for 27 clients are in [[Persona Results]].
