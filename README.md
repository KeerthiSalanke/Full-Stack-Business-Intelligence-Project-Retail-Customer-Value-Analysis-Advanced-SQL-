Project Explanation
This project demonstrates proficiency in the full SQL Data Analytics lifecycle, encompassing the foundational steps of data structuring and cleansing, performing Exploratory Data Analysis (EDA), and executing complex analytical queries to answer specific business questions. It focuses on the crucial distinction between Dimensions (descriptive data) and Measures (quantitative, aggregable data).

Project Outcome and Deliverables
The main outcome is a structured, 
clean dataset (the Data Warehouse)  
series of sophisticated SQL queries that transform raw data into actionable business intelligence.

Key deliverables include:
A Structured Data Warehouse Schema: Designed to support efficient analytical queries.
SQL Scripts for ETL/ELT: Scripts for Data Cleansing, Integration, and Loading.
Comprehensive Analytical Reports: A set of advanced SQL queries demonstrating various analysis techniques.

Key Stages and Analytical Techniques
The project is broken down into three main phases, moving from foundational setup to advanced insights:
1. Data Warehousing & Preparation
This phase ensures the data is clean, structured, and ready for analysis using an ETL/ELT Process.

Goal: Organize, structure, and prepare the raw data.
Key Tasks:
Defining the data architecture.
Data Cleansing and Data Integration.
Data Modeling: Identifying and separating Dimensions (e.g., Category, Product, Country, Birthdate) from Measures (e.g., Sales, Quantity, Price).

2. Exploratory Data Analysis (EDA)
This phase involves understanding the data's characteristics and scope through basic querying.
Goal: Understand the data structure and content.
Key Tasks:
Profiling Dimensions: Using DISTINCT to explore unique values in dimensions (e.g., Country, Category).
Date Exploration: Determining the data range using MIN/MAX on date dimensions and calculating duration using functions like DATEDIFF.
Profiling Measures: Using simple aggregation functions like SUM and AVG to get key metrics.

3. Advanced Data Analytics
This phase utilizes complex SQL techniques (including Window Functions and CTEs) to answer business questions.
Goal: Generate reports and answer business questions through complex queries.
Key Analytical Tasks:Aggregation (Measure By Dimension): Calculating totals/averages grouped by different dimensions (e.g., Total Sales By Country)
Change-Over-Time Analysis: Analyzing trends over time (e.g., Total Sales By Year).
Cumulative Analysis: Calculating running totals and moving averages using Window Functions.
Performance Analysis: Comparing a measure to a target (e.g., Current Sales vs. Average Sales or Previous Year Sales) using Window Functions.
Part-to-Whole (Proportional) Analysis: Calculating the percentage contribution of each dimension to the total (e.g., Sales/Total Sales * 100 By Category).
Data Segmentation: Categorizing data based on measure ranges using the CASE WHEN statement (e.g., Total Products By Sales Range, categorized as Low, Medium, or Large).
