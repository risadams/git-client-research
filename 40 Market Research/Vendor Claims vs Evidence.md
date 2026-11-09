---
title: Vendor Claims vs Evidence
description: Headline vendor claims checked against independent sources, with status per claim.
retrieved: 2026-11-09
tags: [market-research, claims, evidence]
---

# Vendor Claims vs Evidence

Method: take each vendor's most visible claim, then look for independent support. Statuses: Supported, Partly supported, Unverified, Contradicted in part, Cannot verify. "Unverified" means I found no independent evidence either way, not that the claim is false. Nothing was tested hands-on except in [[Benchmarks]].

| Vendor | Claim | Status | Evidence |
|---|---|---|---|
| Tower | Native apps avoid 'Electron's performance issues' | Unverified | Tower's own comparison page offers no benchmarks. GitKraken reviews on Capterra mention high memory use and slowdowns on very large repos, which is consistent but anecdotal. No head-to-head test found. |
| Tower | Team plan is 36% cheaper than GitKraken above 10 users | Unverified | Needs GitKraken per-seat prices for the same tier. Found: Pro about $4 to $5 per user per month on third-party pages (unit and billing term vary), and on-premise at $24 per user per month. Tower's 36% figure cannot be reproduced from these. |
| Tower | GitKraken and other Git GUIs lack drag-and-drop interactive rebase | Contradicted in part | GitKraken's help center (updated 2026-02) describes starting an interactive rebase by dragging a branch onto another, with pick, reword, squash and drop. Tower's table also marks both tools as having undo. |
| Tower | Only Tower offers force push with lease and date or filename history search | Unverified | Not checked against other clients. |
| Tower | 'Undo Anything' reverses virtually any Git operation | Partly supported | Tower docs state it. A reviewer on DEV Community says other clients undo only some actions. Vault shows only 5 clients mention undo, so rarity is real, but breadth of Tower's coverage was not tested. |
| Tower | 100,000+ developers and designers | Unverified | Same figure repeated across directories. A 2015 press release said 50,000+. No independent count. |
| GitKraken | Easiest Git client for beginners ('Git simplified') | Partly supported | Capterra reviews praise ease. Commenters on DEV Community left after a pricing change that charged for private repos. No controlled comparison. |
| GitKraken | SOC 2 Type II compliant | Cannot verify | Stated consistently on several vendor pages. The report is available only to Business and Enterprise customers under an NDA, so it cannot be checked from outside. |
| GitKraken | 2M+ users since 2016; 40M+ developers across the suite | Unverified | Vendor figures with different scopes and years. See [[Popularity Metrics]]. |
| SmartGit | Rock-solid; trusted for more than a decade | Unverified | Vendor interview. No independent source retrieved. |
| SmartGit | Syntevo is owned by European individuals | Vendor statement | Appears on smartgit.dev's vendor comparison page, which is authored by a competitor of the listed vendors. |
| GitButler | Builds what comes after Git | Opinion | Series A of $17M shows investor belief, not user benefit. Survey cited in the vendor's blog is self-selected from its own waitlist. |
| GitHub Desktop | Millions of downloads, 500,000+ monthly active users | Stale vendor claim | From GitHub's June 2019 announcement of version 2.0. Seven years old. |
| Sourcetree | Free and fully featured | Supported for price | Free, but long-running performance complaints appear in Atlassian community threads from 2013 to 2018, and a 2026 thread shows a crash fixed in 4.2.17. |
| Fork | Fast and least buggy | Weak support | One unaffiliated DEV Community review from 2019. |
| Sublime Merge | Fast | Weak support | A few five-star SourceForge reviews say 'Fast'. No measurement. |

## Patterns

- **Comparison pages are marketing.** Tower's page against GitKraken, GitKraken's page against Tower, and smartgit.dev's vendor-landscape page each present a table where the author's product looks best.
- **Performance claims are the least supported.** No vendor publishes reproducible benchmarks. See [[Benchmarks]] for a first small test of two terminal clients.
- **User counts have no shared definition.** Downloads, sign-ups, installs, and monthly active users appear interchangeably.
- **One claim was contradicted by the vendor's rival's own docs.** Check feature-absence claims first; they are the cheapest to disprove.

## Excluded source

A DEV Community article claimed a team moved from GitKraken to GitHub Desktop with measured gains and described GitHub Desktop as using native Rust bindings. GitHub Desktop's own project description says it is built with Electron, TypeScript and React, so the article's central comparison is wrong. I excluded it from this vault.


Back to [[Market Research Hub]] | [[00 Index]] | [[Data Reliability]]
