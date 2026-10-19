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

The analysis investigates questions across five main areas:

### 1. Sales Performance
- How does revenue change over time?
- Which months generate the highest and lowest sales?
- How does revenue change month over month?

### 2. Product Performance & Profitability
- Which products and categories generate the most revenue and profit?
- Which products experience negative profits?
- How do discounts relate to sales and profitability?
- Which products have the highest return rates?

### 3. Customer Analysis
- Which customer segments contribute the most revenue?
- Who are the highest-value customers?
- How does customer satisfaction vary across sales channels and product categories?

### 4. Regional & Sales Channel Analysis
- Which countries and regions contribute the most revenue?
- Which sales channels generate the highest revenue and profit?
- Which payment methods are most commonly used?

### 5. Data Quality & Advanced Analysis
- Are there missing values, duplicate order IDs, or orphaned foreign keys?
- How can products be ranked by profit within their categories?
- What does cumulative revenue reveal about overall sales performance?

## SQL Skills Demonstrated

The project applies SQL techniques to answer practical business questions, including:

- `SELECT`, `WHERE`, and `ORDER BY`
- Aggregate functions such as `SUM()`, `AVG()`, and `COUNT()`
- `GROUP BY` and `HAVING`
- `INNER JOIN` and relational data analysis
- `CASE` expressions and conditional aggregation
- Subqueries and `NULLIF()`
- Date functions for time-based analysis
- Percentage calculations and profitability metrics
- Window functions for ranking, running totals, and month-over-month analysis
- Data quality checks and integrity validation

## Key Findings

to come later ??????????????????????????

## Business Recommendations

later ??????????????




