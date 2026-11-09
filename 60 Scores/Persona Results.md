---
title: Persona Results
description: "Pilot results: 27 clients scored against 12 personas, with ceiling, unknown count, and dealbreaker flags."
tags: [personas, rubric, results]
---

# Persona Results

> [!warning] Pilot, rule-derived, not tested
> Scores come from documented features by fixed rules ([[Scoring Criteria]]), not hands-on tests. Unknown evidence scores 0, so every score is a floor. Read the **Ceiling** and **Unknown** columns before trusting a rank. Gates flag, they never remove a client ([[Dealbreaker Gates]]).

Columns: **Score** counts unknowns as 0. **Ceiling** counts unknowns as 3. **Known-only** scores only known use cases. **Unknown** is the number of use cases with no evidence and the share of weight they carry. **Low evidence** appears when unknown weight exceeds 40%. Method: [[Scoring Rubric]]. Data: [[Score Matrix]].

## Score by persona (floor)

Clients are ordered by their average score across the 12 personas. This ordering is a convenience, not a ranking: personas have different needs.

| Client                            | P1  | P2  | P3  | P4  | P5  | P6  | P7  | P8  | P9  | P10 | P11 | P12 |
| --------------------------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [[Gitember]]                      | 63% | 64% | 59% | 53% | 50% | 45% | 52% | 38% | 24% | 53% | 47% | 67% |
| [[rgitui]]                        | 54% | 61% | 50% | 46% | 48% | 30% | 39% | 40% | 40% | 42% | 31% | 56% |
| [[Git Revenge]]                   | 46% | 49% | 37% | 42% | 46% | 37% | 45% | 37% | 42% | 59% | 53% | 28% |
| [[BeeBranch]]                     | 50% | 51% | 26% | 34% | 39% | 38% | 36% | 30% | 34% | 47% | 32% | 44% |
| [[GitKraken Desktop]]             | 50% | 48% | 38% | 37% | 28% | 41% | 34% | 22% | 21% | 39% | 31% | 48% |
| [[SmartGit]]                      | 50% | 50% | 34% | 43% | 27% | 31% | 28% | 22% | 22% | 41% | 26% | 44% |
| [[Tower]]                         | 56% | 51% | 35% | 36% | 25% | 34% | 20% | 8%  | 31% | 53% | 36% | 33% |
| [[GitHub Desktop]]                | 46% | 50% | 34% | 33% | 38% | 29% | 34% | 4%  | 19% | 52% | 32% | 30% |
| [[GitComet]]                      | 40% | 37% | 31% | 34% | 32% | 27% | 38% | 32% | 16% | 35% | 18% | 33% |
| [[Fork]]                          | 36% | 42% | 25% | 26% | 26% | 25% | 19% | 12% | 34% | 55% | 36% | 26% |
| [[GitLens (VS Code)]]             | 39% | 43% | 32% | 31% | 30% | 23% | 21% | 21% | 12% | 29% | 15% | 41% |
| [[Magit]]                         | 37% | 39% | 22% | 26% | 28% | 19% | 21% | 28% | 21% | 32% | 12% | 33% |
| [[Sourcetree]]                    | 36% | 38% | 23% | 24% | 24% | 19% | 17% | 10% | 19% | 41% | 22% | 43% |
| [[VS Code built-in Git]]          | 39% | 42% | 19% | 23% | 24% | 17% | 25% | 13% | 12% | 36% | 24% | 39% |
| [[Sublime Merge]]                 | 32% | 39% | 22% | 23% | 25% | 22% | 19% | 23% | 28% | 32% | 22% | 22% |
| [[TortoiseGit]]                   | 34% | 37% | 23% | 24% | 31% | 16% | 21% | 13% | 26% | 33% | 18% | 33% |
| [[LazyGit]]                       | 28% | 32% | 24% | 28% | 28% | 17% | 19% | 30% | 24% | 23% | 12% | 24% |
| [[SourceGit]]                     | 32% | 35% | 19% | 23% | 20% | 17% | 16% | 21% | 16% | 33% | 18% | 39% |
| [[git-gui and gitk]]              | 37% | 38% | 16% | 19% | 19% | 14% | 19% | 12% | 7%  | 36% | 21% | 46% |
| [[GitButler]]                     | 36% | 35% | 17% | 17% | 17% | 18% | 17% | 24% | 14% | 33% | 22% | 24% |
| [[JetBrains IDE Git]]             | 31% | 33% | 16% | 18% | 14% | 16% | 16% | 18% | 19% | 27% | 24% | 28% |
| [[Desktop Plus]]                  | 37% | 29% | 20% | 20% | 22% | 19% | 24% | 13% | 0%  | 27% | 8%  | 33% |
| [[GitUI]]                         | 26% | 30% | 14% | 17% | 26% | 19% | 19% | 20% | 18% | 23% | 21% | 22% |
| [[ForkPlus]]                      | 26% | 30% | 20% | 18% | 16% | 16% | 18% | 12% | 6%  | 33% | 24% | 31% |
| [[GitUp]]                         | 33% | 35% | 10% | 11% | 18% | 12% | 11% | 2%  | 7%  | 39% | 26% | 31% |
| [[Visual Studio Git integration]] | 18% | 18% | 13% | 14% | 9%  | 12% | 8%  | 3%  | 2%  | 15% | 3%  | 15% |
| [[Anchorpoint]]                   | 17% | 18% | 9%  | 11% | 2%  | 12% | 4%  | 0%  | 2%  | 21% | 10% | 20% |

## P1: Student learning git

Persona page: [[Student Learning Git]]. Total weight 30. Gates for this persona: G01 No free, education, or open-source path, G22 Hides concepts with no way to see more, G23 No undo and no warning before destructive actions.

