# ☕ Cafe Sales Data Cleaning & EDA Project

This is a small portfolio project focused on **data cleaning** and **exploratory data analysis (EDA)** using Microsoft Excel and CSV data. The dataset represents transaction records from a café business, containing various quality issues that were cleaned prior to analysis.

## 📁 Project Structure

```
cafe-sales-data-cleaning/
│
├── data/
│ ├── original/ # Original dataset from Kaggle
│ │ └── dirty_cafe_sales.csv
│ ├── working/ # Working files used during analysis
│ │ └── cafe_sales_working.xlsx
│ └── cafe_sales_cleaned.csv # Cleaned dataset (final version)
│
├── docs/
│ └── images/ # Screenshots of charts, tables, etc.
│
├── data_cleaning_log.txt # Log of cleaning steps performed
└── README.md # This file
```

## 📌 Objectives

- Perform data cleaning and Exploratory Data Analysis (EDA) on the Cafe Sales dataset
- See [`data_cleaning_log.txt`](./data_cleaning_log.txt) for detailed cleaning steps.

## 📊 Exploratory Data Analysis

EDA was done entirely in Excel and includes:

- Total Quantity Sold and MoM Change
- Quantity Percentage by Product and Month
- Total Sales and MoM Change
- Sales by Location and Product
- Unknown Transactions (e.g., blank values or unmatched products)

Each analysis is available in `cafe_sales_working.xlsx`.

Visualizations used:

- Column Charts
- Line Charts
- Bar Chart
- Sparkline

## 📌 Key Insights

- Coffee is the most sold product by quantity, with 3,251 units sold.
- Tea generated the highest total sales, contributing 26.96% of total revenue.
- Sales peaked in October, indicating a possible seasonal trend.
- Digital Wallet is the most commonly used payment method for Takeaway orders, while Cash dominates In-store transactions.
- Several unknown transactions with missing dates were found and should be investigated further.
- A large number of transactions also had **unknown payment methods**, which — along with unknown locations — make up the majority of transactions in the dataset. These categories were included and highlighted in yellow to reflect potential gaps in the data collection system.

## 🛠️ Tools Used

- Microsoft Excel

## ⚠️ Disclaimer

- This analysis is done on a sample dataset, not real-time data
- No advanced statistical modeling was applied

## 📂 Data Source

- The dataset was sourced from [Kaggle - Cafe Sales Dirty Data](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training).
- Downloaded on: **31 July 2025**
