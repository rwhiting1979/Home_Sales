# PySpark Home Sales Analysis

## Overview
Leverage PySpark for analyzing home sales data, focusing on deriving insights such as average prices under various filters. Demonstrates data querying, performance optimization via caching, and partitioning.

## Project Structure
- **Home_Sales.ipynb**: Google Colab notebook with PySpark scripts.
- **home_sales_revised.csv**: Dataset for analysis.

## Execution Steps

### Data Loading
- Load the dataset into a Spark DataFrame.

### SQL Analysis
- Create `home_sales` temporary view for SQL queries.
- Execute queries analyzing average prices based on various home features.

### Optimization
- Cache `home_sales` view for faster query execution.
- Partition data by `date_built` for optimized storage and query performance.

### Performance Comparison
- Analyze query performance with and without caching.
- Evaluate query efficiency on partitioned data versus non-partitioned data.

### Cleanup Operations
- Uncache the `home_sales` view and confirm uncaching.

## Key Queries
1. Average price for homes with four bedrooms, by year sold.
2. Average price for homes built each year, with three bedrooms and three bathrooms.
3. Average price for homes with detailed features, by year built.
4. Average price by "view" rating, with a minimum average price condition.

## Conclusion
This project showcases PySpark's capabilities for data analysis, emphasizing query performance improvements through caching and data partitioning strategies.
