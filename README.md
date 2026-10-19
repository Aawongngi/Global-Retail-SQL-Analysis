# Global-Retail-SQL-Analysis
This is a  global retail sales analysis project using MySQL to investigate sales trends, product profitability, customer behavior, and regional performance, generating insights to support data-driven business decisions.

## Project Overview

This project analyzes a global retail sales dataset to understand business performance across products, customers, regions, and sales channels.

Using MySQL, the project explores real-world business questions related to revenue, profitability, customer behavior, discounts, returns, and customer satisfaction. The goal is to transform raw sales data into meaningful insights that can support better business decisions.

## Business Objectives

- Analyze sales trends across years, quarters, and months.
- Identify the most profitable products and product categories.
- Evaluate the relationship between discounts, revenue, and profit.
- Understand customer purchasing behavior and segment performance.
- Compare revenue and profitability across regions and sales channels.
- Investigate product returns and customer satisfaction.
- Assess data quality, including missing values, duplicates, and data integrity.
- Develop data-driven recommendations for management.

## Tools & Technologies

- **MySQL** — querying and analyzing relational data.
- **MySQL Workbench** — database management and query execution.
- **SQL** — data aggregation, joins, subqueries, date functions, and analytical queries.

## Dataset

The project uses a retail dataset organized into four relational tables:

| Table | Description |
|---|---|
| `sales` | Order transactions, quantities, revenue, costs, profits, discounts, and returns |
| `products` | Product names, categories, prices, and costs |
| `customers` | Customer identifiers, segments, signup dates, and contact fields |
| `regions` | Countries and regional information |

The tables are connected through identifiers such as `product_id`, `customer_id`, and `region_id`.

## Business Questions

This project investigates 18 real-world business questions across 10 analytical areas.

### Sales Performance
1. What is total sales revenue by year, quarter, and month?
2. Which months have the highest and lowest sales?
3. How many orders were placed in each year?

### Profitability
4. What is total profit and profit margin by product category?
5. Which products generate the highest total profit?
6. Which products have negative profit, and how often does this happen?

### Discounts
7. How do average discounts relate to sales and profit?

### Products
8. Which product categories generate the most revenue?
9. What are the top 10 products by quantity sold?
10. What is each category's percentage contribution to total revenue?

### Geography
11. Which countries and regions contribute the most revenue?

### Channels
12. Which sales channel generates the highest revenue and profit?

### Customers
13. Which customer segments contribute the most revenue?
14. Who are the top 20 customers by lifetime sales?

### Payments
15. Which payment methods are used most often and generate the most revenue?

### Returns
16. What percentage of orders are returned?
17. Which products have the highest return rates?

### Customer Experience
18. What is the average customer satisfaction by channel and category?


## SQL Skills Demonstrated

The project applies mainly the below SQL techniques to answer the business questions:

- Data aggregation using `SUM()`, `AVG()`, and `COUNT()`
- Filtering and sorting with `WHERE` and `ORDER BY`
- Grouping data using `GROUP BY`
- Joining relational tables using `INNER JOIN`
- Conditional calculations using `CASE`
- Subqueries and percentage calculations
- Date functions for yearly, quarterly, and monthly analysis
- Profitability and return-rate calculations

## Key Findings

to come later ??????????????????????????

## Business Recommendations

later ??????????????




