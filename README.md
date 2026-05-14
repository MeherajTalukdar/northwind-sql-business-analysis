# northwind-sql-business-analysis
A complete business analysis on northwind database.

# Northwind SQL Business Analysis

A collection of 22 SQL business analysis queries written in PostgreSQL,
using the classic Northwind database. Covers real-world analytical
scenarios across revenue, customers, products, and employee performance.

## Skills Demonstrated
- Multi-table JOINs
- Aggregations and GROUP BY
- Window functions (RANK, LAG, SUM OVER)
- CTEs (Common Table Expressions)
- Conditional aggregation
- Cohort analysis
- Month-over-month growth calculations

## Database
PostgreSQL 15 | Northwind sample database

## Project Structure
| File | Description |
|------|-------------|
| questions/01_beginner.sql | 6 foundational queries |
| questions/02_intermediate.sql | 8 business analysis queries |
| questions/03_advanced.sql | 8 advanced analytical queries |

## How to Run
1. Install PostgreSQL
2. Run schema/northwind_setup.sql to load the database
3. Open any .sql file and run in pgAdmin or psql

## Key Business Questions Answered
- Which customers grew their spend year over year?
- What is the month-over-month revenue trend?
- Which products rank highest within each category?
- Which employees are performing above team average?
