# Drips Wave Points: A Complete Guide

Drips Wave uses a transparent, points-based system to value contributions and distribute rewards. This document explains how points work for **maintainers** and **contributors** in the Open Source Maintainer Toolkit.

---

## What Is Drips Wave?

Drips Wave is a recurring contribution sprint where maintainers nominate issues and contributors solve them for points. At the end of each Wave, the Wave Program’s reward pool is distributed among contributors based on their share of total points.

- **Free for maintainers.** Wave Organizers provide the funding pool.
- **Structured for contributors.** Issues are scoped and complexity-rated.
- **Transparent.** Leaderboards show real-time standings.

---

## Complexity Levels and Points

When a maintainer adds an issue to a Wave, they assign one of three complexity levels. This determines the fixed points awarded upon resolution:

| Complexity | Points | Description | Examples |
|---|---|---|---|
| **Trivial** | **100** | Typos, minor copy changes, very small bug fixes | Fix a broken link, correct a spelling error, add one missing sentence |
| **Medium** | **150** | Standard feature work or involved bug fixes | Expand a guide section, add code examples, create a new checklist |
| **High** | **200** | Complex work, refactors, or new integrations | Write a full tutorial, translate an entire document, restructure a guide |

The maintainer has final say on complexity. If a contributor believes an issue is harder than labelled, they should discuss it with the maintainer before the issue is resolved.

---

## How Contributors Earn Points

1. A maintainer adds an issue to a Wave and sets the complexity.
2. A contributor applies for the issue through the Drips Wave app or GitHub.
3. The maintainer assigns the issue to the contributor.
4. The contributor submits a PR and links it to the issue with `Closes #<number>`.
5. The maintainer reviews and merges.
6. The maintainer **closes the issue as completed**.
7. Drips Wave automatically awards the issue’s points to the contributor.

**Important:** Points are awarded when the **issue is closed**, not when the PR is merged. If your PR is merged but the issue remains open, politely remind the maintainer to close it.

---

## How Maintainers Award Bonus Points (Compliments)

After a Wave ends, maintainers have a **7-day Compliment Window**. During this window, they can issue Compliments to contributors for exceptional work. Compliments award bonus points on top of the issue’s base points.

Use Compliments to:

- Reward particularly thorough documentation
- Recognise a contributor who helped others in the issue thread
- Acknowledge work that exceeded the issue’s stated scope

---

## How Rewards Are Calculated

At the end of a Wave, the total Reward Budget (e.g., $50,000) is distributed among all contributors based on their share of total points earned during that Wave.
