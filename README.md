# Chocolate Sales Analysis – SQL + Excel Dashboard Project

## Overview
This project analyzes chocolate sales data using **SQL for backend analysis** and **Excel for dashboarding**. The goal is to identify underperforming products, inefficient sales transactions, and profit optimization opportunities through data-driven insights.

---

##  Dataset
- **Total Transactions**: 3,791
- **Salespersons**: 25
- **Products**: 22
- **Categories**: 3
- **Time Period**: Year 2022

---

## Objectives
- Flag inefficient transactions (high expense-to-sales ratio)
- Identify underperforming products and salespersons
- Analyze monthly sales and profit trends
- Build a business-facing dashboard for insights and drill-downs

---

## Tools Used
- **SQL (PostgreSQL)**: Window functions, CASE statements, filtering, grouping
- **Microsoft Excel**: PivotTables, KPIs, slicers, interactive dashboard

---

## Key Insights
- 633 sales had expenses > 60% of revenue
- 8 products contributed below-average profit
- 1 salesperson flagged for consistently low profit per box
- 4 products had unusually high average expense per box
- Monthly profit fluctuations observed with underperformance in several months

---

## Project Structure
 chocolate-sales-analysis/
├──  Chocolate_Sales_Dashboard&Insights.xlsx   # Excel dashboard + SQL insight summaries +Data
├── Project_Report_Chocolate_Sales.docx       # Full project report with executive summary
├── query.sql                                 # All SQL queries used for backend insights
├── README.md                                 # Project overview, tools, insights, and dashboard description


---

##  Dashboard 
> Final Excel dashboard includes:
- KPI cards (Total Sales, Profit, Boxes)
- Line chart (Monthly profit trend)
- Bar charts (Top/Bottom products)
- Filters for Category, Product, Salesperson
- SQL Insights sheet (manual summaries of queries)

---

## Conclusion
This project demonstrates how SQL can extract deep operational insights while Excel provides an accessible reporting layer for business teams.



