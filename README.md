# Northwind SQL Business Analysis

A collection of 22 SQL business analysis queries written in PostgreSQL,
using the classic Northwind database. Each query is framed around a real
business scenario — the kind of ad-hoc and recurring analysis requests
a junior data analyst receives on the job.

---

## Skills Demonstrated

- Multi-table JOINs (INNER, LEFT, FULL)
- Aggregations and GROUP BY
- Conditional aggregation with CASE WHEN
- Window functions — RANK(), LAG(), SUM() OVER, AVG() OVER
- CTEs (Common Table Expressions)
- Subqueries and HAVING filters
- Date functions — EXTRACT, DATE_PART, TO_CHAR
- NULL handling — IS NULL, NULLIF, IS NOT NULL
- Cohort analysis and customer retention modelling
- Month-over-month growth calculations
- Running totals and cumulative metrics

---

## Database

- **Engine**: PostgreSQL 15+
- **Dataset**: Northwind sample database
- **Tables used**: customers, orders, order_details, products,
  categories, employees, shippers

---

## Project Structure

```
northwind-sql-business-analysis/
│
├── README.md
│
├── questions/
│   ├── 01_beginner.sql       6 foundational queries       (Q01–Q06)
│   ├── 02_intermediate.sql   8 business analysis queries  (Q07–Q14)
│   └── 03_advanced.sql       8 advanced analytical queries (Q15–Q22)
│
└── schema/
    └── northwind_setup.sql   Database setup file
```

---

## How to Run

1. Install PostgreSQL (version 15 or higher recommended)
2. Run `schema/northwind_setup.sql` to load the Northwind database
3. Open any `.sql` file in pgAdmin or run via `psql`
4. Execute queries individually — each is self-contained with comments

---

## Business Questions Answered

| # | Question | Level |
|---|----------|-------|
| 01 | List all customers from Germany | Beginner |
| 02 | Find products running low on stock | Beginner |
| 03 | Count total orders placed in 1997 | Beginner |
| 04 | Show the most expensive products | Beginner |
| 05 | Find all employees hired before 1993 | Beginner |
| 06 | Calculate average freight cost by ship country | Beginner |
| 07 | Calculate total revenue per product | Intermediate |
| 08 | Identify top 10 customers by total spend | Intermediate |
| 09 | Rank employees by total sales revenue | Intermediate |
| 10 | Find categories with above-average product prices | Intermediate |
| 11 | Calculate monthly revenue trend for 1997 | Intermediate |
| 12 | Find customers who have never placed an order | Intermediate |
| 13 | Delivery gap analysis — promised vs actual | Intermediate |
| 14 | Find orders that shipped late | Intermediate |
| 15 | Month-over-month revenue growth in 1997 | Advanced |
| 16 | Customer segmentation by order frequency | Advanced |
| 17 | Running total of revenue by month in 1997 | Advanced |
| 18 | Rank products within each category by revenue | Advanced |
| 19 | Cohort analysis — customer retention by first order year | Advanced |
| 20 | Employee performance vs team average | Advanced |
| 21 | Identify the best-selling product per country | Advanced |
| 22 | Find customers who increased spend year over year | Advanced |

---

## Author

**Ziku** — Aspiring Data Analyst  
Building toward a career in data analytics with a focus on SQL,
Python, and business intelligence tools.
