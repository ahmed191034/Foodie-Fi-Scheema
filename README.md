# Foodie-Fi SQL Case Study

SQL analysis of Foodie-Fi, a fictional subscription-video-on-demand service, based on the well-known [8 Week SQL Challenge](https://8weeksqlchallenge.com/) dataset. Covers schema design and subscriber-behaviour analysis: trial-to-paid conversion, plan upgrades/downgrades, and churn.

**Tools:** SQL (MySQL/PostgreSQL-compatible)

---

## Schema

Two tables:

- **`plans`** — the 5 subscription tiers: `trial`, `basic monthly`, `pro monthly`, `pro annual`, `churn`
- **`subscriptions`** — each customer's plan changes over time (`customer_id`, `plan_id`, `start_date`)

## Status

⚠️ **In progress.** The schema and seed data (`foodie_fi.sql`) are complete and load cleanly, but the analysis queries — churn rate, trial-to-paid conversion rate, plan upgrade/downgrade paths, revenue by plan — are not yet in this file. That's the part of a case study like this that actually demonstrates SQL analysis skill, so it's the next thing to add before treating this as a portfolio piece.

**Planned queries:**
- What % of trial customers convert to a paid plan?
- What's the churn rate, and how does it vary by starting plan?
- How many customers upgrade from monthly to annual plans, and how long does that take on average?
- What's monthly recurring revenue by plan tier?

## How to Use

1. Open `foodie_fi.sql` in your SQL client (MySQL, PostgreSQL, or SQLite, depending on setup).
2. Run the schema + seed data section first.
3. Run the analysis queries section once added.

## Notes

- Line-ending warnings (LF/CRLF) when opening on Windows are expected and can be ignored.
