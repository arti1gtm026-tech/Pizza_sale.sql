# 🍕 Pizza Sales Analysis Using SQL

## 📌 Project Overview

This project focuses on analyzing pizza sales data using **Microsoft SQL Server** to understand sales performance, revenue trends, and customer ordering patterns. The analysis helps identify top-performing pizza categories, popular pizza sizes, and daily and hourly order trends.

## 🎯 Project Objectives

- Calculate total revenue generated from pizza sales.
- Determine the average order value.
- Calculate the total number of pizzas sold.
- Identify the total number of orders placed.
- Analyze the average number of pizzas sold per order.
- Examine daily and hourly order trends.
- Calculate sales contributions by pizza category.
- Analyze sales distribution by pizza size.
- Identify the busiest days and ordering hours.

## 🧹 Data Validation & Quality Checks

Performed data quality checks to identify potential inconsistencies and improve dataset reliability.

- **Negative and Zero Values:** Checked price and quantity columns for invalid values.
- **Price Verification:** Verified total price calculations using quantity and unit price.
- **Text Validation:** Identified unwanted leading and trailing spaces in pizza names, categories, and sizes.
- **Unique Value Check:** Used `DISTINCT` to identify unique pizza sizes and categories.

## 📊 SQL Analysis Performed

The following business questions were explored using SQL queries:

### 1. Sales Performance Analysis

1. Write an SQL query to calculate the total revenue generated from all pizza sales.
2. Write an SQL query to find the average order value of all customer orders.
3. Write an SQL query to calculate the total number of pizzas sold.
4. Write an SQL query to determine the total number of orders placed.
5. Write an SQL query to calculate the average number of pizzas sold per order.

### 2. Daily & Hourly Order Trend Analysis

6. Write an SQL query to analyze the daily trend of total orders, showing the number of orders placed each day.
7. Write an SQL query to analyze the hourly trend of orders, showing the number of orders placed during each hour of the day.
8. Write an SQL query to identify daily order trends by date and determine the total number of orders placed on each date.
9. Write an SQL query to analyze daily order trends by day of the week and determine the total number of orders placed on each day.
10. Write an SQL query to analyze hourly order trends and determine the total number of orders placed during each hour of the day.

### 3. Sales Distribution Analysis

11. Write an SQL query to calculate the percentage contribution of sales by each pizza category.
12. Write an SQL query to calculate the percentage contribution of sales by each pizza size.

## 💻 SQL Concepts Applied

- `SELECT` and `DISTINCT`
- `WHERE` and `ORDER BY`
- `GROUP BY`
- Aggregate Functions (`SUM`, `COUNT`)
- `ROUND`, `LTRIM` and `RTRIM`
- Subqueries
- Data Validation
- Date and Time Functions (`DATENAME`, `DATEPART`)
- Percentage Calculations

## 🛠️ Technologies Used

- **Microsoft SQL Server** – Database management and query execution.
- **SQL (T-SQL)** – Data retrieval, aggregation, and analysis.
- **SQL Server Management Studio (SSMS)** – Writing and executing SQL queries.
- **GitHub** – Project documentation and version control.

## 📚 What I Learned

- Writing SQL queries for real-world sales analysis.
- Applying data validation techniques to improve data quality.
- Using aggregate functions to calculate business metrics.
- Analyzing sales trends using date and time functions.
- Calculating percentage contributions using subqueries.
- Extracting meaningful business insights from sales data.

## 📝 Conclusion

This project demonstrates the practical application of SQL in data validation and business analysis. By analyzing pizza sales transactions, the project provides insights into revenue performance, customer ordering behavior, and sales distribution across different pizza categories and sizes.

The analysis helps understand sales patterns and supports better business decisions related to sales strategy, inventory management, and demand planning.

---

**Project:** Pizza Sales Analysis Using SQL

**Domain:** Data Analytics

**Database:** Microsoft SQL Server

**Tools:** SQL | SSMS | GitHub

**Created by:** Arti Gautam
