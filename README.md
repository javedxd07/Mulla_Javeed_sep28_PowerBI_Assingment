# Power BI Business Intelligence & Sales Analytics Project

## 📊 Project Overview

This project is a Business Intelligence and Sales Analytics solution developed using **Microsoft Power BI**.

The project focuses on preparing sales data, creating a Star Schema data model, developing DAX measures, and building interactive dashboards to analyze sales, products, customers, salespersons, geography, and budget performance.

## 🎯 Objectives

- Understand and prepare raw business data
- Clean and transform sales data
- Combine 2021, 2022, and 2023 sales data
- Build a Star Schema data model
- Create a Date table for time-based analysis
- Develop DAX measures and KPIs
- Analyze sales trends and business performance
- Compare budget with actual sales
- Build interactive Power BI dashboards

## 🗂️ Data Sources

The project uses the following data tables:

- 2021 Sales
- 2022 Sales
- 2023 Sales
- Products
- Locations
- Customers
- Sales People
- Budgeting
- Date Ranges

## 🏗️ Project Phases

### Phase 1 – Data Understanding & Data Preparation
- Inspected source tables
- Checked data types
- Checked blanks and errors
- Checked duplicate Order IDs
- Verified consistency of 2021, 2022 and 2023 sales tables
- Appended yearly sales data into `Fact_Sales`

### Phase 2 – Data Modeling
- Created a Star Schema
- Created fact and dimension tables
- Established relationships between `Fact_Sales` and dimension tables

### Phase 3 – Date Table
- Created `Dim_Date`
- Added Year, Quarter, Month, Month Name, Week, Day and Year-Month
- Sorted Month Name chronologically
- Connected Date table with sales data

### Phase 4 – DAX Measures
Created measures for:

- Total Sales
- Total Orders
- Total Quantity Sold
- Average Order Value
- Average Selling Price
- Total Cost
- Gross Profit
- Gross Margin %
- Revenue per Unit
- Profit per Unit
- Previous Year Sales
- YoY Sales Growth
- YoY Growth %
- MTD Sales
- YTD Sales
- Budget
- Actual
- Variance
- Achievement %

### Phase 5 – Executive Overview
Created an executive dashboard containing key business KPIs and sales performance visuals.

### Phase 6 – Sales Trend Analysis
Analyzes sales performance across years, quarters and months.

### Phase 7 – Product Performance
Analyzes product sales, quantity, cost, profit, margin and product contribution.

### Phase 8 – Customer Analysis
Analyzes customer sales, orders, quantity, AOV and contribution.

### Phase 9 – Salesperson Performance
Analyzes salesperson sales, profit, orders and performance.

### Phase 10 – Geographic Analysis
Analyzes sales and performance across states and locations.

### Phase 11 – Budget vs Actual
Compares budget with actual performance and analyzes variance and achievement.

### Phase 12 – Interactivity & Advanced Analytics
Includes interactive filtering, drill-down, drill-through, tooltips and advanced analytics.

## ⭐ Key Features

- Interactive Power BI dashboards
- Star Schema data model
- DAX-based KPIs
- Time intelligence
- Sales trend analysis
- Product analysis
- Customer analysis
- Salesperson analysis
- Geographic analysis
- Budget vs Actual analysis
- Interactive slicers and filters
- Drill-down and drill-through

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**

## 📁 Repository Structure

