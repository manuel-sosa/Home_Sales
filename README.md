# Home Sales Analysis using SparkSQL :house:
This repository contains code and analysis for the Module 22 Challenge, focusing on key metrics extraction from home sales data using SparkSQL.

# Project Overview :chart:
The goal of this project is to leverage SparkSQL to perform detailed analysis on a dataset of home sales. The tasks involve creating temporary views, caching data for performance improvement, and partitioning data for efficient querying. The repository demonstrates various operations typical in a data analysis workflow using PySpark.

# Requirements :hammer_and_wrench:
- Apache Spark
- PySpark
- Python 3.x

# Data :memo:
The analysis is based on the home_sales_revised.csv file. The data includes various details about home sales such as the number of bedrooms, bathrooms, floors, square footage, and selling price.

# Analysis :chart_with_upwards_trend:
The analysis involves several key operations:

1. Data Loading and View Creation: Load data into a Spark DataFrame and create a temporary view for querying.
2. Querying Data: Perform SQL queries to calculate:
 - Average price for four-bedroom homes sold per year.
 - Average price of homes per year built with specific features.
 - Impact of view ratings on average home prices.
3. Performance Optimization: Utilize caching and data partitioning to optimize query performance.
4. Runtime Comparison: Compare runtimes between cached and uncached data scenarios.

# File Descriptions :file_folder:
Home_Sales.ipynb: Jupyter notebook containing the PySpark code for the analysis.