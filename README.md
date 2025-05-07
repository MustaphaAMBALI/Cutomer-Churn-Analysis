# Customer Churn Analysis Dashboard

Transforming raw customer data into actionable retention insights using Excel and Power Query.

## Table of Contents
- [Project Objective](Project-Objective)
- [Data Source](Data-Source)
- [Tools and Features](Tools-and-Features)
- [Dashboard Overview](Dashboard-Overview)
- [Key Insights](Key-Insights)
- [Recommendations](Recommendations)
- [Repository Contents](Repository-Contents)

## Project Objective

To analyze customer churn patterns, uncover key drivers, and deliver actionable recommendations through an Excel dashboard that highlights business-critical insights.


## Data Source

[Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  



## Tools and Features

- **Excel**
  - Power Query (data cleaning, new columns from existing ones)
  - PivotTables, PivotCharts
  - Slicer for interactivity (Gender)
  - Conditional formatting
  - Calculated KPIs (e.g., Churn %, Average Monthly Charges)

## Dashboard Overview

- **KPIs**
  - Total Customers
  - Total Churned
  - % Churned
  - Average Monthly Charges

- **Charts**
  - Churn by Contract Type
  - Churn by Internet Service
  - Churn by Payment Method
  - Churn by Tenure Group
  - Average Monthly Charges by Churn Status

## Key Insights

- Electronic check users have the highest churn (1,017 customers), while credit card users have the lowest (232 customers).
- Month-to-month contracts show the highest churn (1,655 customers); two-year contracts have the lowest.
- Churn rate drops sharply with tenure increase — from 1,037 churned in the 0–12 month group to just 6 in the 49–69 month group.
- Churned customers pay slightly higher average monthly charges compared to retained customers.
- Fiber optic internet customers have higher churn rates compared to DSL or no internet service.
- Overall churn rate: 26.54% (1,869 churned out of 7,043 total customers).

## Recommendations

- Offer incentives for long-term contracts.
- Encourage stable payment methods (credit card, bank transfer) to reduce churn.
- Provide proactive support for fiber optic customers.
- Target retention strategies toward early-tenure customers.

## Repository Contents

- Cleaned dataset (`cleaned_customer_churn.xlsx`)
- Excel dashboard (`customer_churn_dashboard.xlsx`)
- Dashboard screenshots (`dashboard_screenshot.png`)
- Conditional formatting