| Rank | Client                            | Score | Ceiling | Known-only | Unknown        | Evidence     | Gates triggered | Gates unknown |
| ---- | --------------------------------- | ----- | ------- | ---------- | -------------- | ------------ | --------------- | ------------- |
| 1    | [[Gitember]]                      | 63%   | 83%     | 79%        | 3 of 13 (20%)  |              | -               | 1             |
| 2    | [[Tower]]                         | 56%   | 89%     | 83%        | 5 of 13 (33%)  |              | -               | 0             |
| 3    | [[rgitui]]                        | 54%   | 71%     | 65%        | 2 of 13 (17%)  |              | -               | 1             |
| 4    | [[SmartGit]]                      | 50%   | 90%     | 83%        | 6 of 13 (40%)  |              | -               | 1             |
| 5    | [[BeeBranch]]                     | 50%   | 73%     | 65%        | 4 of 13 (23%)  |              | -               | 0             |
| 6    | [[GitKraken Desktop]]             | 50%   | 73%     | 65%        | 4 of 13 (23%)  |              | -               | 1             |
| 7    | [[GitHub Desktop]]                | 46%   | 86%     | 76%        | 5 of 13 (40%)  |              | -               | 2             |
| 8    | [[Git Revenge]]                   | 46%   | 79%     | 68%        | 5 of 13 (33%)  |              | -               | 2             |
| 9    | [[GitComet]]                      | 40%   | 77%     | 63%        | 6 of 13 (37%)  |              | -               | 2             |
| 10   | [[GitLens (VS Code)]]             | 39%   | 82%     | 69%        | 5 of 13 (43%)  | Low evidence | -               | 1             |
| 11   | [[VS Code built-in Git]]          | 39%   | 79%     | 65%        | 6 of 13 (40%)  |              | -               | 1             |
| 12   | [[git-gui and gitk]]              | 37%   | 87%     | 73%        | 8 of 13 (50%)  | Low evidence | -               | 1             |
| 13   | [[Desktop Plus]]                  | 37%   | 83%     | 69%        | 7 of 13 (47%)  | Low evidence | -               | 2             |
| 14   | [[Magit]]                         | 37%   | 83%     | 69%        | 6 of 13 (47%)  | Low evidence | -               | 2             |
| 15   | [[Sourcetree]]                    | 36%   | 82%     | 67%        | 7 of 13 (47%)  | Low evidence | -               | 1             |
| 16   | [[Fork]]                          | 36%   | 69%     | 53%        | 5 of 13 (33%)  |              | G01             | 1             |
| 17   | [[GitButler]]                     | 36%   | 69%     | 53%        | 5 of 13 (33%)  |              | -               | 2             |
| 18   | [[TortoiseGit]]                   | 34%   | 71%     | 54%        | 5 of 13 (37%)  |              | -               | 1             |
| 19   | [[GitUp]]                         | 33%   | 83%     | 67%        | 8 of 13 (50%)  | Low evidence | -               | 0             |
| 20   | [[SourceGit]]                     | 32%   | 89%     | 74%        | 8 of 13 (57%)  | Low evidence | -               | 1             |
| 21   | [[Sublime Merge]]                 | 32%   | 79%     | 60%        | 6 of 13 (47%)  | Low evidence | G01             | 2             |
| 22   | [[JetBrains IDE Git]]             | 31%   | 78%     | 58%        | 6 of 13 (47%)  | Low evidence | -               | 2             |
| 23   | [[LazyGit]]                       | 28%   | 81%     | 60%        | 7 of 13 (53%)  | Low evidence | -               | 2             |
| 24   | [[ForkPlus]]                      | 26%   | 82%     | 59%        | 8 of 13 (57%)  | Low evidence | -               | 3             |
| 25   | [[GitUI]]                         | 26%   | 82%     | 59%        | 8 of 13 (57%)  | Low evidence | -               | 2             |
| 26   | [[Visual Studio Git integration]] | 18%   | 88%     | 59%        | 9 of 13 (70%)  | Low evidence | -               | 3             |
| 27   | [[Anchorpoint]]                   | 17%   | 87%     | 56%        | 10 of 13 (70%) | Low evidence | -               | 2             |

## P2: Solo developer (hobby)

Persona page: [[Hobby Solo Developer]]. Total weight 28. Gates for this persona: G02 Free tier excludes private repositories, G03 Subscription-only licensing, G04 Mandatory account for local use.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Gitember]] | 64% | 82% | 78% | 2 of 13 (18%) |  | - | 1 |
| 2 | [[rgitui]] | 61% | 68% | 65% | 2 of 13 (7%) |  | - | 3 |
| 3 | [[Tower]] | 51% | 80% | 72% | 4 of 13 (29%) |  | G03 | 1 |
| 4 | [[BeeBranch]] | 51% | 76% | 68% | 4 of 13 (25%) |  | - | 1 |
| 5 | [[SmartGit]] | 50% | 93% | 88% | 6 of 13 (43%) | Low evidence | - | 1 |
| 6 | [[GitHub Desktop]] | 50% | 82% | 74% | 4 of 13 (32%) |  | - | 1 |
| 7 | [[Git Revenge]] | 49% | 81% | 72% | 4 of 13 (32%) |  | - | 3 |
| 8 | [[GitKraken Desktop]] | 48% | 73% | 63% | 4 of 13 (25%) |  | G02 | 1 |
| 9 | [[GitLens (VS Code)]] | 43% | 79% | 67% | 5 of 13 (36%) |  | - | 1 |
| 10 | [[VS Code built-in Git]] | 42% | 77% | 65% | 6 of 13 (36%) |  | - | 1 |
| 11 | [[Fork]] | 42% | 70% | 58% | 4 of 13 (29%) |  | - | 1 |
| 12 | [[Magit]] | 39% | 82% | 69% | 6 of 13 (43%) | Low evidence | - | 1 |
| 13 | [[Sublime Merge]] | 39% | 82% | 69% | 6 of 13 (43%) | Low evidence | - | 1 |
| 14 | [[git-gui and gitk]] | 38% | 88% | 76% | 8 of 13 (50%) | Low evidence | - | 1 |
| 15 | [[Sourcetree]] | 38% | 81% | 67% | 6 of 13 (43%) | Low evidence | - | 1 |
| 16 | [[GitComet]] | 37% | 83% | 69% | 7 of 13 (46%) | Low evidence | - | 1 |
| 17 | [[TortoiseGit]] | 37% | 69% | 54% | 5 of 13 (32%) |  | - | 1 |
| 18 | [[SourceGit]] | 35% | 88% | 74% | 7 of 13 (54%) | Low evidence | - | 1 |
| 19 | [[GitUp]] | 35% | 85% | 69% | 8 of 13 (50%) | Low evidence | - | 1 |
| 20 | [[GitButler]] | 35% | 74% | 57% | 6 of 13 (39%) |  | - | 3 |
| 21 | [[JetBrains IDE Git]] | 33% | 76% | 58% | 6 of 13 (43%) | Low evidence | - | 3 |
| 22 | [[LazyGit]] | 32% | 82% | 64% | 7 of 13 (50%) | Low evidence | - | 1 |
| 23 | [[GitUI]] | 30% | 83% | 64% | 8 of 13 (54%) | Low evidence | - | 1 |
| 24 | [[ForkPlus]] | 30% | 80% | 60% | 7 of 13 (50%) | Low evidence | - | 3 |
| 25 | [[Desktop Plus]] | 29% | 93% | 80% | 9 of 13 (64%) | Low evidence | - | 1 |
| 26 | [[Anchorpoint]] | 18% | 86% | 56% | 9 of 13 (68%) | Low evidence | - | 2 |
| 27 | [[Visual Studio Git integration]] | 18% | 86% | 56% | 9 of 13 (68%) | Low evidence | - | 3 |

