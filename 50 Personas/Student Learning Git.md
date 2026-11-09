---
title: Student learning git
persona_id: P1
status: requested
payer: "Usually the student; often free or discounted"
chooser: "The student, or an instructor or course"
total_weight: 30
tags: [persona, personas]
---

# P1: Student learning git

Status: **requested** (requested by you)

Someone in their first year of git, in a course or self-taught. Priority is understanding, safety, and zero cost.

> [!warning] Constructed persona
> This persona is a modeling assumption built from the vault's market research, not from a user survey. Priorities and weights are my judgment (grade B) and are meant to be edited.

## Who pays and who chooses

- Payer: Usually the student; often free or discounted
- Chooser: The student, or an instructor or course

## Context

- Low budget. Education discounts or free tiers matter more than features.
- Low tolerance for jargon. Needs to see what a button does.
- May use a school machine with a fixed OS.
- Moves to the CLI later; a client that teaches transfers well.

## Use cases

Weights: Must = 3, Should = 2, Nice = 1. Total weight: 30. Definitions are in [[Use Case Catalog]].

| ID | Use case | Priority | Weight | What good looks like for this persona |
|---|---|---|---|---|
| [[Use Case Catalog#UC01\|UC01]] | First-run setup without the CLI | Must | 3 | Can finish setup and first clone alone. |
| [[Use Case Catalog#UC02\|UC02]] | Daily commit loop | Must | 3 | Commit, push, pull without a mistake. |
| [[Use Case Catalog#UC03\|UC03]] | Understand history visually | Must | 3 | Seeing branches helps the mental model. |
| [[Use Case Catalog#UC04\|UC04]] | See the commands being run | Must | 3 | Seeing the equivalent command is the main learning aid. |
| [[Use Case Catalog#UC05\|UC05]] | Recover from mistakes | Must | 3 | Mistakes are guaranteed; undo must be easy. |
| [[Use Case Catalog#UC30\|UC30]] | Cost fits the persona | Must | 3 | Free, or an education path. |
| [[Use Case Catalog#UC31\|UC31]] | Runs on the persona's operating system | Must | 3 | Works on the student's OS. |
| [[Use Case Catalog#UC06\|UC06]] | Branch, merge, and resolve conflicts | Should | 2 | First merge conflict is a rite of passage; guidance helps. |
| [[Use Case Catalog#UC08\|UC08]] | Pull requests from the client | Should | 2 | Course work often goes through GitHub. |
| [[Use Case Catalog#UC11\|UC11]] | Multiple identities and accounts | Should | 2 | School and personal accounts. |
| [[Use Case Catalog#UC07\|UC07]] | Clean history before sharing | Nice | 1 | Later in the journey. |
| [[Use Case Catalog#UC23\|UC23]] | Keyboard-driven speed and editor fit | Nice | 1 | Not a priority. |
| [[Use Case Catalog#UC21\|UC21]] | AI assistance | Nice | 1 | Neutral; may reduce learning if it writes every message. |

## Dealbreaker gates (flag only)

A gate flags a client for this persona. It never removes the client from the ranking or changes its score. Definitions and evidence rules: [[Dealbreaker Gates]].

| Gate | Name | What it means for this persona |
|---|---|---|
| [[Dealbreaker Gates#G01\|G01]] | No free, education, or open-source path | No free or education path after a trial |
| [[Dealbreaker Gates#G22\|G22]] | Hides concepts with no way to see more | Hides all concepts behind one Sync button with no way to see more |
| [[Dealbreaker Gates#G23\|G23]] | No undo and no warning before destructive actions | No undo and no warning before destructive actions |

## Related

- [[Persona Index]]
- [[Audience Guide]]
- [[Market Segments]]
