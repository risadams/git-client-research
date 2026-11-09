---
title: Popularity Metrics
description: GitHub stars, forks, issues, review-site scores, and user-count claims for Git clients.
retrieved: 2026-11-09
tags: [market-research, popularity, metrics]
---

# Popularity Metrics

Snapshot 2026-11-09. Counts are abbreviated on GitHub pages (for example 81.6k), so they are accurate to about 100. The shell could not reach the GitHub API, so release dates, contributor counts, and commit cadence were not captured. See [[Open Questions]].

## GitHub open-source signals

| Project | Repo | Stars | Forks | Open issues | License | Type |
|---|---|---|---|---|---|---|
| [[LazyGit\|LazyGit]] | jesseduffield/lazygit | 81.6k | 3.0k | 857 | MIT | Terminal UI |
| [[GitUI\|GitUI]] | gitui-org/gitui | 22.6k | 796 | 249 | MIT | Terminal UI (Rust) |
| [[GitHub Desktop\|GitHub Desktop]] | desktop/desktop | 21.9k | 10.6k | about 1k | MIT | Desktop GUI |
| [[GitButler\|GitButler]] | gitbutlerapp/gitbutler | 21.8k | 1.0k | 319 | Fair-source (FSL), converts to MIT after 2 years | Desktop GUI + CLI |
| [[GitUp\|GitUp]] | git-up/GitUp | 12.1k | 1.5k | 356 | GPL-3.0 | Desktop GUI (macOS) |
| [[SourceGit\|SourceGit]] | sourcegit-scm/sourcegit | 5.9k | 494 | 147 | MIT | Desktop GUI (cross-platform) |

Reading the table:

- Stars measure interest and bookmarks, not active use or paying customers.
- Forks per star: GitHub Desktop 0.48, GitUp 0.12, LazyGit 0.04, GitUI 0.04, GitButler 0.05, SourceGit 0.08. A high ratio can reflect contributors (GitHub Desktop is often forked as a base for other clients, such as Desktop Plus) rather than users.
- Open issues relative to stars: LazyGit 857 (about 1.0%), GitHub Desktop about 1k (4.6%), GitUp 356 (2.9%), GitButler 319 (1.5%), GitUI 249 (1.1%), SourceGit 147 (2.5%). Open issues are a rough maintenance backlog signal.
- No stars exist for closed-source products (Tower, GitKraken, SmartGit, Sublime Merge, Fork, Sourcetree).

## Review-site and mindshare signals

| Product | Metric | Value | Source and caveat |
|---|---|---|---|
| [[Sourcetree\|Sourcetree]] | PeerSpot mindshare, Version Control category | 6.3% (Nov 2026), 6.9% a year earlier | Category includes hosting products such as Bitbucket (13.7%) |
| [[Sourcetree\|Sourcetree]] | PeerSpot rating | 3.7 / 5 | Small review count |
| [[Sourcetree\|Sourcetree]] | Toolradar rating | 4.4 / 5 from 397 reviews | Toolradar also says "0 verified reviews compared"; treat as aggregated |
| [[Sourcetree\|Sourcetree]] | TrustRadius likelihood to recommend | 8.6 / 10 from 8 ratings | Tiny sample |
| [[Sublime Merge\|Sublime Merge]] | SourceForge reviews | 5.0 / 5 on a handful of reviews | Tiny sample |
| [[Tower\|Tower]] | softwares.com data score | 3.8 | Directory score, not user reviews |
| [[GitKraken Desktop\|GitKraken Desktop]] | softwares.com score | 4.7 | Directory score |

## User-count claims (all vendor-sourced)

| Product | Claim | Date | Reliability |
|---|---|---|---|
| [[Tower\|Tower]] | 100,000+ developers and designers | current docs | Vendor; undefined "user" |
| [[Tower\|Tower]] | 50,000+ customers | 2015 press release | Vendor; implies growth of 2x in about 10 years |
| [[GitKraken Desktop\|GitKraken Desktop]] | 2M+ users acquired since 2016 | 2020 | Vendor quote via CB Insights; total downloads or sign-ups unclear |
| [[GitKraken Desktop\|GitKraken Desktop]] | 40M+ developers, 100K organizations | 2026 company profile | Marketing claim across the whole suite including GitLens; not comparable |
| [[GitHub Desktop\|GitHub Desktop]] | Millions of downloads; 500,000+ people active in the app each month | June 2019 (version 2.0 announcement) | Vendor; seven years old. The only monthly-active figure found for any client |
| Bitbucket (Sourcetree's platform) | 10M registered users (2019), 15M developers (2025) | secondary | Platform, not client |

## What would improve this page

Install counts: Homebrew analytics, winget, Flathub, Chocolatey, VS Code Marketplace installs (GitLens), Mac App Store ranks. All were out of reach this session. See [[Open Questions]].


Back to [[Market Research Hub]] | [[00 Index]] | [[Confidence Levels]]
