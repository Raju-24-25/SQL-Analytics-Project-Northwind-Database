# SQL Analytics Project – Northwind Database

## Project Overview

This project presents a comprehensive business analytics solution built using the Northwind Database. The objective was to answer real-world business questions through SQL analysis and transform transactional data into actionable insights.

The project covers revenue analysis, product performance, customer segmentation, employee productivity, inventory health, and regional business performance using advanced SQL techniques.

---

## Business Problem

Organizations generate large volumes of transactional data but often struggle to convert it into strategic decisions.

This project demonstrates how SQL can be used to:

* Identify top-performing products
* Analyze revenue trends
* Evaluate employee performance
* Monitor inventory risk
* Segment customers by lifetime value
* Support business decision-making

---

## Dataset

### Database

Northwind Database

### Domain

Retail & Wholesale Distribution

### Core Tables

* Customers
* Orders
* Order Details
* Products
* Categories
* Employees
* Suppliers
* Inventory

---

## Project Objectives

### Revenue Analysis

Determine which products generate the highest revenue.

### Trend Analysis

Analyze monthly revenue growth and seasonality patterns.

### Employee Performance

Identify top-performing employees and regions.

### Inventory Analysis

Detect stock risks and inventory shortages.

### Customer Segmentation

Group customers based on lifetime value.

---

## SQL Concepts Applied

### Joins

* INNER JOIN
* LEFT JOIN

### Aggregations

* SUM()
* COUNT()
* AVG()
* GROUP BY
* HAVING

### Window Functions

* RANK()
* DENSE_RANK()
* NTILE()

### Common Table Expressions (CTEs)

Used for:

* Customer segmentation
* Revenue ranking
* Performance analysis

### CASE Statements

Used for inventory classification and business rules.

---

## Business Questions Answered

### BQ1 — Which Products Drive the Most Revenue?

Identified the Top 10 products contributing the highest revenue.

Key Finding:

* Revenue is highly concentrated among a small number of products.
* Seafood, Beverages, and Meat/Poultry categories dominate sales.

---

### BQ2 — How Has Monthly Revenue Changed Over Time?

Analyzed monthly revenue across a three-year period.

Key Finding:

* Revenue demonstrates consistent growth.
* Strong Q4 seasonal patterns observed each year.

---

### BQ3 — Who Are the Top Performing Employees?

Ranked employees based on generated revenue.

Key Finding:

* Top performers contribute approximately 8.8% each of total revenue.
* Revenue contribution is evenly distributed across teams.

---

### BQ4 — What Is the Inventory Health Status?

Products were classified into stock risk categories.

Key Finding:

* 15 products are currently in Critical or Out-of-Stock status.
* Potential revenue loss risk identified.

---

### BQ5 — Which Customer Segments Generate the Most Value?

Customers were segmented using NTILE(4).

Key Finding:

* Platinum customers generate nearly half of total revenue.
* Small Business customers have the highest average order value.

---

## Key Business Insights

### Revenue Concentration

A limited number of products drive a significant share of total sales.

### Seasonality

Q4 consistently outperforms other quarters by a substantial margin.

### Regional Performance

Revenue distribution is balanced across regions, reducing geographic risk.

### Customer Value

High-value customer segments contribute disproportionately to revenue.

### Inventory Risk

Automated reorder triggers could significantly reduce stockouts.

---

## Technologies Used

* SQL
* SQLite
* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Visualizations

* Top Products by Revenue
* Category Revenue Share
* Monthly Revenue Trend
* Employee Revenue Ranking
* Revenue by Region
* Inventory Health Dashboard
* Customer Lifetime Value Segmentation

---

## Skills Demonstrated

* SQL Query Optimization
* Business Intelligence
* Customer Analytics
* Revenue Analysis
* Data Storytelling
* Data Visualization
* Window Functions
* Common Table Expressions (CTEs)

---

## Project Workflow

1. Database Exploration
2. Business Question Definition
3. SQL Query Development
4. Data Extraction
5. Aggregation & Analysis
6. Visualization
7. Business Insight Generation
8. Reporting

---

## Results

The project successfully transformed transactional data into business intelligence insights that support revenue optimization, customer retention strategies, inventory planning, and operational decision-making.

---

## Author

Raju Mondal

Aspiring Data Analyst | Data Science & AI Enthusiast

LinkedIn: https://www.linkedin.com/in/raju-mondal-24-25-ds/

GitHub: https://github.com//Raju-24-25
