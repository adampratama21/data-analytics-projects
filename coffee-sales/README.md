# 📊 Coffee Sales Dashboard (March 2024-March 2025)

This project analyzes the Coffee Sales dataset from March 2024 to March 2025 downloaded from Kaggle. The data represents purchases made using a coffee machine installed in a shopping center in Vinnytsia, Ukraine. It includes **exploratory data analysis (EDA)** using Excel and **interactive dashboard creation** using **Power BI**.

## 📁 Project Structure

```
📦 coffee-sales/
├── data/
│ ├── original/
│ │ └── index_1.csv
│ │ └── index_2.csv
│ ├── working/
│ │ ├── coffee_sales_vending_machine.csv
│ └── index_1_cleaned.csv
│ └── index_2_cleaned.csv
│ └── index_all.csv
├── docs/
│ ├── images/
│ │ ├── dashboard_overview.png
│ │ ├── date_slicer.png
│ │ ├── machine_button_slicer.png
│ │ ├── most_popular_product_card.png
│ │ ├── payment_type_distribution_card.png
│ │ ├── top_products_by_total_sales_matrix.png
│ │ ├── total_items_sold_card.png
│ │ └── total_sales_by_machine_card.png
│ │ └── total_sales_by_month_chart.png
│ │ └── total_sales_card.png
│ ├── Coffee_Sales_Dashboard.pdf
│ └── Coffee_Sales_Dashboard_Guide.pptx
├── powerbi_dashboard/
│ └── Coffee_Sales_Dashboard.pbix
├── data_cleaning_log.txt
└── README.md
```

## 📌 Objectives

- Perform Exploratory Data Analysis (EDA) on the Coffee Sales dataset
- Visualize the dataset using Power BI
- Create an interactive dashboard for deeper insights
- Provide usage instructions for the dashboard

## 📊 Exploratory Data Analysis

EDA was performed using Microsoft Excel with pivot tables and charts. Key analyses include:

- Total Sales By Machine (Machine 1 vs Machine 2)
- Month-over-Month Sales
- Payment Method Distribution for Each Machine
- Top Products By Machine
- Top Products By Month For Each Machine

Each analysis is available in separate worksheet tabs in `coffee_sales_vending_machine.xlsx`.

## 📈 Power BI Dashboard

An interactive dashboard was created using Power BI, featuring:

- Filterable slicers (e.g., Machine, Year and Month)
- Cards showing Total Sales, Total Sales by Machine, Total Items Sold, Payment Type Distribution, and Most Popular Product
- Matrix showing top products by total sales
- Line and stacked column chart displaying total sales by month

**Data Source:**  
Kaggle — [Coffee Sales](https://www.kaggle.com/datasets/ihelon/coffee-sales/)

**Last Data Refresh:**  
09/08/2025 14:44:13 WIB
**Downloaded at:**  
05/08/2025 14:57:09 WIB

## 📝 User Guide

See `Coffee_Sales_Dashboard_Guide.pptx` for instructions on how to use and interpret the dashboard, including tips such as:

- Selecting a product from the matrix visualization to filter and interact with other visualizations on the dashboard
- Use slicers to filter results by machine or by date (year and month)

## 🛠️ Tools Used

- Microsoft Excel (for EDA & pivot tables)
- Power BI (for data modeling & dashboard creation)

## ⚠️ Disclaimer

This project is intended for personal learning and practice purposes only. It demonstrates skills in data cleaning, exploratory data analysis (EDA), and data visualization using publicly available datasets. All data belongs to their respective owners.