## P3: Open source solo maintainer

Persona page: [[Open Source Solo Maintainer]]. Total weight 37. Gates for this persona: G01 No free, education, or open-source path, G06 No pull request checkout or patch apply, G07 Commit signing unsupported or bypassed.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Gitember]] | 59% | 76% | 71% | 3 of 15 (16%) |  | - | 1 |
| 2 | [[rgitui]] | 50% | 79% | 71% | 5 of 15 (30%) |  | - | 2 |
| 3 | [[GitKraken Desktop]] | 38% | 84% | 70% | 7 of 15 (46%) | Low evidence | - | 1 |
| 4 | [[Git Revenge]] | 37% | 77% | 62% | 7 of 15 (41%) | Low evidence | - | 2 |
| 5 | [[Tower]] | 35% | 86% | 72% | 8 of 15 (51%) | Low evidence | G01 | 1 |
| 6 | [[GitHub Desktop]] | 34% | 83% | 67% | 8 of 15 (49%) | Low evidence | - | 1 |
| 7 | [[SmartGit]] | 34% | 83% | 67% | 8 of 15 (49%) | Low evidence | - | 1 |
| 8 | [[GitLens (VS Code)]] | 32% | 80% | 61% | 8 of 15 (49%) | Low evidence | - | 1 |
| 9 | [[GitComet]] | 31% | 87% | 71% | 9 of 15 (57%) | Low evidence | - | 1 |
| 10 | [[BeeBranch]] | 26% | 83% | 60% | 9 of 15 (57%) | Low evidence | - | 1 |
| 11 | [[Fork]] | 25% | 79% | 55% | 9 of 15 (54%) | Low evidence | G01 | 2 |
| 12 | [[LazyGit]] | 24% | 86% | 64% | 10 of 15 (62%) | Low evidence | - | 2 |
| 13 | [[TortoiseGit]] | 23% | 86% | 62% | 10 of 15 (62%) | Low evidence | - | 2 |
| 14 | [[Sourcetree]] | 23% | 85% | 60% | 10 of 15 (62%) | Low evidence | - | 2 |
| 15 | [[Magit]] | 22% | 92% | 73% | 11 of 15 (70%) | Low evidence | - | 2 |
| 16 | [[Sublime Merge]] | 22% | 84% | 57% | 10 of 15 (62%) | Low evidence | G01 | 2 |
| 17 | [[Desktop Plus]] | 20% | 93% | 73% | 11 of 15 (73%) | Low evidence | - | 2 |
| 18 | [[ForkPlus]] | 20% | 93% | 73% | 11 of 15 (73%) | Low evidence | - | 3 |
| 19 | [[SourceGit]] | 19% | 97% | 88% | 12 of 15 (78%) | Low evidence | - | 2 |
| 20 | [[VS Code built-in Git]] | 19% | 97% | 88% | 12 of 15 (78%) | Low evidence | - | 2 |
| 21 | [[GitButler]] | 17% | 87% | 58% | 10 of 15 (70%) | Low evidence | - | 3 |
| 22 | [[JetBrains IDE Git]] | 16% | 95% | 75% | 12 of 15 (78%) | Low evidence | - | 3 |
| 23 | [[git-gui and gitk]] | 16% | 95% | 75% | 12 of 15 (78%) | Low evidence | - | 2 |
| 24 | [[GitUI]] | 14% | 100% | 100% | 13 of 15 (86%) | Low evidence | - | 2 |
| 25 | [[Visual Studio Git integration]] | 13% | 91% | 58% | 12 of 15 (78%) | Low evidence | - | 2 |
| 26 | [[GitUp]] | 10% | 96% | 73% | 13 of 15 (86%) | Low evidence | - | 2 |
| 27 | [[Anchorpoint]] | 9% | 95% | 67% | 13 of 15 (86%) | Low evidence | - | 2 |

## P4: Open source team

