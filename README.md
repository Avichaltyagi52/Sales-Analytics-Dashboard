# 🧾 Interactive Sales Analysis Dashboard (Power BI)

## 📊 Project Overview
This Power BI project presents an **Interactive Sales Analysis Dashboard** designed to help businesses monitor and analyze key sales performance metrics.  
The dashboard provides **real-time insights into revenue, profit, regional performance, product categories, and customer segments**, enabling data-driven decisions to boost sales growth and efficiency.

---

## 🎯 Objectives
- Track overall **sales performance** and identify trends.  
- Analyze **regional and product-level sales**.  
- Compare **profit margins and revenue growth** across time periods.  
- Identify **top-performing products, regions, and sales representatives**.  
- Enable interactive exploration through filters and slicers.

---

## 🧩 Tools & Technologies Used
- **Power BI Desktop** – Data visualization and reporting  
- **Power Query** – Data transformation and cleaning  
- **DAX (Data Analysis Expressions)** – KPI and metric calculations  
- **Excel / CSV Dataset** – Data source for the dashboard  

---

## 🧮 Key Metrics & DAX Measures
Some of the main measures created for this dashboard include:
- `Total Sales = SUM(Sales[Sales Amount])`
- `Total Profit = SUM(Sales[Profit])`
- `Profit Margin = DIVIDE([Total Profit], [Total Sales])`
- `Sales YoY Growth = ([Current Year Sales] - [Previous Year Sales]) / [Previous Year Sales]`
- `Average Order Value = DIVIDE([Total Sales], [Order Count])`

---

## 📈 Dashboard Features
- **Dynamic Filters** for Region, Product Category, and Time Period  
- **KPIs and Cards** showing Total Sales, Profit, and Margin %  
- **Interactive Charts** (Bar, Line, Donut, and Map visuals)  
- **Trend Analysis** with Year-over-Year comparisons  
- **Top & Bottom Products** by Revenue and Profit  
- **Drill-through Reports** for deeper analysis  

---

## 🧠 Insights Derived
- Sales are highest in the **North Region** with strong profit margins.  
- **Category A products** contribute to most of the total revenue.  
- **Q4** shows a significant increase in profit compared to Q1, indicating seasonal trends.  
- **Few low-performing SKUs** significantly impact total profit — need optimization.  

---
