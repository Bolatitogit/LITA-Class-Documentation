# LITA-Class-Documentation

### Data Analysis
### Excel for Data Analysis
Excel is widely used for data manipulation, analysis, and visualization. It’s a powerful tool for small to medium-sized datasets, especially when interactive features or quick calculations are needed.
### Key Features and Functions of Excel:
Data Input and Organization: Excel allows you to store data in cells, organized in rows and columns, which can easily be filtered and sorted.
Formulas and Functions:
* Basic Functions: SUM(), AVERAGE(), COUNT(), MAX(), MIN().
* Statistical Functions: STDEV(), VAR(), MEDIAN(), MODE().
* Conditional Functions: IF(), COUNTIF(), SUMIF().
* Lookup Functions: VLOOKUP(), HLOOKUP(), INDEX(), MATCH().
* Text Functions: CONCATENATE(), LEFT(), RIGHT(), LEN().
* Date Functions: TODAY(), NOW(), DATEDIF(), EDATE().
* Pivot Tables: Useful for summarizing large datasets by grouping, sorting, and aggregating data to find trends and patterns.
* Data Visualization: Excel offers a range of chart types such as bar charts, line charts, scatter plots, pie charts, and histograms to visually interpret data.
* Conditional Formatting: Highlights data based on specific criteria (e.g., color scales, data bars, icon sets) to make trends and outliers easily identifiable.
* Data Cleaning: Functions like TRIM(), CLEAN(), SUBSTITUTE(), and TEXT TO COLUMNS are used for cleaning and standardizing data.
* What-If Analysis: Tools like Goal Seek and Data Tables to analyze different scenarios.
* Solver Tool: Helps in optimization problems by adjusting variables to achieve desired outcomes under specified constraints.
Check out an excel example [Click here] (https://docs.google.com/spreadsheets/d/1ZDSUlqoUJjr5vxU8-Kl48qCwjlHSgmKZ/edit?gid=1961855967#gid=1961855967)

 ### SQL (Structured Query Language) for Data Analysis:
SQL is the standard language for managing and querying relational databases. It’s ideal for handling large datasets and performing complex operations with high efficiency.
Key Features of SQL:
* Data Retrieval (Queries): SQL allows you to retrieve specific data from a database using the SELECT statement. You can filter, sort, group, and join data from multiple tables.
* Basic Query: SELECT column_name FROM table_name;
* Filtering: WHERE clause, e.g., SELECT * FROM Employees WHERE age > 30;
* Sorting: ORDER BY, e.g., ORDER BY age DESC;
* Grouping: GROUP BY, e.g., GROUP BY department;
* Aggregation: Functions like COUNT(), SUM(), AVG(), MAX(), MIN().
* Joins: Combines data from multiple tables using inner, left, right, and full joins, e.g., SELECT * FROM Employees JOIN Departments ON Employees.dept_id = Departments.dept_id;.
* Data Manipulation: SQL is used to add, update, or delete data.
* Insert Data: INSERT INTO table_name (columns) VALUES (values);
* Update Data: UPDATE table_name SET column_name = value WHERE condition;
* Delete Data: DELETE FROM table_name WHERE condition;
* Data Filtering: SQL’s WHERE clause allows for advanced filtering, including using logical operators (AND, OR, NOT) and comparison operators (=, >, <).
* Data Grouping & Aggregation:
* Aggregation functions like COUNT(), SUM(), AVG(), and GROUP BY to summarize data.
Example: SELECT department, COUNT(*) FROM Employees GROUP BY department;
* Advanced Queries:
* Subqueries (nested queries): SELECT name FROM Employees WHERE salary > (SELECT AVG(salary) FROM Employees);
* Common Table Expressions (CTEs): WITH cte_name AS (SELECT ... ) SELECT * FROM cte_name;
* Window Functions: Used for ranking, cumulative totals, moving averages, etc.
* Data Integrity: SQL databases enforce constraints like primary keys, foreign keys, and unique constraints to ensure the accuracy of data.
* Views: SQL allows the creation of virtual tables (VIEWS) to simplify complex queries or restrict data access.
Example: CREATE VIEW HighSalaryEmployees AS SELECT * FROM Employees WHERE salary > 50000;
Stored Procedures & Functions: These allow you to write reusable SQL code blocks for tasks like data processing.