Persona page: [[Open Source Team]]. Total weight 35. Gates for this persona: G01 No free, education, or open-source path, G07 Commit signing unsupported or bypassed, G08 Ignores repository hooks, templates, or git configuration.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Gitember]] | 53% | 79% | 72% | 4 of 15 (26%) |  | - | 2 |
| 2 | [[rgitui]] | 46% | 80% | 70% | 5 of 15 (34%) |  | - | 3 |
| 3 | [[SmartGit]] | 43% | 83% | 71% | 7 of 15 (40%) |  | - | 1 |
| 4 | [[Git Revenge]] | 42% | 79% | 67% | 7 of 15 (37%) |  | - | 1 |
| 5 | [[GitKraken Desktop]] | 37% | 86% | 72% | 8 of 15 (49%) | Low evidence | - | 2 |
| 6 | [[Tower]] | 36% | 85% | 70% | 8 of 15 (49%) | Low evidence | G01 | 2 |
| 7 | [[GitComet]] | 34% | 86% | 71% | 8 of 15 (51%) | Low evidence | - | 1 |
| 8 | [[BeeBranch]] | 34% | 83% | 67% | 8 of 15 (49%) | Low evidence | - | 1 |
| 9 | [[GitHub Desktop]] | 33% | 85% | 69% | 9 of 15 (51%) | Low evidence | - | 2 |
| 10 | [[GitLens (VS Code)]] | 31% | 86% | 69% | 9 of 15 (54%) | Low evidence | - | 2 |
| 11 | [[LazyGit]] | 28% | 88% | 69% | 9 of 15 (60%) | Low evidence | - | 2 |
| 12 | [[Magit]] | 26% | 91% | 75% | 10 of 15 (66%) | Low evidence | - | 2 |
| 13 | [[Fork]] | 26% | 77% | 53% | 8 of 15 (51%) | Low evidence | G01 | 2 |
| 14 | [[Sourcetree]] | 24% | 84% | 60% | 9 of 15 (60%) | Low evidence | - | 2 |
| 15 | [[TortoiseGit]] | 24% | 84% | 60% | 9 of 15 (60%) | Low evidence | - | 2 |
| 16 | [[SourceGit]] | 23% | 97% | 89% | 11 of 15 (74%) | Low evidence | - | 2 |
| 17 | [[VS Code built-in Git]] | 23% | 97% | 89% | 12 of 15 (74%) | Low evidence | - | 2 |
| 18 | [[Sublime Merge]] | 23% | 86% | 62% | 10 of 15 (63%) | Low evidence | G01 | 2 |
| 19 | [[Desktop Plus]] | 20% | 94% | 78% | 12 of 15 (74%) | Low evidence | - | 2 |
| 20 | [[git-gui and gitk]] | 19% | 96% | 83% | 12 of 15 (77%) | Low evidence | - | 2 |
| 21 | [[ForkPlus]] | 18% | 95% | 79% | 12 of 15 (77%) | Low evidence | - | 3 |
| 22 | [[JetBrains IDE Git]] | 18% | 95% | 79% | 12 of 15 (77%) | Low evidence | - | 3 |
| 23 | [[GitUI]] | 17% | 100% | 100% | 13 of 15 (83%) | Low evidence | - | 2 |
| 24 | [[GitButler]] | 17% | 91% | 67% | 11 of 15 (74%) | Low evidence | - | 3 |
| 25 | [[Visual Studio Git integration]] | 14% | 89% | 56% | 12 of 15 (74%) | Low evidence | - | 3 |
| 26 | [[Anchorpoint]] | 11% | 94% | 67% | 13 of 15 (83%) | Low evidence | - | 2 |
| 27 | [[GitUp]] | 11% | 94% | 67% | 13 of 15 (83%) | Low evidence | - | 2 |

## P5: Corporate user (self-purchased)

Persona page: [[Corporate User (Self-Purchased)]]. Total weight 40. Gates for this persona: G05 License tied to one machine, G09 Cannot authenticate to enterprise or self-hosted hosts, G10 Data leaves the machine with no user control.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Gitember]] | 50% | 80% | 71% | 5 of 16 (30%) |  | - | 3 |
| 2 | [[rgitui]] | 48% | 78% | 69% | 5 of 16 (30%) |  | - | 3 |
| 3 | [[Git Revenge]] | 46% | 73% | 63% | 5 of 16 (28%) |  | - | 2 |
| 4 | [[BeeBranch]] | 39% | 77% | 63% | 7 of 16 (38%) |  | - | 2 |
| 5 | [[GitHub Desktop]] | 38% | 88% | 77% | 9 of 16 (50%) | Low evidence | - | 3 |
| 6 | [[GitComet]] | 32% | 84% | 67% | 9 of 16 (52%) | Low evidence | - | 3 |
| 7 | [[TortoiseGit]] | 31% | 83% | 65% | 9 of 16 (52%) | Low evidence | - | 3 |
| 8 | [[GitLens (VS Code)]] | 30% | 85% | 67% | 9 of 16 (55%) | Low evidence | - | 3 |
| 9 | [[Magit]] | 28% | 86% | 67% | 10 of 16 (57%) | Low evidence | - | 3 |
| 10 | [[LazyGit]] | 28% | 88% | 69% | 10 of 16 (60%) | Low evidence | - | 3 |
| 11 | [[GitKraken Desktop]] | 28% | 82% | 61% | 9 of 16 (55%) | Low evidence | - | 3 |
| 12 | [[SmartGit]] | 27% | 84% | 63% | 10 of 16 (57%) | Low evidence | - | 3 |
| 13 | [[GitUI]] | 26% | 93% | 79% | 11 of 16 (68%) | Low evidence | - | 3 |
| 14 | [[Fork]] | 26% | 83% | 61% | 10 of 16 (57%) | Low evidence | - | 3 |
| 15 | [[Tower]] | 25% | 95% | 83% | 12 of 16 (70%) | Low evidence | - | 3 |
| 16 | [[Sublime Merge]] | 25% | 85% | 62% | 10 of 16 (60%) | Low evidence | - | 3 |
| 17 | [[Sourcetree]] | 24% | 89% | 69% | 11 of 16 (65%) | Low evidence | - | 3 |
| 18 | [[VS Code built-in Git]] | 24% | 89% | 69% | 11 of 16 (65%) | Low evidence | - | 3 |
| 19 | [[Desktop Plus]] | 22% | 92% | 75% | 12 of 16 (70%) | Low evidence | - | 3 |
| 20 | [[SourceGit]] | 20% | 98% | 89% | 13 of 16 (78%) | Low evidence | - | 3 |
| 21 | [[git-gui and gitk]] | 19% | 92% | 70% | 12 of 16 (72%) | Low evidence | - | 3 |
| 22 | [[GitUp]] | 18% | 98% | 92% | 13 of 16 (80%) | Low evidence | - | 3 |
| 23 | [[GitButler]] | 17% | 82% | 48% | 11 of 16 (65%) | Low evidence | - | 3 |
| 24 | [[ForkPlus]] | 16% | 88% | 58% | 12 of 16 (72%) | Low evidence | - | 3 |
| 25 | [[JetBrains IDE Git]] | 14% | 87% | 52% | 12 of 16 (72%) | Low evidence | - | 3 |
| 26 | [[Visual Studio Git integration]] | 9% | 97% | 73% | 14 of 16 (88%) | Low evidence | - | 3 |
| 27 | [[Anchorpoint]] | 2% | 95% | 33% | 15 of 16 (92%) | Low evidence | - | 3 |

## P6: Corporate user (mandated and funded)

