# home-sales-challenge

# Home Sales Analysis with PySpark

This project involves using PySpark SQL to analyze home sales data. It includes answering specific questions using SparkSQL functions, caching tables, handling Parquet data, and evaluating query runtimes.

## Assignment Overview

The task involves performing various analyses and answering specific questions using PySpark SQL functions. Below are the main steps covered in this notebook:

1. **Data Ingestion:** Reading the `home_sales_revised.csv` data into a Spark DataFrame.
2. **Creating a Temporary Table:** Creation of a temporary table named `home_sales`.
3. **Analysis Questions:** Using SparkSQL to answer specific questions:
    - Average price for a four-bedroom house sold for each year.
    - Average price of a home for each year built with three bedrooms and three bathrooms.
    - Average price of a home for each year with specific criteria (three bedrooms, three bathrooms, two floors, and area ≥ 2,000 square feet).
    - View rating for homes costing more than or equal to $350,000, with runtime evaluation.
4. **Table Caching:** Caching the `home_sales` temporary table and checking if it's cached.
5. **Cached Queries:** Running cached and uncached queries to compare the runtime difference.
6. **Handling Parquet Data:** Partitioning by the "date_built" field, creating a temporary table for Parquet data.
7. **Query Runtime Evaluation:** Running a query on Parquet data with runtime evaluation.
8. **Uncaching Tables:** Uncaching the `home_sales` temporary table and verifying if it's uncached using PySpark.

## Author and Data
Mu Li, 12/6/2023
