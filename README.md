# Task 6: Sales Trend Analysis Using Aggregations

## Objective
Analyze monthly revenue and order volume from the online_sales dataset using SQL aggregations.

## Tools
- PostgreSQL / MySQL / SQLite

## Queries Performed
1. Monthly revenue & order volume
2. Top 3 months by revenue
3. Yearly revenue summary

## Key SQL Concepts Used
- Aggregate functions: SUM(), COUNT(DISTINCT)
- Date extraction: EXTRACT(YEAR/MONTH FROM order_date)
- GROUP BY & ORDER BY for sorting
- Limiting results with LIMIT
- Handling NULLs (default aggregation ignores NULL)

## Observations (Example)
- Revenue peaks in certain months (seasonal trends)
- Order volume correlates with revenue trends
- Top 3 revenue months: e.g., December, November, March

## Learning Outcome
- Learned to group data by month/year
- Analyzed time trends using SQL
- Practiced aggregations and top-N analysis