Persona page: [[Corporate User (Mandated and Funded)]]. Total weight 43. Gates for this persona: G11 No central control of telemetry and AI, G12 No single sign-on or central administration, G13 No vendor security documentation.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Gitember]] | 45% | 82% | 72% | 6 of 17 (37%) |  | - | 3 |
| 2 | [[GitKraken Desktop]] | 41% | 90% | 80% | 8 of 17 (49%) | Low evidence | - | 2 |
| 3 | [[BeeBranch]] | 38% | 78% | 63% | 7 of 17 (40%) |  | - | 2 |
| 4 | [[Git Revenge]] | 37% | 79% | 64% | 7 of 17 (42%) | Low evidence | - | 3 |
| 5 | [[Tower]] | 34% | 92% | 81% | 10 of 17 (58%) | Low evidence | - | 2 |
| 6 | [[SmartGit]] | 31% | 89% | 74% | 10 of 17 (58%) | Low evidence | - | 3 |
| 7 | [[rgitui]] | 30% | 81% | 62% | 8 of 17 (51%) | Low evidence | - | 3 |
| 8 | [[GitHub Desktop]] | 29% | 90% | 75% | 10 of 17 (60%) | Low evidence | - | 3 |
| 9 | [[GitComet]] | 27% | 85% | 65% | 10 of 17 (58%) | Low evidence | - | 3 |
| 10 | [[Fork]] | 25% | 90% | 71% | 11 of 17 (65%) | Low evidence | - | 3 |
| 11 | [[GitLens (VS Code)]] | 23% | 88% | 67% | 11 of 17 (65%) | Low evidence | - | 3 |
| 12 | [[Sublime Merge]] | 22% | 95% | 81% | 12 of 17 (72%) | Low evidence | - | 3 |
| 13 | [[Sourcetree]] | 19% | 96% | 83% | 13 of 17 (77%) | Low evidence | - | 3 |
| 14 | [[Desktop Plus]] | 19% | 89% | 64% | 12 of 17 (70%) | Low evidence | - | 3 |
| 15 | [[Magit]] | 19% | 89% | 64% | 12 of 17 (70%) | Low evidence | - | 3 |
| 16 | [[GitUI]] | 19% | 95% | 80% | 13 of 17 (77%) | Low evidence | - | 3 |
| 17 | [[GitButler]] | 18% | 90% | 64% | 12 of 17 (72%) | Low evidence | - | 3 |
| 18 | [[LazyGit]] | 17% | 94% | 73% | 13 of 17 (77%) | Low evidence | - | 3 |
| 19 | [[SourceGit]] | 17% | 94% | 73% | 13 of 17 (77%) | Low evidence | - | 3 |
| 20 | [[VS Code built-in Git]] | 17% | 94% | 73% | 13 of 17 (77%) | Low evidence | - | 3 |
| 21 | [[ForkPlus]] | 16% | 92% | 67% | 13 of 17 (77%) | Low evidence | - | 3 |
| 22 | [[JetBrains IDE Git]] | 16% | 92% | 67% | 13 of 17 (77%) | Low evidence | - | 3 |
| 23 | [[TortoiseGit]] | 16% | 88% | 56% | 12 of 17 (72%) | Low evidence | - | 3 |
| 24 | [[git-gui and gitk]] | 14% | 95% | 75% | 14 of 17 (81%) | Low evidence | - | 3 |
| 25 | [[Anchorpoint]] | 12% | 94% | 67% | 14 of 17 (81%) | Low evidence | - | 3 |
| 26 | [[GitUp]] | 12% | 89% | 53% | 13 of 17 (77%) | Low evidence | - | 3 |
| 27 | [[Visual Studio Git integration]] | 12% | 91% | 56% | 14 of 17 (79%) | Low evidence | - | 3 |

## P7: Contractor or consultant

Persona page: [[Contractor or Consultant]]. Total weight 32. Gates for this persona: G10 Data leaves the machine with no user control, G14 No per-repository identity separation.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Gitember]] | 52% | 77% | 69% | 3 of 13 (25%) |  | - | 2 |
| 2 | [[Git Revenge]] | 45% | 76% | 65% | 5 of 13 (31%) |  | - | 0 |
| 3 | [[rgitui]] | 39% | 79% | 65% | 5 of 13 (41%) | Low evidence | - | 2 |
| 4 | [[GitComet]] | 38% | 81% | 67% | 6 of 13 (44%) | Low evidence | - | 2 |
| 5 | [[BeeBranch]] | 36% | 77% | 61% | 6 of 13 (41%) | Low evidence | - | 0 |
| 6 | [[GitHub Desktop]] | 34% | 91% | 79% | 7 of 13 (56%) | Low evidence | - | 2 |
| 7 | [[GitKraken Desktop]] | 34% | 84% | 69% | 6 of 13 (50%) | Low evidence | - | 2 |
| 8 | [[SmartGit]] | 28% | 88% | 69% | 8 of 13 (59%) | Low evidence | - | 1 |
| 9 | [[VS Code built-in Git]] | 25% | 91% | 73% | 9 of 13 (66%) | Low evidence | - | 2 |
| 10 | [[Desktop Plus]] | 24% | 93% | 77% | 9 of 13 (69%) | Low evidence | - | 1 |
| 11 | [[GitLens (VS Code)]] | 21% | 96% | 83% | 9 of 13 (75%) | Low evidence | - | 2 |
| 12 | [[Magit]] | 21% | 90% | 67% | 9 of 13 (69%) | Low evidence | - | 2 |
| 13 | [[TortoiseGit]] | 21% | 86% | 61% | 9 of 13 (66%) | Low evidence | - | 2 |
| 14 | [[Tower]] | 20% | 98% | 90% | 10 of 13 (78%) | Low evidence | - | 2 |
| 15 | [[GitUI]] | 19% | 94% | 75% | 10 of 13 (75%) | Low evidence | - | 2 |
| 16 | [[LazyGit]] | 19% | 94% | 75% | 10 of 13 (75%) | Low evidence | - | 2 |
| 17 | [[Sublime Merge]] | 19% | 94% | 75% | 10 of 13 (75%) | Low evidence | - | 2 |
| 18 | [[git-gui and gitk]] | 19% | 94% | 75% | 10 of 13 (75%) | Low evidence | - | 2 |
| 19 | [[Fork]] | 19% | 88% | 60% | 9 of 13 (69%) | Low evidence | - | 2 |
| 20 | [[ForkPlus]] | 18% | 90% | 63% | 9 of 13 (72%) | Low evidence | - | 2 |
| 21 | [[Sourcetree]] | 17% | 92% | 67% | 10 of 13 (75%) | Low evidence | - | 2 |
| 22 | [[GitButler]] | 17% | 89% | 59% | 9 of 13 (72%) | Low evidence | - | 2 |
| 23 | [[SourceGit]] | 16% | 100% | 100% | 11 of 13 (84%) | Low evidence | - | 2 |
| 24 | [[JetBrains IDE Git]] | 16% | 91% | 62% | 10 of 13 (75%) | Low evidence | - | 2 |
| 25 | [[GitUp]] | 11% | 96% | 73% | 11 of 13 (84%) | Low evidence | - | 2 |
| 26 | [[Visual Studio Git integration]] | 8% | 96% | 67% | 11 of 13 (88%) | Low evidence | - | 2 |
| 27 | [[Anchorpoint]] | 4% | 98% | 67% | 12 of 13 (94%) | Low evidence | - | 2 |

