[![View Dashboard](https://img.shields.io/badge/Tableau-Dashboard-blue?logo=tableau)](https://public.tableau.com/app/profile/amani.mulira/viz/SalesDashboard_17588012430230/SalesDashboard#2)

# Tableau Sales and Customer Dashboard Project

## Overview
This project creates an interactive sales and customer dashboard in Tableau, designed to help sales managers, executives, marketing teams, and management analyze sales performance and customer behaviors. It consists of two interconnected dashboards: a Sales Dashboard and a Customer Dashboard. The dashboards are dynamic, allowing users to select any historical year for analysis, and include interactive charts with filters for products (category, subcategory) and locations (region, state, city).

This project is based on the YouTube tutorial "Tableau Complete Project End-to-End | Like I Do in My Real Projects" by Data with Baraa.

## Features
- **Dynamic Year Selection**: Analyze data for any selected year compared to the previous year.
- **Interactive Visualizations**: Charts and graphs allow filtering and navigation.
- **Navigation**: Easy switching between Sales and Customer dashboards.
- **Key Performance Indicators (KPIs)**: Display totals for sales, profits, quantity, customers, and orders.
- **Trend Analysis**: Monthly and weekly trends, with highlights for high/low performers.
- **Comparisons**: Year-over-year comparisons for various metrics.
- **Top Performers**: Rankings like top 10 customers by profit.

## Dashboards

### Sales Dashboard
Focuses on sales metrics and trends:
- **KPI Overview**: Total sales, profits, and quantity for the current and previous year.
- **Monthly KPIs**: Sales data for both years, identifying highest and lowest months.
- **Product Subcategory Comparison**: Sales and profit by subcategory for both years.
- **Weekly Trends**: Sales and profit for the current year, with averages and highlights for above/below average weeks.

### Customer Dashboard
Centers on customer data and behaviors:
- **KPI Overview**: Total customers, sales per customer, and orders for the current and previous year.
- **Monthly KPIs**: Customer-related data for both years, identifying highest and lowest months.
- **Customer Distribution**: Based on number of orders to analyze loyalty and engagement.
- **Top 10 Customers**: Ranked by profit, including orders, sales, profit, and last order date.

## Data Requirements
- The data is provided in a ZIP file containing CSV files (e.g., sales data with columns for dates, products, locations, sales, profits, etc.).
- Download the appropriate ZIP based on your location: EU (comma as decimal separator) or Non-EU (dot as decimal separator).
- Data source: Typically a sample sales dataset (e.g., similar to Superstore dataset, but customized for this project).
- Ensure Tableau can connect to the CSV files without issues; if problems occur, check decimal formats.
