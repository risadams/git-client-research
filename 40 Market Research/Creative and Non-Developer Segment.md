---
title: Creative and Non-Developer Segment
description: "Game artists, designers and other non-engineers: large binaries, locking, previews. Anchorpoint, Unity Version Control, Perforce, and where Git GUIs fit."
retrieved: 2026-11-09
tags: [market-research, segments, creative, game-dev]
---

# Creative and Non-Developer Segment

Artists, designers, animators and technical writers use version control with different needs from engineers: large binary files, exclusive file locking, thumbnails, and an interface with few Git concepts. Retrieved 2026-11-09.

> [!warning] Source bias
> Most comparison material below comes from Anchorpoint (a vendor in this segment), Perforce (the incumbent), and Diversion (a vendor). Each says so or is obviously interested. Treat rankings as vendor opinion.

## Players

| Tool | Model | Pitch | Evidence quality |
|---|---|---|---|
| Perforce Helix Core and P4V | Centralized VCS | Industry standard for AAA game development (Perforce's and Anchorpoint's own descriptions) | Vendor claim |
| Unity Version Control (formerly Plastic SCM) | Centralized or distributed, from Codice, owned by Unity | Strong with large binaries; Gluon mode gives artists a simplified GUI | Vendor and Perforce pages; acquisition year conflicts (2020 on two pages, 2023 on one) |
| Anchorpoint | Git client plus asset manager | Git with file locking, LFS and thumbnails for Unreal and Unity artists | Vendor; its own blog says its locking is advisory only |
| Diversion | Cloud VCS | Large-asset source control and Perforce alternative | Vendor |
| Git plus LFS in a general client | Git | Free and flexible; needs LFS and a host that supports locking | Anchorpoint and Diversion describe it as a steeper curve for artists |

Older price points for Plastic SCM from TrustRadius (not current; one page says the product is no longer available for sale under that name): Cloud $6.95, Team $9.95, Enterprise $23.25 per user, Enterprise perpetual $595 per user.

## What artists need that most Git GUIs lack

| Need | Why | Coverage in my records |
|---|---|---|
| Exclusive file locking | Binary files cannot be merged | Not tracked as a feature in the vault. Git LFS locking depends on host and client support |
| Thumbnails and rich previews | Visual history | 2 clients mention rich file preview |
| Image and binary diff | Review art changes | 4 clients mention it |
| Git LFS | Store large files outside history | 9 clients mention it |
| Few Git concepts exposed | Non-engineers avoid branches and rebases | Unity's Gluon mode and Anchorpoint target this |
| Per-folder permissions | Control who edits what | Plastic is described as having more granular authorization than Git |
| Bundled storage | Binary repos are large | One comparison site says some vendors bundle storage and bandwidth |

## Implications

- The segment is served by specialist tools, not by the mainstream Git GUIs. Tower and Sourcetree are documented as supporting LFS, but nothing I retrieved shows a mainstream GUI with locking and previews aimed at artists.
- Git-based entrants (Anchorpoint) compete on staying compatible with any Git host, which reduces lock-in compared with Perforce and Unity.
- Engine ownership shapes the market: Unity owns Plastic; Perforce has a long Unreal footprint.

## Gaps

- Pricing for Anchorpoint and Diversion was not retrieved.
- No independent adoption data. Studio share between Perforce, Plastic, Git and SVN was not found.
- File-locking support per Git GUI is unchecked.

See also [[Tower|Tower]], [[Sourcetree|Sourcetree]], [[Fork|Fork]], [[Adjacent Tools]], [[Market Segments]].


Back to [[Market Research Hub]] | [[00 Index]] | [[Data Reliability]]
