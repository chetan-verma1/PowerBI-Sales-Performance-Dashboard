# Power BI Sales Performance Dashboard

## Project Overview
This project is an interactive Sales Performance Dashboard created using Power BI.  
It analyzes sales, orders, customers, product categories, customer segments, regional performance, and monthly sales trends using Superstore sales data.

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Data Visualization
- CSV Dataset

## Dashboard Pages
1. Executive Summary
2. Customer Analysis
3. Product Analysis

## Key Features
- Total Sales, Total Orders, and Total Customers KPI cards
- Monthly Sales Trend analysis
- Sales by Region and Category
- Sales by State
- Top 10 Customers by Sales
- Sales by Segment
- Sales by Sub-Category
- Top 10 Products by Sales
- Interactive slicers for Region, Category, Segment, and Sub-Category

## DAX Measures Used
```DAX
Total Sales = SUM(train[Sales])

Total Orders = DISTINCTCOUNT(train[Order ID])

Total Customers = DISTINCTCOUNT(train[Customer ID])

Total Products = DISTINCTCOUNT(train[Product ID])

Average Sales per Order = DIVIDE([Total Sales], [Total Orders])

## Dataset

The dataset used in this project was downloaded from Kaggle and used for educational/portfolio purposes only.

The raw dataset is not included in this repository due to dataset licensing considerations.

```Dataset Source: Kaggle - Superstore Sales Dataset

Note: The years in the dataset were modified for practice and dashboard demonstration purposes.

## Business Insights
Identified top-performing regions and states based on sales.
Analyzed customer segments contributing the highest revenue.
Found best-selling product categories, sub-categories, and products.
Created monthly sales trend analysis to understand sales performance over time.

## Project Outcome

This dashboard helps business users monitor sales performance, understand customer behavior, and identify high-performing products and regions.

---

## Author

Created by **Chetan Verma**

If you found this project useful, feel free to ⭐ this repository.

---

<p align="center">
  <b>Made with ❤️ </b>
</p>

