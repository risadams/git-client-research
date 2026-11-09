---
title: Scoring Rubric
description: "How clients are scored against personas: 0 to 3 scale, unknowns scored as 0 with a note, a score range, and gate flags."
tags: [personas, rubric]
---

# Scoring Rubric

Decided 2026-11-09. Personas are in [[Persona Index]], use cases in [[Use Case Catalog]], and gates in [[Dealbreaker Gates]].

## Decisions

| Question | Decision |
|---|---|
| Which personas | All 12 (P1 to P12) |
| Scale | 0 to 3 per use case |
| Unknown evidence | Scored 0, with a note that it is unknown |
| Excluded count | Every persona score reports how many use cases were unknown, and how much weight they carry |
| Dealbreakers | Flag only. A flag never excludes a client or changes its score |

## Scale per use case

| Score | Meaning |
|---|---|
| 0 | Not supported, or no evidence (see notation below) |
| 1 | Partial: present but limited or awkward |
| 2 | Good: works well for the use case |
| 3 | Excellent: among the strongest implementations in the vault |

**Notation.** Write `0` when there is evidence the client does not support the use case. Write `0u` when there is no evidence (unknown). Both count as 0 in the score. Every score carries an evidence grade (V, L, B, S, or T from [[Confidence Levels]]), and a `0u` carries the note "unknown".

## Persona score

Weights come from each persona page: Must = 3, Should = 2, Nice = 1.

- **Score** = sum(weight x score) / (3 x sum of all weights), as a percentage. Unknowns count as 0, so the score is a floor.
- **Ceiling** = the same formula with every unknown scored 3. It shows the most the client could reach if the missing evidence turned out well.
- **Unknown** = number of unknown use cases out of the persona's total, and the share of total weight they carry.
- **Known-only score** = the score computed on known use cases only. It is shown for comparison, because a large gap between it and the score means the result depends on missing evidence.
- **Low evidence label:** applied when unknown weight exceeds 40% of total weight. This threshold is provisional.

### Arithmetic example

Hypothetical numbers, not a real client: a persona with three use cases, weights 3, 2, 1, scored 3, `0u`, 2.

| Measure | Calculation | Result |
|---|---|---|
| Score | (3x3 + 2x0 + 1x2) / (3 x 6) | 61.1% |
| Ceiling | (3x3 + 2x3 + 1x2) / (3 x 6) | 94.4% |
| Unknown | 1 of 3 use cases; weight 2 of 6 | 33.3% of weight |
| Known-only score | (3x3 + 1x2) / (3 x 4) | 91.7% |

## Gate flags

Reported next to the score, per client and persona: the number of Triggered gates, the number of Unknown gates, and their IDs. A Triggered gate is shown even when the score is high. Definitions and the tri-state rules are in [[Dealbreaker Gates]].

## Reporting format

| Persona | Score | Ceiling | Unknown | Known-only | Gate flags |
|---|---|---|---|---|---|
| P2 | 61% | 94% | 1 of 3 (33% of weight) | 92% | 0 triggered, 2 unknown |

The row above reuses the hypothetical example and is illustrative only.

## Ambiguity to confirm

"Excluded count consideration" can be read two ways. I implemented it as reporting how many use cases were unknown (scored 0) and what the score would be with them excluded (known-only score) or fully favorable (ceiling). If you meant that some use cases should be excluded from the score entirely, tell me which.

## Criteria, storage, and pilot

- **Criteria:** what earns 0u, 1, 2, or 3 for each of the 33 use cases is in [[Scoring Criteria]].
- **Storage:** scores live in one table, [[Score Matrix]], with overrides listed beside it. I chose this over per-client frontmatter because Obsidian's Properties editor handles flat values best and one table is easy to review. Change it if you prefer frontmatter.
- **Pilot set:** the 27 clients with audience ratings, as I suggested. Results are in [[Persona Results]].
- **Still open:** hands-on tests (grade T) are the only way to earn a 3 on many use cases. Thin L-grade notes (39 clients) are not scored yet.
