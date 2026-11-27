# Retail Store Sales Analysis Using Python

## Project Overview
This project focuses on analyzing retail store sales data using Python. The main objective is to explore sales transactions and understand customer purchasing behaviour, product categories, payment methods, and sales patterns.

## Dataset Information
- Total Records: 12,575
- Total Columns: 11
- Dataset: Retail Store Sales

### Key Columns
- Transaction ID
- Customer ID
- Category
- Item
- Price Per Unit
- Quantity
- Total Spent
- Payment Method
- Location
- Transaction Date
- Discount Applied

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Workflow

### 1. Data Loading
- Imported the retail sales dataset using Pandas.
- Loaded the CSV file into a DataFrame.

### 2. Data Inspection
- Checked dataset dimensions using `shape`.
- Inspected column names and data types using `info()`.
- Viewed sample records using `head()`.

### 3. Statistical Analysis
- Used `describe()` to understand numerical columns.
- Examined price, quantity, and total spending distributions.

### 4. Missing Value Analysis
- Identified missing values using `isnull()`.
- Calculated missing-value counts for each column.
- Inspected records containing missing values.
- Examined missing values in Price Per Unit, Item, Quantity, Total Spent, and Discount Applied.

### 5. Data Exploration
- Explored relationships between price per unit, quantity, and total spending.
- Examined transaction details and customer purchase information.

## Project Objective
The project aims to understand retail transaction data and identify useful information about sales, customer purchases, product categories, and payment preferences.

## Repository Files
- `retail_store_sales.ipynb` – Python analysis notebook.
- `retail_store_sales.csv` – Original dataset.
- `retail_store_sales_cleaned.csv` – Cleaned dataset file.
- `dashboard1.png`, `dashboard2.png`, `dashboard3.png` – Project dashboard screenshots.

## Conclusion
This project demonstrates the use of Python and Pandas for exploring retail sales data, inspecting dataset quality, identifying missing values, and performing basic statistical analysis.




## Business Questions & Data Visualization

The project explores the following business questions using Python, Pandas, and Matplotlib.

### 1. How do sales change across different months?
- Chart: Monthly Sales Trend
- Visualized monthly revenue trends using a Line Chart.

### 2. Which are the top 10 products generating the highest revenue?
- Chart: Top 10 Products by Revenue
- Used a Horizontal Bar Chart to identify top-performing products.

### 3. How do discounts affect total revenue?
- Chart: Revenue: With vs Without Discount
- Compared revenue generated from discounted and non-discounted transactions using a Bar Chart.

### 4. Who are the top 10 customers based on total spending?
- Chart: Top 10 Customers by Total Spending
- Used a Horizontal Bar Chart to identify the highest-spending customers.

### 5. Which payment method generates the highest revenue?
- Chart: Revenue by Payment Method
- Compared revenue across different payment methods using a Bar Chart.

### 6. Which product category has the highest average spending?
- Chart: Average Spending by Category
- Used a Bar Chart to compare average customer spending across product categories.

## Key Analysis Areas
- Monthly sales performance
- Top-performing products
- Discount-based revenue comparison
- Customer spending analysis
- Payment method performance
- Category-wise average spending

## Conclusion
This project demonstrates how Python-based Exploratory Data Analysis (EDA) can help understand retail sales performance, customer purchasing behaviour, product performance, and revenue patterns.


