Retail Store Sales Data Cleaning

  -About the Project

This is my first data cleaning project using Python and Pandas. I worked with a retail store sales dataset to understand how to clean raw data and make it ready for further analysis.

## What I Did

- Checked the dataset structure, columns, and data types.
- Identified missing values in different columns.
- Filled missing prices using the total spent and quantity when both values were available.
- Converted the transaction date column to datetime format.
- Converted the discount column to a Boolean data type while keeping unknown values as missing.
- Checked for duplicate rows and found no duplicates.
- Verified that the total spent matched the price per unit multiplied by the quantity wherever the values were available.
- Checked for zero and negative values in prices, quantities, and total amounts.

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- CSV dataset

## Dataset Overview

- Rows: 12,575
- Columns: 11
- Data: Retail transactions, including product categories, prices, quantities, payment methods, locations, and transaction dates.

## Handling Missing Values

Some missing values remained after cleaning because I could not determine their correct values from the available data. I left missing item names, quantities, total amounts, and discount statuses unchanged rather than filling them with guesses.

## Output

The cleaned dataset was saved as `retail_store_sales_cleaned.csv`.

## What I Learned

Through this project, I learned how to inspect a dataset, handle missing values, convert data types, check duplicates, validate calculations, and save a cleaned CSV file using Pandas.

This project helped me get more practical experience with data cleaning and understand the importance of checking data quality before analysis.
