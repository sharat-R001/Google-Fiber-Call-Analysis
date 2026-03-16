# Google-Fiber-Call-Analysis
This project analyzes customer support data for Google Fiber to identify trends in repeat callers. By consolidating multi-market data using SQL and visualizing it in Tableau, the project reveals which problem types drive repeat volume and provides actionable insights to improve First Contact Resolution (FCR).
**Data Engineering & Business Intelligence Project**

## Project Overview
This project analyzes fictionalized customer support data for Google Fiber to identify trends in repeat callers. [cite_start]The objective is to provide stakeholders with insights into repeat caller volumes across different markets and problem types to improve operational optimization.

## Technical Workflow
1. **Requirement Gathering**: Identified stakeholders and established KPIs centered on "First Contact Resolution" to reduce call volume and increase customer satisfaction.
2. **Data Engineering (BigQuery)**:
    * Uploaded three raw CSV files (`market_1`, `market_2`, `market_3`) into Google BigQuery.
    * Executed a **SQL `UNION ALL` statement** to merge the tables into a single target table because the tables had matching columns.
3. **Data Visualization (Tableau)**:
    *Connected Tableau to the consolidated dataset and renamed raw fields for stakeholder clarity (e.g., `date_created` to **Call Date**).
   *Built an interactive dashboard tracking calls from the initial contact (**Day 0**) through seven days of repeat activity (**Day 1-7**).
4. **Executive Reporting**: Synthesized findings into a PowerPoint presentation to provide actionable recommendations to leadership.

## Key Business Insights
* **Peak Volume**: March saw the highest call volume in Q1 with **24,453** initial contacts.
* **Monday Surge**: Mondays are the busiest day for first contacts, accounting for **18.57%** of total weekly volume.
* **Primary Driver**: **Type 5 (Internet & WiFi)** is the leading cause of repeat calls across all markets, representing nearly **70%** of volume in Market 3.
