# SQL-And-Data-Interview

### SQL and data interviews under time pressure: window functions, joins, and explaining a query out loud.

![Chain T](https://img.shields.io/badge/Chain%20T-E11D48?style=for-the-badge) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge)](LICENSE-GPL) [![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue?style=for-the-badge)](LICENSE-AGPL)

[📖 Lesson Plan](docs/LESSON_PLAN.md)

<!-- SCREENSHOT PLACEHOLDER: docs/screenshots/overview.png -->

> ⬜ **Scaffold pending.** Directory created to portfolio standard; full content (README, lesson plan, tour + quiz, skeleton code) still to be built. Part of **Chain T — Interview Prep**.

## Why This Was Built

I use SQL constantly, but writing it live on a whiteboard while narrating is a different skill from writing
it in an editor with a database to test against. The gap is mostly recall and composure — window functions
and multi-step CTEs in particular are easy to reach for slowly and hard to reach for instantly.

This is deliberate practice on that gap: common interview patterns, drilled until the syntax stops being the
thing I'm thinking about, so I can spend the time on the actual problem.

## Why This Matters (Industry Application)

SQL screens are near-universal for data engineering, analytics, and backend roles, and they're usually
early — fail it and nothing else you know gets evaluated. Window functions and CTEs are the most commonly
tested and most commonly fumbled topics.

## Topics Covered

| Area | What this project covers |
|------|--------------------------|
| Joins | Inner, outer, self-joins, and anti-joins |
| Window functions | ROW_NUMBER, RANK, LAG/LEAD, running totals |
| CTEs | Structuring multi-step logic readably |
| Aggregation | GROUP BY, HAVING, and conditional aggregates |
| Common patterns | Top-N per group, gaps and islands, deduplication |
| Explaining | Narrating a query and reasoning about performance |

## How This Connects

Chain T (Interview Prep). Drills **SQL-For-Analytics** and the **Chain I** SQL depth into recall speed.

---
Dual licensed — [GPL v3](LICENSE-GPL) and [AGPL v3](LICENSE-AGPL).
