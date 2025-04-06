# Home Sales Analysis with PySpark

## Overview

This project leverages PySpark and SparkSQL to perform data analysis on home sales data. The analysis includes creating temporary views, executing SQL queries, partitioning data, caching and uncaching tables, and comparing query runtimes. This notebook is a challenge assignment for Module 22 of the Data Science Bootcamp.

## Technologies Used

- Python 3.x
- PySpark
- SparkSQL
- Jupyter Notebook
- AWS S3 (data source)

## Files

- `Home_Sales.ipynb` – The main notebook containing the code and output for all tasks.
- `home_sales_revised.csv` – The source data file (provided via AWS S3 bucket).
- `README.md` – Project documentation (this file).

## Tasks Completed

✅ Load home sales data into a Spark DataFrame  
✅ Create a temporary table named `home_sales`  
✅ Run SQL queries to calculate average home prices based on different criteria  
✅ Use caching to improve performance and compare runtimes  
✅ Partition the dataset by `date_built` and write/read to Parquet  
✅ Create a temporary table from Parquet data and re-run SQL queries  
✅ Uncache the original `home_sales` table and verify  

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Home_Sales.git
   cd Home_Sales
