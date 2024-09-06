Retail Sales Data Analysis
Project Overview
This project focuses on analyzing a retail dataset sourced from Kaggle to derive key business insights, such as top-selling products, regional sales leaders, and month-over-month sales comparisons. It involves data cleaning and preprocessing using Python (Pandas), followed by querying the data in SQL to answer specific business questions. The goal is to help retail businesses make data-driven decisions.

Technologies Used
Python (Pandas): For data cleaning and preprocessing.
SQL (SQL Server): For running queries to extract insights from the cleaned data.
SQLAlchemy: For connecting Python to the SQL Server.
Steps Involved
1. Dataset Source
The retail dataset was sourced from Kaggle and contains detailed records of orders, including product details, order dates, prices, and profits.
2. Data Cleaning and Preprocessing (Python)
Handle Missing Values: Replaced 'Not Available' and 'unknown' values with NaN.
Column Renaming: Standardized column names by converting them to lowercase and replacing spaces with underscores.
Derived Columns: Calculated new columns such as profit (sale price - cost price).
Date Formatting: Converted the order_date column from string format to datetime for easier querying.
Dropping Unnecessary Columns: Removed redundant columns like list_price, cost_price, and discount_percent.
3. Data Upload to SQL Server
Loaded the cleaned dataset into a SQL Server database using SQLAlchemy, allowing further analysis through SQL queries.
4. SQL Queries for Insights
Top 10 Revenue Generating Products:
Identified the top 10 products generating the highest revenue.
Top 5 Products by Region:
Analyzed sales to find the top 5 selling products in each region.
Month-over-Month Growth (2022 vs. 2023):
Compared sales growth month-over-month for 2022 and 2023.
Highest Sales Month by Category:
Determined which months had the highest sales for each product category.
Subcategory Profit Growth (2022 vs. 2023):
Found the subcategory with the highest growth in profit between 2022 and 2023.
