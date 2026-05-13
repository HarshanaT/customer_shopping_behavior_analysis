# Customer Shopping Trends Analysis 

## Project Overview
This project focuses on analyzing customer purchasing behavior and optimize marketing strategies. Built an end-to-end data pipeline starting from raw data cleaning in Python, moving to structured storage in MySQL, and finishing with an interactive dashboard in Power BI.

## Tech Stack
- **Data Cleaning:** Python (Pandas, NumPy)
- **Database Management:** MySQL Workbench
- **Data Visualization:** Power BI 
- **Environment:** VS Code, Jupyter Notebooks

## The Data Pipeline

### Data Cleaning & Preprocessing (Python)
- Handled missing values and outliers in the raw dataset.
- Formatted currency and categorical columns for SQL compatibility.
- Exported the final `cleaned_data.csv` for database ingestion.

### Database Management (SQL)
- Imported the cleaned dataset into a MySQL schema.
- Performed complex queries to verify data integrity, including:
  - **Subqueries:** Identifying customers spending above average while using discounts.
  - **Aggregations:** Calculating average ratings per product category.
  - **Filtering:** Comparing "Standard" vs "Express" shipping revenue.

### Data Visualization (Power BI)
Built an interactive dashboard to answer key business questions:
- **Top 5 Performing Products:** Based on average review ratings.
- **Shipping Method Impact:** Comparing purchase amounts across shipping tiers.
- **Customer Segmentation:** Ccalculate unique customer counts and average transaction values.



