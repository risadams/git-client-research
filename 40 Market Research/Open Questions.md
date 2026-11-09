---
title: Open Questions
description: Market data still missing and how to get it.
retrieved: 2026-11-09
tags: [market-research, gaps]
---

# Open Questions

| # | Missing data | Why it matters | Route |
|---|---|---|---|
| 1 | Install counts per client | Best proxy for share | Homebrew analytics, winget, Chocolatey, Flathub, Mac App Store, VS Code Marketplace; blocked from the shell this session |
| 2 | Release dates and cadence | Maintenance health | GitHub API (token invalid in this session) or release pages |
| 3 | Paid tier prices for GitKraken | Needed for a complete cost table | GitKraken pricing page |
| 4 | Sublime Merge store price | Conflicting evidence | sublimehq.com/store |
| 5 | G2, Capterra, Gartner Peer Insights scores | Independent review scale | Review sites, with sample sizes |
| 6 | Survey data on Git GUI usage | None known | Run a poll, or search JetBrains Developer Ecosystem data for "Git GUI" |
| 7 | Revenue estimates for paid vendors | Market size | Private companies; only rough estimates possible |
| 8 | Customer logos and case studies | Enterprise segment evidence | Vendor sites |
| 9 | Churn and switching behavior | Competitive dynamics | Interviews or Reddit and Hacker News mining |
| 10 | Remaining vendors: SourceGit maintainers, Gitember, Desktop Plus, Anchorpoint | Completeness | Per-project pages |

Next batch I can do without new access: vendor pages for the 14 verified clients, the GitKraken pricing page, Hacker News and Reddit sentiment, and JetBrains survey data.


## Resolved in batch 2

| # | Item | Result |
|---|---|---|
| 3 | GitKraken paid prices | Partly: Pro about $4 to $5 per user per month; on-premise $24. Cloud tiers above Pro still missing |
| New | Adjacent tools | [[Adjacent Tools]] |
| New | Creative segment | [[Creative and Non-Developer Segment]] |
| New | Claims vs evidence | [[Vendor Claims vs Evidence]] |
| New | Enterprise checklist | [[Enterprise Buying Checklist]]; only GitKraken answered most rows |
| New | Traceability | [[Issue Tracker Traceability]] |
| New | Switching stories | [[Switching Stories]] |
| New | Dashboard | [[Dashboard]] |
| New | Benchmarks | [[Benchmarks]]; terminal clients only |

## Still open from batch 2

- Enterprise checklist cells marked "not retrieved" for Tower, SmartGit, Sourcetree, Sublime Merge, GitHub Desktop and GitButler.
- Whether any commercial GUI vendor supports Jujutsu.
- File locking support per Git GUI.
- Anchorpoint and Diversion pricing.
- Lazygit could not be installed in the sandbox (Go module proxy not reachable), so it has no benchmark.
- Sourcetree sentiment after 2020 is thin.

Back to [[Market Research Hub]] | [[00 Index]] | [[Confidence Levels]]
