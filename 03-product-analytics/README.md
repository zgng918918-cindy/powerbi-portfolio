# Product Analytics Funnel & Retention Dashboard (Power BI)

This project demonstrates an end-to-end **Product Analytics** solution built in **Power BI**, focusing on user engagement, conversion funnel performance, and retention metrics for an e-commerce style digital product.

The dashboard enables stakeholders to understand how users move from **product views → cart → checkout → purchase**, and how active and sticky the user base is over time.


# Business Objectives

This dashboard answers key product questions:

- How many users are actively using the product?
- How sticky is the product (DAU vs MAU)?
- Where do users drop off in the funnel?
- Which funnel stage causes the biggest loss?
- Are conversions improving or declining over time?


# Key Metrics Implemented

## Engagement
- Total Users
- Total Sessions
- DAU (Daily Active Users)
- MAU (30-Day Rolling)
- Stickiness % (DAU / MAU)

## Funnel
- View Item Users
- Add to Cart Users
- Checkout Users
- Purchase Users
- Conversion Rates**
  - View → Cart
  - Cart → Checkout
  - Checkout → Purchase


# Core Analytics Logic

This dashboard was built using a star-schema model with relationships between:

- `Users`
- `Sessions`
- `Events`
- `Calendar`
- `Products`

Key DAX techniques used:
- `DISTINCTCOUNT` for user-level funnel
- Rolling windows for MAU
- `DATESINPERIOD` for time-based engagement
- Event-based funnel stage calculation
- Conversion rate measures


# Funnel Design

The funnel tracks unique users through the following event stages:

1. View Item
2. Add to Cart
3. Begin Checkout
4. Purchase

Users are counted uniquely per stage to avoid double counting and to reflect true drop-off.


## Dashboard Preview

# Overview
screenshots/overview.png

# Funnel Analysis
screenshots/Conversion Bar Chart.png


## Tools Used
- Microsoft Power BI
- DAX
- Power Query
- Star Schema Modeling


##  Files Included

| File | Description |
|------|------------|
| `Product_Analytics.pbix` | Power BI dashboard |
| `screenshots/` | Portfolio images |
| `README.md` | Project documentation |


##  What This Demonstrates

This project shows:
- Product-focused analytics thinking
- Funnel & conversion tracking
- Engagement and retention measurement
- Dashboard storytelling
- Real-world product KPIs used by FinTech and tech companies



