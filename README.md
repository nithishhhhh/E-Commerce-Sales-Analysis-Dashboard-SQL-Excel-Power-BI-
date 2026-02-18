# End-to-End E-Commerce Sales Analysis Dashboard (SQL + Excel + Power BI)

##  Project Overview

This is an end-to-end Data Analysis project where I analyzed E-commerce sales data using **MySQL, Excel, and Power BI** to generate business insights and build an interactive dashboard.

The project covers the complete data workflow:

* Data Cleaning in SQL
* KPI Analysis
* Data Export to Excel
* Interactive Dashboard in Power BI

---

##  Dashboard Preview

![Dashboard Preview]()

---

##  Business Objectives

* Analyze total revenue, profit, and orders
* Identify top-performing regions and categories
* Track monthly sales trends
* Understand customer payment behavior
* Build an interactive dashboard for decision-making

---

##  Tools & Technologies Used

* MySQL (Data Cleaning & Analysis)
* Microsoft Excel (Data Handling & Export)
* Power BI (Data Visualization & Dashboard)
* SQL (Joins, Aggregations, Group By, KPIs)

---

##  Dataset Information

* Domain: E-commerce Sales
* Records: 5000+ rows
* Fields: Orders, Sales, Profit, Category, Region, Payment Mode, Date, Product Details

---

##  Data Cleaning (SQL)

Performed data cleaning using SQL:

* Renamed columns for better readability
* Checked for null values
* Removed duplicates
* Validated data types
* Structured dataset for analysis

Example:

```sql
SELECT * FROM `order`;
SELECT COUNT(*) FROM `order`;
```

---

##  KPI Analysis (SQL Queries)

Key KPIs calculated:

* Total Revenue
* Total Profit
* Total Orders
* Regional Sales Performance
* Category-wise Revenue
* Monthly Sales Trend
* Payment Mode Analysis

Example KPI Query:

```sql
SELECT 
    SUM(Sales) AS total_revenue,
    SUM(Profit) AS total_profit,
    COUNT(order_id) AS total_orders
FROM `order`;
```

---

##  Dashboard Features (Power BI)

* KPI Cards (Revenue, Profit, Orders)
* Sales by Region (Bar Chart)
* Monthly Sales Trend (Line Chart)
* Revenue by Category (Bar Chart)
* Revenue by Payment Mode (Pie Chart)
* Interactive Filters (Region & Category Slicers)
* Dark Theme Professional Layout

---

##  Key Insights

* North region generated the highest total sales
* Home Decor and Furniture are top revenue categories
* Net Banking and COD contribute the highest revenue share
* Consistent monthly sales trend with peak seasonal spikes

---

##  Project Workflow

1. Data Collection (CSV Dataset)
2. Data Cleaning using MySQL
3. KPI & Business Analysis using SQL
4. Export Clean Data to Excel
5. Dashboard Development in Power BI
6. Interactive Visualization & Insights

---

##  Project Files

* SQL Queries (.sql)
* Cleaned Dataset (.csv / .xlsx)
* Power BI Dashboard (.pbix)
* Dashboard Preview Image
* README Documentation

---

##  Skills Demonstrated

* Data Cleaning
* SQL Analysis
* Data Visualization
* Business Intelligence
* Dashboard Design
* Data Storytelling
* End-to-End Data Analysis Workflow

---

##  Author

**Nithish**
Aspiring Data Analyst | SQL | Excel | Power BI

---

⭐ If you found this project useful, feel free to star the repository!