## P8: DevOps or SRE engineer

Persona page: [[DevOps or SRE]]. Total weight 30. Gates for this persona: G15 No native build for the persona's operating system, G16 Not usable from a terminal or remote session.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[rgitui]] | 40% | 83% | 71% | 6 of 13 (43%) | Low evidence | - | 1 |
| 2 | [[Gitember]] | 38% | 84% | 71% | 6 of 13 (47%) | Low evidence | - | 1 |
| 3 | [[Git Revenge]] | 37% | 87% | 73% | 6 of 13 (50%) | Low evidence | - | 1 |
| 4 | [[GitComet]] | 32% | 79% | 60% | 7 of 13 (47%) | Low evidence | - | 0 |
| 5 | [[BeeBranch]] | 30% | 90% | 75% | 8 of 13 (60%) | Low evidence | - | 1 |
| 6 | [[LazyGit]] | 30% | 87% | 69% | 8 of 13 (57%) | Low evidence | - | 0 |
| 7 | [[Magit]] | 28% | 91% | 76% | 9 of 13 (63%) | Low evidence | - | 1 |
| 8 | [[GitButler]] | 24% | 78% | 52% | 7 of 13 (53%) | Low evidence | - | 0 |
| 9 | [[Sublime Merge]] | 23% | 90% | 70% | 9 of 13 (67%) | Low evidence | - | 1 |
| 10 | [[GitKraken Desktop]] | 22% | 89% | 67% | 9 of 13 (67%) | Low evidence | - | 0 |
| 11 | [[SmartGit]] | 22% | 86% | 61% | 9 of 13 (63%) | Low evidence | - | 1 |
| 12 | [[SourceGit]] | 21% | 94% | 79% | 10 of 13 (73%) | Low evidence | - | 1 |
| 13 | [[GitLens (VS Code)]] | 21% | 84% | 58% | 8 of 13 (63%) | Low evidence | - | 1 |
| 14 | [[GitUI]] | 20% | 97% | 86% | 10 of 13 (77%) | Low evidence | - | 0 |
| 15 | [[JetBrains IDE Git]] | 18% | 91% | 67% | 10 of 13 (73%) | Low evidence | - | 1 |
| 16 | [[Desktop Plus]] | 13% | 93% | 67% | 11 of 13 (80%) | Low evidence | - | 0 |
| 17 | [[VS Code built-in Git]] | 13% | 93% | 67% | 11 of 13 (80%) | Low evidence | - | 1 |
| 18 | [[TortoiseGit]] | 13% | 70% | 31% | 8 of 13 (57%) | Low evidence | G15 | 0 |
| 19 | [[ForkPlus]] | 12% | 99% | 92% | 11 of 13 (87%) | Low evidence | - | 1 |
| 20 | [[git-gui and gitk]] | 12% | 96% | 73% | 11 of 13 (83%) | Low evidence | - | 1 |
| 21 | [[Fork]] | 12% | 79% | 37% | 9 of 13 (67%) | Low evidence | G15 | 1 |
| 22 | [[Sourcetree]] | 10% | 77% | 30% | 9 of 13 (67%) | Low evidence | G15 | 1 |
| 23 | [[Tower]] | 8% | 81% | 29% | 10 of 13 (73%) | Low evidence | G15 | 1 |
| 24 | [[GitHub Desktop]] | 4% | 84% | 22% | 10 of 13 (80%) | Low evidence | G15 | 1 |
| 25 | [[Visual Studio Git integration]] | 3% | 83% | 17% | 11 of 13 (80%) | Low evidence | G15 | 1 |
| 26 | [[GitUp]] | 2% | 89% | 17% | 11 of 13 (87%) | Low evidence | G15 | 1 |
| 27 | [[Anchorpoint]] | 0% | 90% | 0% | 12 of 13 (90%) | Low evidence | G15 | 1 |

## P9: Large repository engineer

Persona page: [[Monorepo Engineer]]. Total weight 30. Gates for this persona: G17 Unusable on large repositories, G18 Ignores sparse checkout or partial clone.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Git Revenge]] | 42% | 76% | 63% | 5 of 12 (33%) |  | - | 2 |
| 2 | [[rgitui]] | 40% | 80% | 67% | 5 of 12 (40%) |  | - | 2 |
| 3 | [[BeeBranch]] | 34% | 78% | 61% | 6 of 12 (43%) | Low evidence | - | 2 |
| 4 | [[Fork]] | 34% | 78% | 61% | 6 of 12 (43%) | Low evidence | - | 2 |
| 5 | [[Tower]] | 31% | 81% | 62% | 6 of 12 (50%) | Low evidence | - | 2 |
| 6 | [[Sublime Merge]] | 28% | 81% | 60% | 7 of 12 (53%) | Low evidence | - | 2 |
| 7 | [[TortoiseGit]] | 26% | 69% | 45% | 6 of 12 (43%) | Low evidence | - | 2 |
| 8 | [[LazyGit]] | 24% | 78% | 52% | 7 of 12 (53%) | Low evidence | - | 2 |
| 9 | [[Gitember]] | 24% | 74% | 49% | 6 of 12 (50%) | Low evidence | - | 2 |
| 10 | [[SmartGit]] | 22% | 76% | 48% | 7 of 12 (53%) | Low evidence | - | 2 |
| 11 | [[GitKraken Desktop]] | 21% | 84% | 58% | 7 of 12 (63%) | Low evidence | - | 2 |
| 12 | [[Magit]] | 21% | 84% | 58% | 8 of 12 (63%) | Low evidence | - | 2 |
| 13 | [[GitHub Desktop]] | 19% | 82% | 52% | 8 of 12 (63%) | Low evidence | - | 2 |
| 14 | [[JetBrains IDE Git]] | 19% | 82% | 52% | 8 of 12 (63%) | Low evidence | - | 2 |
| 15 | [[Sourcetree]] | 19% | 72% | 40% | 7 of 12 (53%) | Low evidence | - | 2 |
| 16 | [[GitUI]] | 18% | 91% | 67% | 9 of 12 (73%) | Low evidence | - | 1 |
| 17 | [[SourceGit]] | 16% | 89% | 58% | 9 of 12 (73%) | Low evidence | - | 2 |
| 18 | [[GitComet]] | 16% | 82% | 47% | 8 of 12 (67%) | Low evidence | - | 2 |
| 19 | [[GitButler]] | 14% | 78% | 39% | 8 of 12 (63%) | Low evidence | - | 2 |
| 20 | [[GitLens (VS Code)]] | 12% | 86% | 46% | 9 of 12 (73%) | Low evidence | - | 2 |
| 21 | [[VS Code built-in Git]] | 12% | 86% | 46% | 9 of 12 (73%) | Low evidence | - | 2 |
| 22 | [[GitUp]] | 7% | 97% | 67% | 11 of 12 (90%) | Low evidence | - | 2 |
| 23 | [[git-gui and gitk]] | 7% | 87% | 33% | 10 of 12 (80%) | Low evidence | - | 2 |
| 24 | [[ForkPlus]] | 6% | 89% | 33% | 10 of 12 (83%) | Low evidence | - | 2 |
| 25 | [[Anchorpoint]] | 2% | 96% | 33% | 11 of 12 (93%) | Low evidence | - | 2 |
| 26 | [[Visual Studio Git integration]] | 2% | 96% | 33% | 11 of 12 (93%) | Low evidence | - | 2 |
| 27 | [[Desktop Plus]] | 0% | 100% | - | 12 of 12 (100%) | Low evidence | - | 2 |

