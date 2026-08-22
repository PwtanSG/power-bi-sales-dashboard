# Power BI Sales Analytics Dashboard

## Overview

An interactive Power BI dashboard that analyses sales performance
by region, product category, salesperson, month and payment method.

## Business Questions

- Which region contributes the most sales?
- Which product category performs best?
- How do sales change over time?
- Which salesperson generates the most sales?
- Which payment method is used most frequently?

## ETL and Data Cleaning

Power Query was used to:

- Correct column data types
- Remove duplicate orders
- Impute missing Units using the median
- Replace missing Salesperson values with "Unknown"
- Standardise inconsistent region names
- Trim unnecessary spaces
- Calculate Sales Amount

## Sales Calculation

Sales Amount:

Units × Unit Price × (1 − Discount)

## DAX Measures

- Total Sales
- Total Orders
- Total Units
- Average Rating

## Dashboard Visuals

- KPI cards for key business metrics
- Monthly sales trend line chart
- Sales by category bar chart
- Regional share of sales pie chart
- Salesperson performance table
- Orders by payment method doughnut chart
- Category and region slicers

## Data Validation

- Reconciled dashboard totals with transformed source data
- Verified duplicate removal and missing-value treatments
- Tested slicers and interactions
- Tested report refresh after changing the Excel source

## Tools

Power BI Desktop, Power Query, DAX and Excel