# Customer Churn Analysis Dashboard

A Power BI dashboard that diagnoses **why customers churn**, **who is most at risk**, and **when in the customer lifecycle they leave** — built to turn a 26.86% churn rate from a vague problem into a targeted, actionable retention strategy.

##  Overview

This dashboard analyzes **6,687 customers**, of whom **1,796 have churned**, across three connected views:

1. **Churn Problem (The Cause)** — breaks churn down by root-cause category (Competitor, Attitude, Dissatisfaction, Price, Other) and the specific reasons within each.
2. **Churn Problem according to Age** — segments churn by age cohort and age bin to surface both volume risk and rate risk.
3. **Churn Analysis according to Account Length & Service Calls** — maps churn against customer tenure and support-call volume to find lifecycle danger windows and early-warning signals.

##  Key Findings

| Metric | Value |
|---|---|
| Total Customers | 6,687 |
| Churned Customers | 1,796 |
| Overall Churn Rate | 26.86% |
| Top Churn Driver | Competitor offers (44.82% of churn) |
| Highest-Risk Age Group | 30–60 (56.6% of all churned customers) |
| Highest Churn Rate by Age | 52% at age 85 |
| Month-1 Churn Spike | ~600 customers churn in their first month |
| Service Call Tipping Point | At 3+ service calls, churned customers outnumber retained ones |

##  Business Insights

- **Competitive exposure is the #1 churn driver** — nearly half of all churn is tied to customers leaving for a better competitor offer, pointing to a pricing/offer-competitiveness gap rather than a service-quality issue.
- **Controllable churn is underweighted** — Attitude + Dissatisfaction account for ~32% of churn and are fully within the company's control, yet receive less attention than competitor-driven churn.
- **Churn rate climbs sharply with age** — from ~12% in the 20s to 52% at 85, signaling a plan-fit/affordability problem for older customers even though they're a smaller slice of total volume.
- **Onboarding is the biggest single failure point** — roughly a third of all churned customers leave within their first month, before they experience the product's full value.
- **Service calls are a leading indicator** — the relationship between support calls and churn flips dramatically at the 3-call mark, giving a clear, actionable early-warning trigger.

##  Recommendations

1. **Launch a competitive win-back offer** targeted at month-to-month customers to counter the 44.82% of churn driven by competitor offers.
2. **Redesign the first-90-day onboarding journey** to flatten the ~600-customer month-1 churn cliff.
3. **Trigger automatic retention outreach at the 2nd service call**, before the 3rd-call threshold where churn odds flip.
4. **Build age-targeted retention programs** — senior-focused plan reviews for 60+ customers, and loyalty/bundle offers for the high-volume 30–60 segment.
5. **Launch a renewal campaign starting at month 60–65**, ahead of the contract-end churn spike around month 70.

##  Tools Used

- **Power BI** — data modeling, DAX measures, and interactive report design
- Visuals: bar charts, pie chart, scatter/histogram, slicers, map visual, KPI cards

##  Repo Contents

- `dashboard.pbix` — the Power BI report file
- `report.md/` — contains full report for the Dashboard
- `screenshots/` — exported images of each dashboard page

##  How to Use

1. Clone the repo and open `dashboard.pbix` in Power BI Desktop.
2. Use the **Contract Type** slicer (Page 1) and **Account Length** slider (Page 3) to filter the analysis.
3. Hover over visuals for tooltips with exact counts and percentages.

---
*Built to move churn analysis from "what happened" to "what to do about it."*