## P10: Creative or non-developer

Persona page: [[Creative or Non-Developer]]. Total weight 22. Gates for this persona: G19 Cannot handle binary files, G21 Needs the command line for ordinary tasks.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Git Revenge]] | 59% | 68% | 65% | 1 of 9 (9%) |  | - | 1 |
| 2 | [[Fork]] | 55% | 64% | 60% | 1 of 9 (9%) |  | - | 1 |
| 3 | [[Tower]] | 53% | 80% | 73% | 2 of 9 (27%) |  | - | 1 |
| 4 | [[Gitember]] | 53% | 67% | 61% | 1 of 9 (14%) |  | - | 1 |
| 5 | [[GitHub Desktop]] | 52% | 74% | 67% | 2 of 9 (23%) |  | - | 1 |
| 6 | [[BeeBranch]] | 47% | 79% | 69% | 3 of 9 (32%) |  | - | 2 |
| 7 | [[rgitui]] | 42% | 70% | 58% | 2 of 9 (27%) |  | - | 2 |
| 8 | [[SmartGit]] | 41% | 82% | 69% | 3 of 9 (41%) | Low evidence | - | 1 |
| 9 | [[Sourcetree]] | 41% | 73% | 60% | 3 of 9 (32%) |  | - | 1 |
| 10 | [[GitUp]] | 39% | 85% | 72% | 4 of 9 (45%) | Low evidence | - | 2 |
| 11 | [[GitKraken Desktop]] | 39% | 67% | 54% | 2 of 9 (27%) |  | - | 1 |
| 12 | [[git-gui and gitk]] | 36% | 82% | 67% | 4 of 9 (45%) | Low evidence | - | 2 |
| 13 | [[VS Code built-in Git]] | 36% | 77% | 62% | 3 of 9 (41%) | Low evidence | - | 2 |
| 14 | [[GitComet]] | 35% | 85% | 70% | 4 of 9 (50%) | Low evidence | - | 2 |
| 15 | [[SourceGit]] | 33% | 79% | 61% | 4 of 9 (45%) | Low evidence | - | 1 |
| 16 | [[GitButler]] | 33% | 74% | 56% | 4 of 9 (41%) | Low evidence | - | 2 |
| 17 | [[TortoiseGit]] | 33% | 74% | 56% | 3 of 9 (41%) | Low evidence | - | 2 |
| 18 | [[ForkPlus]] | 33% | 61% | 46% | 3 of 9 (27%) |  | - | 1 |
| 19 | [[Magit]] | 32% | 86% | 70% | 5 of 9 (55%) | Low evidence | - | 2 |
| 20 | [[Sublime Merge]] | 32% | 82% | 64% | 4 of 9 (50%) | Low evidence | - | 2 |
| 21 | [[GitLens (VS Code)]] | 29% | 88% | 70% | 5 of 9 (59%) | Low evidence | - | 2 |
| 22 | [[Desktop Plus]] | 27% | 95% | 86% | 6 of 9 (68%) | Low evidence | - | 2 |
| 23 | [[JetBrains IDE Git]] | 27% | 77% | 55% | 4 of 9 (50%) | Low evidence | - | 2 |
| 24 | [[GitUI]] | 23% | 77% | 50% | 5 of 9 (55%) | Low evidence | - | 2 |
| 25 | [[LazyGit]] | 23% | 77% | 50% | 5 of 9 (55%) | Low evidence | - | 2 |
| 26 | [[Anchorpoint]] | 21% | 76% | 47% | 5 of 9 (55%) | Low evidence | - | 1 |
| 27 | [[Visual Studio Git integration]] | 15% | 92% | 67% | 7 of 9 (77%) | Low evidence | - | 2 |

## P11: Data or ML practitioner

