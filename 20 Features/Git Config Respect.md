---
title: Respects Existing Git Config, Hooks, and Credentials
group: Privacy, security and enterprise
client_count: 3
tags: [feature, feature-group/privacy-security-and-enterprise, feature/git-config-respect]
---
# Respects Existing Git Config, Hooks, and Credentials

**Group:** Privacy, security and enterprise  
**Clients with this feature in my notes:** 3 of 66

## What it does
Uses your installed git and its configuration, hooks, credential helpers, and SSH agent instead of reimplementing them.

## Why it matters
Avoids surprises with company hooks and signing setups.

## Git equivalent
n/a

## What to check when evaluating
Does it bundle its own git or use the system one? Are hooks run for all operations?

## Clients listing this feature
> [!warning] Reading this list
> A client missing here may still support it. This list only includes clients whose notes mention the feature. Confidence codes: V verified on official page, L git-scm.com listing, B background, S secondary sources. See [[Methodology and Gaps]].

- [[BeeBranch|BeeBranch]] (V): Token stored in OS keychain or reuse existing Git credentials
- [[Git Revenge|Git Revenge]] (V): Uses your existing git install, config, hooks, credential helpers, and SSH agent
- [[SmartGit|SmartGit]] (V): Built-in file compare, bundles, hooks

Back to [[Features Index]] | [[00 Index]]
