# Task 1: Data Cleaning and Preprocessing

This repository contains code and output files for cleaning the Customer Personality Analysis dataset using Python (Pandas).

## 🧪 What’s included:
- `cleaning_task.ipynb`: colab notebook with full cleaning code
- `cleaned_customer_data.csv`: Cleaned dataset
- `README.md`: This file

## ✅ Cleaning Steps
- Dropped unnecessary columns: ID, Z_CostContact, Z_Revenue
- Renamed all columns to lowercase with underscores
- Handled missing values in income
- Removed duplicates
- Standardized text columns (education, marital_status)
- Converted date column to datetime
- Created new columns: age, customer_since_days, total_spent
