📊 Project Overview

The Global Superstore Dashboard is an interactive Power BI project designed to analyze sales, profit, customers, products, and regional performance across multiple markets. The dashboard provides business insights through dynamic KPIs, trend analysis, geographical visualization, and customer segmentation.

🎯 Objectives
Monitor overall business performance.
Analyze sales and profit trends over time.
Identify top-performing products and customers.
Compare regional and market performance.
Track customer behavior and profitability.
Support data-driven business decisions.
📌 Dashboard Pages
1️⃣ Executive Overview

KPIs

Total Sales
Total Profit
Total Orders
Total Quantity Sold
Profit Margin %
Average Order Value

Visuals

Monthly Sales Trend
Monthly Profit Trend
Sales by Market
Sales by Region (Map)
Sales by Segment

Insights

Sales growth compared to previous year
Best-performing market
Highest revenue-generating segment
2️⃣ Product Analysis

KPIs

Total Sales
Total Profit
Total Orders
Total Quantity
Profit Margin %

Visuals

Top 10 Products by Sales
Top 10 Products by Profit
Sales by Sub-Category
Profit by Sub-Category

Business Insights

Best-selling products
Most profitable product categories
Low-margin product categories
3️⃣ Customer Analysis

KPIs

Total Customers
Total Sales
Average Sales per Customer
Total Profit
Average Profit per Customer

Visuals

Top Customers by Sales
Top Customers by Profit
Customers by Market
Sales by Segment
Customer Segment Trend Analysis

Business Insights

High-value customers
Customer contribution analysis
Segment-wise customer behavior
4️⃣ Regional Analysis

KPIs

Total Sales
Total Profit
Profit Margin %
Top Market
Top Country

Visuals

Sales by Country (Map)
Top Countries by Sales
Sales by Market
Profit by Market
Profit by Country

Business Insights

Best-performing countries
Regional profitability comparison
Market contribution analysis
🛠️ Tools & Technologies
Power BI Desktop
Power Query
DAX (Data Analysis Expressions)
Excel / CSV Dataset
📈 Key DAX Measures
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Total Orders = DISTINCTCOUNT(Orders[Order ID])

Total Quantity = SUM(Orders[Quantity])

Profit Margin % =
DIVIDE([Total Profit],[Total Sales],0)

Average Order Value =
DIVIDE([Total Sales],[Total Orders],0)

Total Customers =
DISTINCTCOUNT(Orders[Customer ID])

Average Sales Per Customer =
DIVIDE([Total Sales],[Total Customers],0)

Average Profit Per Customer =
DIVIDE([Total Profit],[Total Customers],0)
📊 Business Outcomes
Improved visibility of business performance.
Identified top-performing products and customers.
Tracked regional sales and profitability trends.
Enabled strategic decision-making through actionable insights.
🚀 Key Features

✅ Interactive Filters & Slicers
✅ Dynamic KPI Cards
✅ Drill-Down Analysis
✅ Geographic Mapping
✅ Trend Analysis
✅ Customer Segmentation
✅ Product Performance Tracking
✅ Responsive Dashboard Design

Dashboard Preview

The project consists of:

Executive Overview Dashboard
Product Analysis Dashboard
Customer Analysis Dashboard
Regional Analysis Dashboard

This dashboard demonstrates end-to-end Business Intelligence skills including Data Cleaning, Data Modeling, DAX, Data Visualization, and Business Insights Generation using Power BI.
