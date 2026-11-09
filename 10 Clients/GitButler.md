---
title: GitButler
category: Desktop GUI
platforms: "macOS (Apple Silicon), Linux (x86_64), Windows (x86_64)"
license: "FSL-1.1-MIT per git-scm.com (site says 'Free and Open Source'; FSL is source-available and converts to MIT after a delay)"
ease_of_use: 3
status: Active
confidence: V
features: [commit-amend, undo-and-redo, stacked-branches, parallel-branches, history-editing, cli-companion, ai-review-and-explain, agent-support]
audience_tier: Pro
learning_fit: 2
solo_fit: 4
team_fit: 3
website: https://gitbutler.com
tags: [git-client, desktop-gui, required, feature/commit-amend, feature/undo-and-redo, feature/stacked-branches, feature/parallel-branches, feature/history-editing, feature/cli-companion, feature/ai-review-and-explain, feature/agent-support]
---
# GitButler

> [!info] Data quality
> verified on official page, 2026-11-09. See [[Methodology and Gaps]].

| Field | Value |
|---|---|
| Category | Desktop GUI |
| Platforms | macOS (Apple Silicon), Linux (x86_64), Windows (x86_64) |
| Cost | Free (site gives no plan details; sign-in exists) |
| License | FSL-1.1-MIT per git-scm.com (site says 'Free and Open Source'; FSL is source-available and converts to MIT after a delay) |
| Ease of use (my estimate) | ★★★☆☆ (3/5) |
| Status | Active |
| Website | https://gitbutler.com |

## Installation
Desktop: installer from gitbutler.com (DMG, DEB/RPM, MSI). CLI: `curl -fsSL https://gitbutler.com/install.sh | sh` (CLI is called `but`).

## Features
- Parallel branches: work on several branches at once without switching
- Stacked branches with independent review and landing
- Unlimited undo and redo, including after commits
- History editing: move, absorb, reorder, amend changes between commits
- Smartlog summary of active branches
- Works on existing Git repos and remotes with no config
- CLI with JSON output and agent skills aimed at AI coding agents

## Feature tags
> [!warning] Not listed does not mean unsupported
> Tags come only from the feature text in this note. A missing tag means I have no evidence either way.

**Staging and commits:** [[Commit Amend|Commit Amend]]  
**Branching models and history rewriting:** [[Undo and Redo|Undo and Redo]], [[Stacked Branches|Stacked Branches]], [[Parallel Branches|Parallel Branches]], [[History Editing|History Editing]]  
**Interface and ergonomics:** [[CLI Companion|CLI Companion]]  
**AI assistance:** [[AI Review and Explain|AI Review and Explain]], [[Agent Support|Agent Support]]  

## Ease of use
Different mental model from classic Git. Easy once adopted, but unlearning branch-switching takes a few days.

## Audience fit
> [!info] My judgment, not user-tested. See [[Audience Guide]] for scales.

| Dimension | Rating |
|---|---|
| Tier | Pro |
| Good for learning Git | 2/5 |
| Solo developer fit | 4/5 |
| Team fit | 3/5 |

Parallel and stacked branches are a different mental model, so learn standard Git first. Free for solo use. Team value depends on whether the team uses stacked pull requests.

## Best for
People juggling several in-flight changes, stacked-PR workflows, AI-agent-assisted development.

## Caveats
Workflow is opinionated and diverges from standard branch checkout. Young product; features change quickly. Marketing speed claims (agents '60% faster') are vendor claims.

Back to [[00 Index]] | [[01 Comparison Table]]

## Market data

- Vendor: GitButler Inc.
- Ownership: VC-backed startup
- HQ: Berlin, DE (also US)
- Founded: 2023 (Scott Chacon CEO, Kiril Videlov CTO, Anne Leuschner)
- Team: 11 to 50 (ai-market-watch, secondary)
- Funding: Series A $17M, 2026-04-08, led by a16z (Peter Levine joins board), with Fly Ventures and A.Capital; seed about $3.7M in 2023 (secondary)
- Revenue model: Free for individuals today; fair-source license; paid team features implied by the funding story, not verified
- User claims: none stated
- Grade: V (see [[Data Reliability]])
- GitHub: gitbutlerapp/gitbutler, 21.8k stars, 1.0k forks, 319 open issues, license Fair-source (FSL), converts to MIT after 2 years (snapshot 2026-11-09)

More in [[Vendors and Companies]] and [[Popularity Metrics]].
