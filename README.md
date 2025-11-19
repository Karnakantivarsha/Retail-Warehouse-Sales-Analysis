📊 Retail & Warehouse Sales Analysis | Python + Power BI

This project analyzes retail and warehouse sales performance for the year 2020 using Python for data cleaning and Power BI for data visualization.
The goal is to understand sales trends, category performance, supplier contribution, and forecast future sales.

🚀 Project Overview

This project performs:

Data cleaning and preprocessing

Creation of calculated metrics such as TotalSales, Profit

Monthly trend analysis

Category & supplier performance evaluation

Retail vs Warehouse comparison

Top 10 product analysis

6-month sales forecasting in Power BI

Creation of an interactive dashboard

🧰 Tools & Technologies Used
Tool / Technology	Purpose
Python (Pandas, NumPy, Matplotlib, Seaborn)	Data cleaning & analysis
Power BI Desktop	Dashboard and visualizations
Power Query	Data modeling & ETL
Excel	Basic data review
GitHub	Version control & hosting
📂 Project Structure
Retail-Warehouse-Sales-Analysis/
│
├── data/
│   ├── clean_warehouse_retail.csv
│   ├── monthly_trend.csv
│
├── notebooks/
│   ├── sales_analysis.ipynb
│
├── powerbi/
│   ├── Sales_Dashboard.pbix
│
├── reports/
│   ├── Final_Report.pdf
│
├── images/
│   ├── dashboard.png
│   ├── charts_preview.png
│
└── README.md

🧹 Data Cleaning & Preparation (Python)

Steps performed:

Removed duplicates

Standardized column names

Handled missing values

Converted datatypes

Created MonthYear field

Engineered metrics (TotalSales, Profit)

Generated monthly summary table

Exported cleaned data for Power BI

🔧 Feature Engineering

Created new columns:

New Column	Description
TotalSales	RetailSale + WarehouseSales
Profit	Estimated 20% profit on RetailSale
MonthYear	Combined Year & Month
SalesCategory	High / Medium / Low performance
📈 Power BI Dashboard Visuals
Dashboard Includes:
📌 1. KPI Cards

Total Sales

Total Profit

Retail Transactions

Average Monthly Sales

📌 2. Trend Analysis

Monthly Sales Trend

6-Month Sales Forecast

📌 3. Performance Charts

Sales by Category

Top 10 Best Selling Items

Retail vs Warehouse Sales

Supplier Contribution (Donut Chart)

📌 4. Filters (Slicers)

MonthYear

Supplier

ItemType

📊 Data Modeling
🔗 Relationship Created:
clean_warehouse_retail[MonthYear] 
          ---> 
monthly_trend[MonthYear]

📘 How to Run the Project
🔹 Run Python Notebook

Open:

notebooks/sales_analysis.ipynb

🔹 Open Power BI Dashboard

Download and open:

powerbi/Sales_Dashboard.pbix

🙋‍♀️ Author

Karnakanti Varsha
Data Analyst | Python | Power BI | SQL
📧 karnakantivarsha@gmail.com


Type: Many-to-One

Direction: Single
