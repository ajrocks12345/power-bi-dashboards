# Power BI Dashboard Projects

A collection of Power BI dashboards covering data modeling, Power Query, DAX, and dashboard design — built as part of interview assignments and personal practice.

## Projects

### 1. Purchase Analytics Dashboard
A Power BI dashboard analyzing an in-app purchases dataset (unique users, item revenue, top-selling items).

- KPI cards: unique users, avg items per user, avg price per item, total items sold, total revenue
- Calculated table (DAX) for "top 3 items per day" using `RANKX`
- Drillable matrix: revenue by country → date → item
- Synced date slicer across all visuals

**Files:** `purchase-analytics-dashboard/` — dashboard export

---

### 2. Mobile Game Funnel & Engagement Analysis
A Power BI report reconstructing a mobile game analytics dashboard from raw event-query exports — practicing tracing metrics from raw data through to a finished report.

- Isolated and cleaned individual event-query blocks from a large, non-tabular raw data export using Power Query
- Built a user funnel (onboarding → chapter selection → open world) as a funnel chart
- Chapter-level engagement breakdown: unique users, session frequency, rewarded video / interstitial ad engagement

**Files:** `mobile-game-funnel-analysis/` — dashboard export (raw source data not included, as it originates from a private company dataset)

---

## Tools & Techniques
Power BI (Power Query, DAX, data modeling), star-schema design, ETL-style data pipeline design.
