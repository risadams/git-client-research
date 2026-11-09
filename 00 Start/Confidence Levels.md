---
title: Confidence Levels
tags: [git-client, research-log]
---
# Confidence Levels

Every client note has a `confidence:` property and a callout at the top. This page explains what each code means, what it does not mean, and which notes carry it.

## Summary

| Code | Meaning | Clients |
|---|---|---|
| V | Verified on the official page | 14 |
| L | git-scm.com listing only | 39 |
| B | Background knowledge | 8 |
| S | Secondary sources only | 5 |
| T | Tested hands-on by Claude in a sandbox (terminal clients only; see [[Benchmarks]]) | 1 |

## Rules that apply at every level

- **Ease-of-use stars are always my estimate.** They are a 1 to 5 judgment, not a measurement, regardless of confidence. No client was tested hands-on.
- **'Verified' means checked against the vendor's own claims, not tested.** It is a statement about where the text came from.
- **Feature tags** (see [[Features Index]]) come only from each note's own feature text. Low-confidence notes have fewer features written down, so they get fewer tags. A missing tag is not evidence of absence.
- **Dates matter.** Pricing and versions were read on 2026-11-09 and can change at any time.

## V: Verified on the official page

**How it was obtained:** I fetched the vendor's or project's own page (site, pricing page, or GitHub README) on 2026-11-09 and the note's price, platforms, license, and feature list come from it.

**What it covers well:** Price, platforms, license, install method, and features as the vendor states them. Dated 2026-11-09.

**Limits:** Vendor claims are not independent proof. 'Fastest', 'handles 200k commits', or 'no telemetry' are self-reported. Pages can be incomplete (for example GitKraken's pricing page omitted dollar amounts), and pricing changes often.

**How to use it:** Reasonably safe for 'what does it cost and what does it claim'. Not safe for 'does it actually work well'.

**Clients (14):** [[BeeBranch|BeeBranch]], [[Fork|Fork]], [[ForkPlus|ForkPlus]], [[Git Revenge|Git Revenge]], [[GitButler|GitButler]], [[GitComet|GitComet]], [[Gitember|Gitember]], [[GitHub Desktop|GitHub Desktop]], [[GitKraken Desktop|GitKraken Desktop]], [[rgitui|rgitui]], [[SmartGit|SmartGit]], [[Sourcetree|Sourcetree]], [[TortoiseGit|TortoiseGit]], [[Tower|Tower]]

## L: git-scm.com listing only

**How it was obtained:** Price, platform, and license come from the curated list at git-scm.com/tools/guis. Everything else (features, install, caveats) is short, generic, or marked 'not verified'.

**What it covers well:** Platforms, price string, and license, as of the day I read the list.

**Limits:** Feature lists are thin or empty, so these clients under-report on every feature page. Install steps and ease-of-use notes are mostly placeholders. Some listed prices may be stale.

**How to use it:** Good for building a candidate list. Check the vendor site before relying on any detail.

**Clients (39):** [[Anchorpoint|Anchorpoint]], [[Aurees|Aurees]], [[Changes|Changes]], [[Fugitive|Fugitive]], [[Git Extensions|Git Extensions]], [[git-cola|git-cola]], [[GitAhead|GitAhead]], [[GitBreeze|GitBreeze]], [[GitFiend|GitFiend]], [[GitFinder|GitFinder]], [[Gitfox|Gitfox]], [[gitg|gitg]], [[GitKraken CLI|GitKraken CLI]], [[Gitnuro|Gitnuro]], [[Gitoryx|Gitoryx]], [[Gittyup|Gittyup]], [[GitUI|GitUI]], [[GitUp|GitUp]], [[GitVine|GitVine]], [[Glint|Glint]], [[Guitar|Guitar]], [[Kommit|Kommit]], [[LazyGit|LazyGit]], [[Magit|Magit]], [[MeGit (EGit-based)|MeGit (EGit-based)]], [[Meld|Meld]], [[NitroGit|NitroGit]], [[Pocket Git|Pocket Git]], [[PolyGit|PolyGit]], [[Puppy Git|Puppy Git]], [[RelaGit|RelaGit]], [[RepoZ|RepoZ]], [[Retcon|Retcon]], [[SnailGit|SnailGit]], [[SourceGit|SourceGit]], [[Sublime Merge|Sublime Merge]], [[tig|tig]], [[ungit|ungit]], [[Working Copy|Working Copy]]

## B: Background knowledge

**How it was obtained:** Written from my general knowledge of the tool and not re-checked against a source in this research. Mostly IDE-integrated and bundled tools (VS Code, Visual Studio, JetBrains, Xcode, EGit, git-gui, QGit, GitLens).

**What it covers well:** Broad capabilities that change slowly.

**Limits:** Version-specific details, prices (for example GitLens Pro), and recent feature changes may be wrong or outdated.

**How to use it:** Fine for orientation. Verify prices and versions before deciding.

**Clients (8):** [[Eclipse EGit|Eclipse EGit]], [[git-gui and gitk|git-gui and gitk]], [[GitLens (VS Code)|GitLens (VS Code)]], [[JetBrains IDE Git|JetBrains IDE Git]], [[QGit|QGit]], [[Visual Studio Git integration|Visual Studio Git integration]], [[VS Code built-in Git|VS Code built-in Git]], [[Xcode source control|Xcode source control]]

## S: Secondary sources only

**How it was obtained:** Built from third-party pages such as LinuxLinks, Flathub, AUR, package indexes, and search snippets. I did not open the project's own site.

**What it covers well:** Existence, platform, license, and install route as other sites describe them.

**Limits:** Secondary sites copy each other and go stale. Star counts and activity come from indexes that may lag. Feature claims are summaries by someone else.

**How to use it:** Treat as a lead. Open the project page before trusting it.

**Clients (5):** [[Desktop Plus|Desktop Plus]], [[GitFourchette|GitFourchette]], [[GitQlient|GitQlient]], [[Gitu|Gitu]], [[Stage|Stage]]

## Moving a note up a level

1. Open the vendor's pricing, download, and docs pages. Record price, platforms, license, and install method with the date.
2. Copy feature claims from the docs, not from marketing headlines.
3. Install it on a real repository and note what actually works. Then upgrade the ease-of-use stars from estimate to observation.
4. Change `confidence:` in the note's properties and update the callout line. A future level for hands-on tested clients (for example `T`) would sit above V.

## Finding notes by confidence in Obsidian

Search with the property filter, for example `[confidence:L]`. With the Dataview plugin installed, this lists every L-level note:

```dataview
TABLE platforms, license
FROM "10 Clients"
WHERE confidence = "L"
SORT file.name ASC
```

Back to [[00 Index]] | [[Methodology and Gaps]]
