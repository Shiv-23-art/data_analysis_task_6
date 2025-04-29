# data_analysis_task_6

# Online Sales Analysis – SQL + Python

This project is part of my Data Analyst internship task, where I performed time-based sales trend analysis using both SQL and Python.

## Files Included

- `online_sales_analysis.sql`: Full SQL script including:
  - Database creation
  - Table definition
  - Sample data (`INSERT INTO`)

- `online_sales_analysis_visuals.ipynb`: Jupyter Notebook to visualize monthly revenue trends from MySQL using Python.

## Objective

- Analyze monthly revenue and order volume using SQL aggregations
- Visualize revenue trends and 3-month rolling average using Python

## SQL Highlights

  - GROUP BY` with `DATE_FORMAT()` and `EXTRACT()` for time-based aggregation
  - `SUM()` for total revenue, `COUNT(DISTINCT transaction_id)` for order volume
  - **Cumulative revenue tracking using `SUM() OVER ()` for progressive trend analysis**
  - Queries identifying:  
   - Monthly performance  
   - Yearly trends  
   - Top 3 performing months 

## Python Visuals

- Connected to MySQL using `mysql.connector`
- Created line charts with:
  - Monthly Revenue
  - 3-Month Rolling Average

## Output Preview

Screenshots of:
- SQL query results
- Python charts
- **Excel file containing structured results for deeper analysis** 

## What I Learned

- Writing SQL aggregations and formatting dates for analysis
- Connecting Python to a live database
- Visualizing time-series trends with moving averages

- ## Took help of w3schools website and youtube to learn advanced analysis, got into error once, but i tried to debug it and do it again. Also tried to make some visuals for better analysis.
