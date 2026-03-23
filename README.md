# Walmart Sales Forecasting & Data Visualization Project

## 📌 Project Overview
This project focuses on analyzing Walmart sales data to identify key trends, seasonal patterns, and the impact of external economic factors. By combining *Python* for deep-dive exploratory data analysis (EDA) and *Power BI* for interactive stakeholder dashboards, this study transforms raw retail data into actionable business intelligence.

---

## 📊 Dataset Description
The analysis utilizes four primary datasets sourced from Kaggle, encompassing store-level details and external environmental factors:

* *Features Data:* Store-specific metrics including temperature, fuel prices, CPI (Consumer Price Index), unemployment rates, and promotional markdowns.
* *Stores Data:* Categorical information including Store ID, Type (A, B, C), and Size.
* *Training Data:* Historical weekly sales records segmented by Store and Department.
* *Test Data:* Data prepared for future sales prediction, containing store ID, department, date, and holiday status.

---

## ⚙️ Data Processing Workflow

### 1. Data Loading & Inspection
Initial data ingestion is performed using Python libraries (Pandas). We conduct a structural audit to identify data types, schema consistency, and missing values—specifically within the markdown columns.

### 2. Data Cleaning & Preparation
* *Date Standardization:* Converted date strings into datetime objects for time-series analysis.
* *Feature Engineering:* Removed redundant columns and handled null values to ensure data integrity.
* *Data Sorting:* Chronological sorting to ensure accurate trend line visualization.
* *Export:* Saved the cleaned dataset into a centralized file for Power BI integration.

### 3. Data Exploration & Visualization
Using *Matplotlib*, we visualized several critical relationships:
* *Store Type Distribution:* Determining which store categories generate higher sales.
* *Yearly/Monthly Trends:* Identifying seasonal spikes (2010–2012).
* *Economic Impact:* Analyzing how *Fuel Prices, **Temperature, and **Unemployment* correlate with weekly sales.
* *Holiday Analysis:* Measuring the "lift" in sales during holiday periods versus non-holiday weeks.

---

## 📈 Power BI Interactive Dashboards
Beyond static plots, an interactive Power BI suite was developed to allow stakeholders to drill down into specific metrics.

*Key Dashboard Features:*
* *KPI Scorecards:* Instant visibility into Total Sales, Average Weekly Sales, and Economic Averages.
* *Dynamic Filters:* Slicers for Date Ranges, Months, and Years.
* *Distribution Analysis:* Weekly sales spread visualized by holiday status and store type.
* *Store Insights:* Identification of high-performing stores to drive strategic decisions.

---

## 🛠️ Tech Stack
* *Language:* Python (Pandas, Matplotlib, Seaborn)
* *Tool:* Power BI Desktop
* *Dataset Source:* Kaggle Walmart Recruiting - Store Sales Forecasting

## 📂 Project Resources & Dashboard Access
Due to the large file size of the interactive Power BI report (.pbix), the full dashboard file is hosted on Google Drive. You can download and explore the interactive visualizations, including the KPI slicers and store-specific performance metrics, via the link below:

👉 *[Download Power BI Dashboard File](https://drive.google.com/file/d/1lG_EBjUpIjIPP_oGUnr6rhN4rsKfy0yi/view?usp=sharing)*

Note: You will need [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed to open and interact with the .pbix file.

## 📂 Access to output_file CSV Datase

Due to large file size the CSV dataset has been uploaded to a dedicated Google Drive folder for easy access. You can download the output file via the following link:

👉 [Download CSV Dataset Folder](https://drive.google.com/file/d/1W9UXgQlQrss0-ps6GAc4NU9VrqJVc_TJ/view?usp=sharing)

This file support the Power BI report and enable detailed data analysis.
