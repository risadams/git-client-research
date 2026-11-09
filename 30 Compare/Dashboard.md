---
title: Dashboard
description: Dataview queries over client frontmatter. Requires the Dataview community plugin.
tags: [dashboard, dataview]
---

# Dashboard

## All rated clients, best for teams first

```dataview
TABLE category AS Category, audience_tier AS Tier, learning_fit AS Learn, solo_fit AS Solo, team_fit AS Team, ease_of_use AS Ease, confidence AS Conf
FROM "10 Clients"
WHERE team_fit
SORT team_fit DESC, learning_fit DESC
```

## Best for learning (learning fit 4 or higher)

```dataview
TABLE audience_tier AS Tier, learning_fit AS Learn, ease_of_use AS Ease, platforms AS Platforms, license AS License
FROM "10 Clients"
WHERE learning_fit >= 4
SORT learning_fit DESC, ease_of_use DESC
```

## Pro-tier clients

```dataview
TABLE team_fit AS Team, solo_fit AS Solo, platforms AS Platforms, license AS License
FROM "10 Clients"
WHERE audience_tier = "Pro"
SORT team_fit DESC
```

## Simple-tier clients

```dataview
TABLE learning_fit AS Learn, platforms AS Platforms, license AS License
FROM "10 Clients"
WHERE audience_tier = "Simple"
SORT learning_fit DESC
```

## Verified clients only (confidence V)

```dataview
TABLE category AS Category, platforms AS Platforms, license AS License, ease_of_use AS Ease
FROM "10 Clients"
WHERE confidence = "V"
SORT file.name ASC
```

## Clients per category

```dataview
TABLE length(rows) AS Clients
FROM "10 Clients"
GROUP BY category
SORT length(rows) DESC
```

## Clients per confidence level

```dataview
TABLE length(rows) AS Clients
FROM "10 Clients"
GROUP BY confidence
SORT confidence ASC
```

## Find a feature

Replace the slug with any feature from [[Features Index]], for example `stacked-branches`, `undo-and-redo`, `interactive-rebase`.

```dataview
TABLE category AS Category, platforms AS Platforms, confidence AS Conf
FROM "10 Clients"
WHERE contains(features, "stacked-branches")
SORT file.name ASC
```

## Clients with no feature tags yet

```dataview
LIST
FROM "10 Clients"
WHERE !features OR length(features) = 0
SORT file.name ASC
```

## Market research pages

- [[Market Research Hub]]
- [[Benchmarks]]
- [[Adjacent Tools]]
- [[Vendor Claims vs Evidence]]

Back to [[00 Index]]
