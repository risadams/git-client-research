---
title: Home
description: Top-level overview and navigation for the git client market research vault.
tags: [moc, home]
created: 2026-11-09
---
# Git Client Research: Home

Market research on Git GUI clients: who makes them, what they cost, how popular they are, which features they have, and which fit which kind of user. Everything is dated 2026-11-09 unless a page says otherwise. Ratings are judgments from documented features, not hands-on tests, except where a page is graded **T** ([[Benchmarks]]).

## Start here, by question

| I want to... | Go to |
|---|---|
| See every client with platform, cost, license, and ease of use | [[01 Comparison Table]] |
| Browse the full catalog by type (desktop, TUI, IDE, mobile) | [[00 Index]] |
| Find the right client for a kind of person | [[Persona Results]] (pilot), [[Persona Index]] |
| See how scoring works | [[Scoring Rubric]], [[Scoring Criteria]], [[Dealbreaker Gates]] |
| Filter and sort clients by team fit, learning fit, or tier | [[Dashboard]] |
| Choose by situation: solo or team, learning, simple or pro | [[Audience Guide]] |
| Understand who owns and funds each product | [[Vendors and Companies]] |
| Compare prices | [[Pricing Landscape]] |
| See popularity and trends | [[Popularity Metrics]], [[Trends]] |
| Check what vendors claim against the evidence | [[Vendor Claims vs Evidence]] |
| Buy for a company | [[Enterprise Buying Checklist]] |
| Compare by capability | [[Features Index]] |
| Know how far to trust a number | [[Confidence Levels]], [[Data Reliability]] |
| See what is still unknown and what to do next | [[Methodology and Gaps]], [[Open Questions]] |

The whole market-research section is indexed at [[Market Research Hub]].

## What is in the vault

| Folder | Contents | Count |
|---|---|---|
| `00 Start` | Catalog index, confidence definitions, methodology and gaps | 3 pages |
| `10 Clients` | One note per client, with frontmatter used by the Dashboard | 66 |
| `20 Features` | One page per feature, with the clients that have it | 51 |
| `30 Compare` | Comparison table, features index with matrix, audience guide, dashboard | 4 pages |
| `40 Market Research` | Vendors, popularity, pricing, segments, trends, claims, benchmarks | 16 pages |
| `50 Personas` | 12 personas, a shared catalog of 33 use cases, rubric, criteria, and gates | 17 pages |
| `60 Scores` | Pilot scores for 27 clients and results by persona | 2 pages |

## Headline findings

Each line links to the page that holds the evidence and its grade.

- **Outside capital is behind two prominent tools.** GitKraken has been private-equity owned since 2020 (Resurgens), and GitButler raised a $17M Series A in April 2026. One aggregator lists $22M, and the company blog says $17M. See [[Vendors and Companies]].
- **LazyGit, a terminal UI, has by far the most GitHub stars** among the clients with recorded counts (81.6k), ahead of GitUI (22.6k), GitHub Desktop (21.9k), and GitButler (21.8k). Star counts measure interest among developers, not market share, and no public market share data for Git clients was found. See [[Popularity Metrics]].
- **Pricing models differ.** Free (GitHub Desktop, Sourcetree), one-time (Fork, $59.99), and per-user subscriptions (Tower, from $69/yr). See [[Pricing Landscape]].
- **GitUI is fast on a large repository.** On a test clone of git/git (82,725 commits), it drew its first screen in about 30 ms and loaded the full history in about 1.4 to 1.5 s. One client, one machine. See [[Benchmarks]].
- **Many enterprise answers are missing.** The vendor matrix is mostly "not retrieved" except for GitKraken. See [[Enterprise Buying Checklist]].

## How much to trust it

- Confidence by client: 14 verified on an official page (V), 39 from the git-scm.com listing only (L), 8 from background knowledge (B), 5 from secondary sources (S). See [[Confidence Levels]].
- Only 27 of 66 clients have audience ratings, because the rest have thin notes.
- Feature tags under-report. A missing tag means no evidence found, not "unsupported".

Next step: hands-on tests to replace documented-feature scores, and scoring the 39 clients with thin notes. Pilot results are in [[Persona Results]]; read them with the ceiling and unknown columns.
