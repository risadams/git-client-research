---
title: Enterprise Buying Checklist
description: Procurement and security criteria for Git clients, with what is known per vendor and the questions to send.
retrieved: 2026-11-09
tags: [market-research, enterprise, security]
---

# Enterprise Buying Checklist

Only GitKraken published enough to fill most rows. For every other vendor the cells say "not retrieved", which means I did not find it, not that it is absent. Retrieved 2026-11-09.

## Known answers

| Criterion | GitKraken | Tower | SmartGit | Sourcetree | GitHub Desktop | Sublime Merge | GitButler |
|---|---|---|---|---|---|---|---|
| SSO | Advanced, Business, Enterprise plans (SAML 2.0 stated) | Enterprise plan exists ($149 per user per year); SSO details not retrieved | not retrieved | Atlassian account required (Mac, per directory) | not retrieved | License key; no accounts mentioned | not retrieved |
| Security attestation | SOC 2 Type II; report for Business and Enterprise under NDA | not retrieved | not retrieved | Atlassian company programs (not client-specific) | Microsoft company programs (not client-specific) | not retrieved | not retrieved |
| Self-hosted or offline licensing | Self-Hosted Server ($24 per user per month, annual, minimum 10 users, LDAP, air-gapped) and Serverless with license keys | not retrieved | not retrieved | Free, no license server | Free | Key based (store issues license keys) | not retrieved |
| Self-hosted Git integrations | GitHub Enterprise Server, GitLab Self-Managed, Bitbucket Data Center, Azure DevOps Server | Azure DevOps Server, Perforce GitSwarm, custom servers (per Tower) | not retrieved | Bitbucket (Atlassian) | GitHub Enterprise | not retrieved | not retrieved |
| AI data controls | Org-wide API keys, custom endpoints (Azure OpenAI, Anthropic, Ollama), provider restrictions | not retrieved | not retrieved | no AI features found | not retrieved | no AI features found | AI features exist; data flow not retrieved |
| Central policy or admin | Settings on gitkraken.dev propagate to Desktop, GitLens, CLI | Enterprise plan | not retrieved | none found | none found | none found | not retrieved |
| Minimum seats | 10 for on-premise | not retrieved | not retrieved | none | none | none | not retrieved |
| Data storage location | AWS (S3, RDS, MongoDB Atlas); regions not retrieved | Local client | Local client | Local client | Local client | Local client | not retrieved |
| Support | Dedicated account rep on Enterprise | not retrieved | not retrieved | not retrieved | not retrieved | not retrieved | not retrieved |
| Free for education | not retrieved | Yes (students, teachers, non-profits) | Yes (academic, open source, charity) | Free | Free | not retrieved | free for individuals |

Cells that name a plan describe the vendor's published tiers. Cells marked "no AI features found" mean none turned up in my searches.

## Questions to send every vendor

1. Which SSO protocols are supported, and on which plan?
2. Do you hold SOC 2 Type II, ISO 27001, or equivalent? Can you share the report under NDA before purchase?
3. What does the client send over the network besides Git traffic (telemetry, crash reports, update checks)? Can this be disabled by policy?
4. Can the client run fully offline or air-gapped, and how are licenses validated?
5. What AI features exist, which model providers are used, and can we bring our own endpoint? Is customer code retained or used for training?
6. Are installers code-signed and notarized? Is there an SBOM?
7. Which credentials does the client store, and where (OS keychain or file)?
8. Support SLA, response times, and escalation path.
9. Pricing at 25, 100 and 500 seats, with volume tiers and renewal caps.
10. How do you handle end of life and data portability if the product is discontinued?

## Related

[[Pricing Landscape]], [[Vendors and Companies]], [[GitKraken Desktop|GitKraken Desktop]], [[Tower|Tower]].


Back to [[Market Research Hub]] | [[00 Index]] | [[Data Reliability]]
