# Task-3: Use SQL queries to extract and analyze data from a database.
# SQL Analysis on American Community Survey 1-Year Data (2015)
## Objective
To explore, analyze, and manipulate demographic and economic data using SQL on the **American Community Survey 1-Year Data for 2015**, focusing on U.S. states, places, and congressional districts.

## Tools Used
- **Database Engine**: SQLite  
- **Dataset**: U.S. Census Bureau's 2015 ACS 1-Year estimates (demographic, income, and population data)

## Operations Performed

### 1. Schema Review
Inspected structure of tables: `states`, `places`, and `congressional_districts`.

### 2. Basic SQL Queries
Used `SELECT`, `WHERE`, `ORDER BY`, and `GROUP BY` to retrieve and sort data.

### 3. Joins
Implemented `INNER JOIN`, `LEFT JOIN`, and simulated `RIGHT JOIN` to combine information across tables.

### 4. Subqueries
Used nested queries to perform comparisons and extract insights (e.g., states above national income average).

### 5. Aggregate Functions
Applied `SUM`, `AVG` to calculate total population, average income, and more.

### 6. Views for Analysis
Created SQL views like `state_population_income` and `district_poverty_analysis` for simplified future querying.

### 7. Query Optimization
Utilized indexes (`CREATE INDEX`) to improve performance on frequent query fields like `state`, `name`, and composite keys.

## Outcome
Efficient SQL-based approach to extract meaningful insights from demographic data, with reusable views and optimized queries.
