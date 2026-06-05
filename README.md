# Exploratory Data Analysis - E-commerce Sales

This project contains an Exploratory Data Analysis of a 3-year e-commerce sales dataset from 2023 to 2025.

## Objective
Analyze sales performance across 7 products to identify trends, distribution patterns, and statistical outliers using the Interquartile Range method.

## Key Insights
- Revenue declined 58% from 2023 to 2025, indicating market or demand shift
- No statistical outliers detected using IQR method - all products fall within normal bounds
- Instagram drives the highest revenue at $275K compared to other channels  
- Order quantity is concentrated at lower values, showing most orders are small-ticket items

## Dashboard Features
1. **Revenue by Product** - Bar chart with IQR conditional formatting for outlier detection
2. **Outlier Status Table** - Shows Q1, Q3, IQR bounds and Normal/Outlier status per product
3. **Order Size Distribution** - Visualizes how many orders had 1, 2, 3+ items
4. **Revenue by Channel** - Identifies top performing marketing sources
5. **KPI Cards** - Total Revenue, Mean Quantity, Total Orders, Median Revenue
6. **Key Insights Box** - Executive summary of main findings

## Tools Used
- Power BI Desktop - Data modeling and visualization
- DAX - Calculated measures for IQR bounds and outlier flags
- Excel - Initial data cleaning

## Files in this Repo
- `EDA_Dashboard.pbix` - Power BI dashboard file
- `Screenshots/` - PNG exports of Page 1 and Page 2 dashboards
- `Report.pdf` - Written analysis and interpretation

## How to Use
1. Open `EDA_Dashboard.pbix` in Power BI Desktop
2. Use Year and Product slicers to filter the dashboard
3. Check the "Outliers Status" table to see IQR results

## Conclusion
The analysis shows a stable product portfolio with no extreme outliers. The revenue decline over time and channel performance differences provide actionable insights for business strategy.

---
Created by: TolulopeDorcas  
For: DECODELABS Data Analysis Project
