# 📊 Netflix Shows Dashboard (2008–2021)

This project explores the Netflix Shows Dataset from 2008 to 2021 downloaded from Kaggle. It includes **exploratory data analysis (EDA)** using Excel and **interactive dashboard creation** using **Power BI**.

## 📁 Project Structure

```
📦 netflix-shows/
├── data/
│   ├── original/
│   │   └── netflix_titles.csv
│   ├── working/
│   │   ├── netflix_titles_fixed.csv
│   │   └── netflix_titles_working.xlsx
│   └── netflix_titles_cleaned.csv
├── docs/
│   ├── images/
│   │   ├── dashboard_overview.png
│   │   ├── filter_panel.png
│   │   ├── most_popular_rating_card.png
│   │   ├── top5_countries_by_total_shows.png
│   │   ├── top5_genres_by_type.png
│   │   ├── total_shows_by_country.png
│   │   ├── total_shows_by_date_added.png
│   │   └── total_shows_card.png
│   ├── Netflix_Dashboard_Guide.pptx
│   └── Netflix_Shows_Dashboard.pdf
├── powerbi_dashboard/
│   └── netflix_shows.pbix
├── data_cleaning_log.txt
└── README.md

```

## 📌 Objectives

- Perform Exploratory Data Analysis (EDA) on the Netflix dataset
- Visualize the dataset using Power BI
- Create an interactive dashboard for deeper insights
- Provide usage instructions for the dashboard

## 📊 Exploratory Data Analysis (Excel)

EDA was performed using Microsoft Excel with pivot tables and charts. Key analyses include:

- Type Distribution (Movie vs TV Show)
- Top 10 Genres
- Rating Distribution
- Top 10 Countries with Most Shows
- Shows Added Over the Years

Each analysis is available in separate worksheet tabs in `netflix_titles_working.xlsx`.

## 🧭 Power BI Dashboard

An interactive dashboard was created using Power BI, featuring:

- Filterable slicers (e.g., Year Added, Type)
- Cards showing the most popular rating and total shows grouped by type
- Map visualizing total shows by country
- Stacked column chart displaying shows added over the years
- Stacked bar charts for top 5 genres and countries

**Data Source:**  
Kaggle — [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

**Last Data Refresh:**  
29/07/2025 21:51:58 WIB  
**Downloaded at:**  
28/07/2025 23:31:51 WIB

## 📝 User Guide

See `Netflix_Dashboard_Guide.pptx` for instructions on how to use and interpret the dashboard, including tips like:

- Hover over map bubbles to view total shows per country
- Use slicers to filter results by year and type.

## 🛠️ Tools Used

- Microsoft Excel (for EDA & pivot tables)
- Power BI (for data modeling & dashboard creation)
- Power Pivot (for distinct count calculations)

## ⚠️ Disclaimer

This project is intended for personal learning and practice purposes only. It demonstrates skills in data cleaning, exploratory data analysis (EDA), and data visualization using publicly available datasets. All data belongs to their respective owners.
