# 📖 Lesson Plan — SQL-And-Data-Interview

> **Chain T — Interview Prep** | SQL and data interviews under time pressure: window functions, joins, and explaining a query out loud.

## What This Project Is

Drill the SQL that interviews actually test — window functions, multi-step CTEs, and the classic patterns — until syntax stops being the bottleneck.

## Learning Objectives

By the end I can:

1. Write every join type fluently, including anti-joins.
2. Use ROW_NUMBER, RANK, LAG/LEAD, and running totals without hesitation.
3. Structure multi-step logic with readable CTEs.
4. Solve top-N-per-group, gaps-and-islands, and deduplication.
5. Aggregate conditionally with FILTER / CASE.
6. Narrate a query aloud and reason about its performance.

## Software You Will Use

- PostgreSQL (local or in-browser).
- A practice dataset.
- A timer for drill sessions.

## Build Order

1. Drill joins until anti-joins are automatic.
2. Work through each window function on real data.
3. Solve top-N-per-group three different ways; compare.
4. Do gaps-and-islands and deduplication patterns.
5. Practise explaining a query aloud while writing it.
6. Time yourself on unseen problems.

## Common Mistakes to Avoid

- Reaching for a subquery where a window function is clearer.
- Confusing WHERE and HAVING.
- Forgetting that COUNT(*) and COUNT(col) treat NULLs differently.
- Writing correct SQL silently and never explaining the approach.
- Ignoring how the query would behave on a large table.

## Check Your Understanding

The quiz covers window-function semantics, join types, NULL handling in aggregates, and top-N-per-group.

## Why This Matters (Industry Application)

SQL screens are near-universal for data engineering, analytics, and backend roles, and they're usually
early — fail it and nothing else you know gets evaluated. Window functions and CTEs are the most commonly
tested and most commonly fumbled topics.

## Reflection Questions

- Which pattern do you still have to think about, and how will you drill it?
- How would you explain a window function to someone who has only used GROUP BY?
