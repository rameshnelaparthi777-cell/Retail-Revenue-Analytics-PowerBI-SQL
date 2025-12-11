# Retail-Revenue-Analytics-PowerBI-SQL
This project analyses sales performance, customer behaviour, product pricing impact, and revenue forecasts for a retail business.
The objective is to understand overall performance and support data-driven decisions across revenue, customers, and product strategy.

 ## Project Overview

The analysis was carried out using Power BI for dashboarding and MySQL for data exploration.
The dataset includes sales transactions, pricing changes, product details, customer information, and monthly revenue forecasts.

The project is organised into three dashboards, each focusing on a specific business area:

### Executive Summary

### Forecast & Pricing Analysis

### Customer Analytics

Together, these dashboards provide a complete view of revenue performance, profitability, customer segments, and pricing impact.

## Key Insights
### 1. Executive Summary

 Total Revenue: $408M

 Total Profit: $217M

 Profit Margin: 53%

 Total Quantity Sold: 150K units

 Top Categories: Electronics, Sports, Fashion

### 2. Forecast & Pricing Analysis

 Actual revenue remained stable but slightly below forecast values.

 Price changes resulted in a negative impact of ~4M.

Several products experienced a drop in revenue after price revisions.

### 3. Customer Analytics

 High-value customers contributed a major share of revenue.

 Loyal and high-value segments performed consistently across categories.

 Chennai and Mumbai emerged as the top-revenue regions.

# Dataset & Data Model

The project follows a Star Schema, with Sales acting as the central fact table.

###### Fact Table

##### Sales

##### Dimension Tables

##### Customers

##### Products

##### Pricing_Changes

##### Forecasts

###### DimDate

# Star Schema (Data Model)

![Star Schema](data_model/star_schema.png)

# Tools Used

### Power BI – Data modelling & dashboard development

### SQL (MySQL) – Exploratory data analysis

### Excel – Initial data checks & cleaning

### DAX – Measures and calculations

### Power Query – Data transformations

# SQL Analysis Included

SQL was used to calculate:

Total Revenue & Total Profit

Profit Margin

Category & Segment performance

Price change impact

Customer lifetime value

Region-wise revenue

Top-selling products

Your SQL file will be included in:

 sql/retail_sales_analysis.sql

# Power BI Dashboards

Screenshots of the three dashboards are included in the dashboards/ folder:

Executive Summary

Forecast & Pricing

Customer Analytics

# Advanced Power BI Features Used

Bookmarks to switch between Monthly / Quarterly / Yearly views

Buttons for interactive navigation

Trend lines to show revenue direction


# Project Highlights

Demonstrates strong understanding of ETL, DAX, and Data Modelling.

Shows ability to build a clean, business-focused dashboard.

Covers end-to-end analytics workflow from SQL to insights.

Uses KPIs and visuals aligned with real-world business reporting.
