# Online-Retail-Data-Cleaning
Data cleaning and preprocessing of the UCI Online Retail dataset using Python, Pandas, and Jupyter Notebook
E-Commerce Sales & Customer Analytics

Project Overview

This project focuses on cleaning and preprocessing the Online Retail dataset from the UCI Machine Learning Repository. The goal is to transform raw transactional data into a clean, analysis-ready dataset for further sales analysis and customer segmentation.

Dataset

- Dataset: Online Retail.xlsx
- Source: UCI Machine Learning Repository
- Records: 541,909 transactions
- Features: Invoice numbers, stock codes, descriptions, quantities, invoice dates, unit prices, customer IDs, and countries.

Task 1: Data Cleaning and Preprocessing

The following steps were performed:

- Loaded the dataset using Pandas
- Handled missing values
- Removed cancelled orders (InvoiceNo starting with 'C')
- Removed transactions with non-positive quantities and prices
- Removed duplicate records
- Created a TotalPrice column
- Extracted Year, Month, Day, Hour, and DayOfWeek from InvoiceDate
- Exported the cleaned dataset as CSV

Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

Output Files

- task1_data_cleaning.ipynb
- OnlineRetail_clean.csv

Author

Ashwathi