Persona page: [[Data or ML Practitioner]]. Total weight 24. Gates for this persona: G20 No useful diff for notebooks or large files.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Git Revenge]] | 53% | 78% | 70% | 3 of 10 (25%) |  | - | 0 |
| 2 | [[Gitember]] | 47% | 68% | 60% | 2 of 10 (21%) |  | - | 1 |
| 3 | [[Tower]] | 36% | 86% | 72% | 5 of 10 (50%) | Low evidence | - | 1 |
| 4 | [[Fork]] | 36% | 69% | 54% | 4 of 10 (33%) |  | - | 1 |
| 5 | [[BeeBranch]] | 32% | 82% | 64% | 5 of 10 (50%) | Low evidence | - | 1 |
| 6 | [[GitHub Desktop]] | 32% | 74% | 55% | 4 of 10 (42%) | Low evidence | - | 1 |
| 7 | [[GitKraken Desktop]] | 31% | 76% | 56% | 4 of 10 (46%) | Low evidence | - | 1 |
| 8 | [[rgitui]] | 31% | 76% | 56% | 4 of 10 (46%) | Low evidence | - | 1 |
| 9 | [[GitUp]] | 26% | 89% | 70% | 6 of 10 (62%) | Low evidence | - | 1 |
| 10 | [[SmartGit]] | 26% | 89% | 70% | 6 of 10 (62%) | Low evidence | - | 1 |
| 11 | [[JetBrains IDE Git]] | 24% | 86% | 63% | 6 of 10 (62%) | Low evidence | - | 1 |
| 12 | [[VS Code built-in Git]] | 24% | 86% | 63% | 6 of 10 (62%) | Low evidence | - | 1 |
| 13 | [[ForkPlus]] | 24% | 74% | 47% | 5 of 10 (50%) | Low evidence | - | 1 |
| 14 | [[Sublime Merge]] | 22% | 93% | 76% | 7 of 10 (71%) | Low evidence | - | 1 |
| 15 | [[GitButler]] | 22% | 85% | 59% | 6 of 10 (62%) | Low evidence | - | 1 |
| 16 | [[Sourcetree]] | 22% | 81% | 53% | 6 of 10 (58%) | Low evidence | - | 1 |
| 17 | [[GitUI]] | 21% | 92% | 71% | 7 of 10 (71%) | Low evidence | - | 1 |
| 18 | [[git-gui and gitk]] | 21% | 92% | 71% | 7 of 10 (71%) | Low evidence | - | 1 |
| 19 | [[GitComet]] | 18% | 89% | 62% | 7 of 10 (71%) | Low evidence | - | 1 |
| 20 | [[SourceGit]] | 18% | 89% | 62% | 7 of 10 (71%) | Low evidence | - | 1 |
| 21 | [[TortoiseGit]] | 18% | 81% | 48% | 6 of 10 (62%) | Low evidence | - | 1 |
| 22 | [[GitLens (VS Code)]] | 15% | 94% | 73% | 7 of 10 (79%) | Low evidence | - | 1 |
| 23 | [[LazyGit]] | 12% | 92% | 60% | 8 of 10 (79%) | Low evidence | - | 1 |
| 24 | [[Magit]] | 12% | 92% | 60% | 8 of 10 (79%) | Low evidence | - | 1 |
| 25 | [[Anchorpoint]] | 10% | 89% | 47% | 8 of 10 (79%) | Low evidence | - | 1 |
| 26 | [[Desktop Plus]] | 8% | 100% | 100% | 9 of 10 (92%) | Low evidence | - | 1 |
| 27 | [[Visual Studio Git integration]] | 3% | 94% | 33% | 9 of 10 (92%) | Low evidence | - | 1 |

## P12: Observer (Scrum Master, PM, reviewer)

Persona page: [[Non-Coding Observer]]. Total weight 18. Gates for this persona: G24 No safe read-only mode, G25 Needs developer concepts to get started.

| Rank | Client | Score | Ceiling | Known-only | Unknown | Evidence | Gates triggered | Gates unknown |
|---|---|---|---|---|---|---|---|---|
| 1 | [[Gitember]] | 67% | 83% | 80% | 1 of 8 (17%) |  | - | 2 |
| 2 | [[rgitui]] | 56% | 83% | 77% | 2 of 8 (28%) |  | - | 2 |
| 3 | [[GitKraken Desktop]] | 48% | 81% | 72% | 3 of 8 (33%) |  | - | 2 |
| 4 | [[git-gui and gitk]] | 46% | 85% | 76% | 3 of 8 (39%) |  | - | 2 |
| 5 | [[BeeBranch]] | 44% | 89% | 80% | 4 of 8 (44%) | Low evidence | - | 2 |
| 6 | [[SmartGit]] | 44% | 83% | 73% | 3 of 8 (39%) |  | - | 2 |
| 7 | [[Sourcetree]] | 43% | 81% | 70% | 3 of 8 (39%) |  | - | 2 |
| 8 | [[GitLens (VS Code)]] | 41% | 80% | 67% | 3 of 8 (39%) |  | - | 2 |
| 9 | [[SourceGit]] | 39% | 83% | 70% | 4 of 8 (44%) | Low evidence | - | 2 |
| 10 | [[VS Code built-in Git]] | 39% | 83% | 70% | 4 of 8 (44%) | Low evidence | - | 2 |
| 11 | [[Desktop Plus]] | 33% | 94% | 86% | 5 of 8 (61%) | Low evidence | - | 2 |
| 12 | [[GitComet]] | 33% | 94% | 86% | 5 of 8 (61%) | Low evidence | - | 2 |
| 13 | [[Magit]] | 33% | 94% | 86% | 5 of 8 (61%) | Low evidence | - | 2 |
| 14 | [[Tower]] | 33% | 78% | 60% | 4 of 8 (44%) | Low evidence | - | 2 |
| 15 | [[TortoiseGit]] | 33% | 72% | 55% | 3 of 8 (39%) |  | - | 2 |
| 16 | [[ForkPlus]] | 31% | 81% | 63% | 4 of 8 (50%) | Low evidence | - | 2 |
| 17 | [[GitUp]] | 31% | 76% | 57% | 4 of 8 (44%) | Low evidence | - | 2 |
| 18 | [[GitHub Desktop]] | 30% | 91% | 76% | 5 of 8 (61%) | Low evidence | - | 2 |
| 19 | [[Git Revenge]] | 28% | 83% | 62% | 4 of 8 (56%) | Low evidence | - | 2 |
| 20 | [[JetBrains IDE Git]] | 28% | 83% | 62% | 5 of 8 (56%) | Low evidence | - | 2 |
| 21 | [[Fork]] | 26% | 81% | 58% | 4 of 8 (56%) | Low evidence | - | 2 |
| 22 | [[GitButler]] | 24% | 85% | 62% | 5 of 8 (61%) | Low evidence | - | 2 |
| 23 | [[LazyGit]] | 24% | 80% | 54% | 4 of 8 (56%) | Low evidence | - | 2 |
| 24 | [[GitUI]] | 22% | 83% | 57% | 5 of 8 (61%) | Low evidence | - | 2 |
| 25 | [[Sublime Merge]] | 22% | 78% | 50% | 4 of 8 (56%) | Low evidence | - | 2 |
| 26 | [[Anchorpoint]] | 20% | 81% | 52% | 5 of 8 (61%) | Low evidence | - | 2 |
| 27 | [[Visual Studio Git integration]] | 15% | 87% | 53% | 6 of 8 (72%) | Low evidence | - | 2 |

