# Home_Sales

Overview:

This assignment uses Apache Spark and PySpark SQL to analyze home sales data. The assignment includes data, processing, SQL queries, and performance optimizations like caching and partitioning. The goal is to get insights from the dataset and optimize query execution.

Technologies:

- Python

- Apache Spark/ PySpark

- Google Colab

- SQL for data analysis

- Parquet for data storage


Dataset:

- The dataset 'home_sales_revised.csv' contains home sales data such as: sale price, number of bedrooms, number of bathrooms, living area, year built, sale date, number of floors, and view rate.


Key Tasks and Features:

- Load CSV from an AWS S3 bucket into a PySpark DataFrame.

- SQL Queries:

1. Find the average home price per yearfor different criteria

2. Analyze price trends based on number of bedrooms, bathrooms, and floors

3. Calculate average price per view rating for homes $350,000

- Performance Optimization

4. Caching: Cache the 'home_sales' table and compare query speed

5. Partitioning: Sote the data in 'parquet' format, partitioned by 'date_built', to optimize query performance

Runtime Comparison:

- Measure execution time for 'cached' vs 'non-cached' queries and 'Parquet' vs 'CSV'.


