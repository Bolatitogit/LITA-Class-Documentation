# LITA-Class-Documentation

### Data Analysis
----
[Excel for Data Analysis](#excel-for-data-analysis)

[Key Features and Functions of Excel](#key-features-and-functions-of-excel)

[SQL Structured Query Language for Data Analysis](sql-structured-query-language-for-data-analysis)

[Power BI for Data Analysis](#power-bi-for-data-analysis)

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
* Filtering: WHERE clause, e.g., SELECT  * FROM Employees WHERE age > 30;
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
Example:
```SQL
CREATE VIEW HighSalaryEmployees AS SELECT * FROM Employees
WHERE salary > 50000;
```
### Power BI for Data Analysis
Power BI is a powerful business analytics tool developed by Microsoft, designed to provide interactive visualizations and business intelligence capabilities with a simple interface for creating reports and dashboards. It allows users to connect, model, and visualize data, making it useful for data analysis and insights.
Key Concepts in Power BI for Data Analysis
1 Data Sources and Connections:

* Power BI supports a wide range of data sources, including SQL databases, Excel, cloud services like Azure and Google Analytics, APIs, and even real-time data streams.
* Use the Get Data button to connect to various data sources.
* Power BI allows you to combine multiple data sources for analysis using Power Query.
2 Data Transformation with Power Query:

* Power Query is an ETL (Extract, Transform, Load) tool in Power BI for cleaning and transforming raw data before analysis.
* You can perform tasks such as filtering, merging datasets, removing duplicates, unpivoting, and creating calculated columns.
* Power Query uses M language for data transformations.
* Example transformation steps include changing data types, renaming columns, or performing complex joins between tables.
3 Data Modeling:

* Power BI allows you to build relationships between tables, often resembling relational database structures.
* Relationships enable the combining of datasets for more complex analysis.
* You can define relationships between tables using primary keys and foreign keys, allowing cross-referencing of information.
* Example: Connecting Sales data with Products table via a common ProductID.
4 DAX (Data Analysis Expressions):

* DAX is a formula language used in Power BI for creating calculated columns, measures, and custom aggregations.
* It allows for advanced data manipulations, including time intelligence (e.g., calculating year-over-year growth) and conditional logic.
* Examples of DAX functions include:
* SUM(): Calculates the total of a column.
* AVERAGE(): Computes the average.
* CALCULATE(): Used for complex calculations by modifying the context.
* DATEADD(): Helps perform time-based calculations.
5 Visualizations:

* Power BI offers a wide range of visualizations, including bar charts, pie charts, line charts, tables, KPIs, and maps.
* Visualizations are highly interactive. For example, clicking on a bar in a chart will filter related visuals across the dashboard.
* Key visual elements in Power BI:
* Slicers: Allow users to filter data on reports and dashboards.
* Drill-downs: Enable deeper exploration of hierarchical data (e.g., from yearly data to monthly).
* Custom Visuals: Apart from the built-in ones, Power BI supports importing custom visuals for specialized use cases.
6 Dashboards and Reports:

* Reports: Pages of visuals derived from datasets. They can be single or multi-page.
* Dashboards: A collection of visuals from one or multiple reports, providing an at-a-glance overview.
* Dashboards can include KPIs, which are metrics that show key performance indicators.
7 Sharing and Collaboration:

* Power BI allows users to share reports and dashboards through the Power BI Service (the online version of Power BI).
* You can publish your work to the cloud, where others can access and interact with it.
* Row-level security can be applied to ensure that users only see the data they are allowed to view.
* Reports can also be embedded into other applications using Power BI Embedded.
8 Data Refresh and Real-Time Analytics:

* Power BI supports scheduled refresh for connecting live datasets, ensuring that your reports are always up-to-date.
* Real-time dashboards can be created using live data feeds (e.g., IoT sensor data or live transaction data).
* Refresh schedules can be customized for daily, hourly, or more frequent updates.
9 Power BI Service vs. Power BI Desktop:

* Power BI Desktop: Used for creating reports and visualizations locally.
* Power BI Service: A cloud-based platform where reports can be published, shared, and consumed by users.
Reports created in Power BI Desktop can be uploaded to the Power BI Service for real-time collaboration.
10 Power BI Mobile:

* Power BI has a mobile version that allows users to view reports and dashboards on smartphones and tablets, providing flexibility and accessibility for insights on the go.


