---
title: Switching Stories
description: Why users left Sourcetree, GitKraken and others, mined from public forums with sampling caveats.
retrieved: 2026-11-09
tags: [market-research, sentiment, churn]
---

# Switching Stories

> [!warning] Sampling
> About 25 public posts and review pages surfaced by web search, from 2026-11-09. Not random. Complaint threads over-represent unhappy users, and several are old. Counts below are of reasons seen in this sample, not of users.

## Reasons for leaving

| Leaving | Reason | Destination mentioned | Example evidence |
|---|---|---|---|
| [[Sourcetree\|Sourcetree]] | Slow, crashes, missed file changes | GitKraken, Fork, SmartGit, Sublime Merge, SourceGit, command line | Atlassian community threads 2013 to 2018 (Windows and Mac), a team that bought GitKraken licenses because Sourcetree became "unusable", and a DEV Community commenter reporting missed changes |
| [[GitKraken Desktop\|GitKraken Desktop]] | Paywall for private repos or non-GitHub remotes after a pricing change | Fork, built-in editor Git, free tools | DEV Community comments (2019 onward) |
| [[GitKraken Desktop\|GitKraken Desktop]] | Memory use and slowness (Electron) | Sublime Merge for conflicts, CLI | 2016 comments on Scott Hanselman's post, DEV Community, Capterra cons |
| Any GUI | Prefer editor-integrated Git | VS Code built-in | "I use the built-in git from VS Code now" |
| Any GUI | Keep CLI, use GUI for one task | Sublime Merge for conflicts, lazygit for diffs | DEV Community, Hacker News (a Jujutsu user keeps lazygit for diff viewing) |
| Windows | Moved to Linux | LazyGit, SourceGit | Lemmy post: SourceGit is similar to Sourcetree but faster and open source |

## Reasons for arriving

- To GitKraken from Sourcetree: conflict resolution, per a Lemmy commenter.
- To Fork: fastest and least buggy, per one unaffiliated 2019 review; the same thread says the one thing missed from GitKraken is the built-in conflict tool.
- To Sublime Merge: conflict resolution alongside the CLI.

## Observations

1. **Performance is the most common reason to leave a free client.** Sourcetree's reputation for slowness dates to 2013 and persists in comments despite fixes (embedded Git, libgit2). Recent evidence is thinner: a May 2026 thread reports a crash fixed in 4.2.17.
2. **Pricing gates cause churn at the free-to-paid boundary.** The GitKraken private-repo paywall appears repeatedly. The current free tier is limited to local and public remotes (see [[Pricing Landscape]]).
3. **Conflict resolution is a recurring deciding feature.** Users name it as the reason to adopt or to miss a client.
4. **Many users never leave the CLI.** The GitButler survey (self-selected waitlist, 1,200+ responses) found only 8% use a GUI exclusively. See [[Trends]].

## Excluded

One DEV Community article about leaving GitKraken for GitHub Desktop was excluded because it misdescribes GitHub Desktop's architecture. See [[Vendor Claims vs Evidence]].


Back to [[Market Research Hub]] | [[00 Index]] | [[Data Reliability]]
