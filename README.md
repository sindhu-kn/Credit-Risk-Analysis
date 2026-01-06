Project Overview

This project simulates a real-world credit risk monitoring system used by banks and NBFCs to assess portfolio health, identify high-risk segments, and analyze loan exposure and default behavior.

The objective is to demonstrate how SQL-based data preparation and Power BI analytics can be combined to generate actionable business insights for credit and risk decision-making.

Business Objective

1. Monitor overall loan portfolio exposure
2. Identify high-value customers and high-risk loans
3. Analyze default trends across demographics and credit scores
4. Detect risk concentration across regions and products
5. Support data-driven credit policy decisions

Dataset Description

The analysis is based on structured relational data representing a banking environment:
1. Customers – demographic details
2. Loans – loan amount, status, defaults
3. Products – loan types

Tech Stack & Skills Used

🔹 SQL
1. Joins (customer–loan–product integration)
2. CTEs for layered and reusable risk calculations
3. Subqueries for exposure and default segmentation
4. Aggregations for portfolio-level KPIs
5. Structured queries to support BI-ready datasets

🔹 Power BI
1. Data Modeling (Fact–Dimension schema)
2. DAX Measures for:
       Default Rate
       Loan Exposure
       Risk Ratios
3. Interactive Dashboards
4. KPI cards, slicers, filters, and drill-throughs


Key Metrics Tracked
1. Total Loan Exposure
2. Default Rate (%)
3. Risk Category Distribution
4. Region-wise Default Trends
5. High-Risk Loan Identification
6. High-Value Customer Identification

Business Insights Generated
1. High-risk loans contribute a disproportionate share of total exposure, indicating concentration risk
2. Lower credit score bands show consistently higher default rates
3. Younger age groups exhibit higher default behavior compared to older segments
4. Certain regions show elevated default rates despite moderate exposure
5. Product-level analysis highlights areas requiring tighter credit controls

Dashboard Features
1. Portfolio overview with key KPIs
2. Risk segmentation by credit score, age group, and region
3. Product-wise exposure visualization
4. High-risk customer drill-down view
5. Interactive filters for dynamic analysis

Key Learnings

Translating business risk questions into SQL logic

Designing scalable data models for BI tools

Using DAX to convert raw data into decision-ready metrics

Applying analytics to real-world banking and risk use cases


