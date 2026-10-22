# CodeOrbit-Data-Analyst-Internship
Data cleaning and sales analysis projects using Microsoft Excel for my CodeOrbit Tech Data Analyst Internship.
This repository contains completed internship tasks involving data cleaning and data analysis using Python and Excel.

## Project 1: Data Cleaning in Excel/Python
A messy, realistic sample passenger dataset (modeled on the classic Titanic dataset) is cleaned, documented, and delivered in both Python/CSV and Excel formats.

**Result:** 79 raw rows → 64 clean rows, 0 missing values remaining.

**Files:**
- `make_messy_data.py` — generates the raw sample dataset
- `clean_data.py` — main cleaning script (documented, step-by-step)
- `build_cleaning_excel.py` — builds the formatted Excel deliverable
- `titanic_raw_messy.csv` — raw, uncleaned sample dataset
- `titanic_cleaned.csv` — final cleaned dataset
- `cleaning_log.txt` — auto-generated log of every cleaning step
- `Titanic_Data_Cleaning.xlsx` — Excel workbook: raw data, cleaned data, summary, log
- `Data_Cleaning_Report.docx` — written report documenting the process

**Run it:**
```bash
python make_messy_data.py     # (optional) regenerate raw sample data
python clean_data.py          # clean the data
python build_cleaning_excel.py  # (optional) rebuild the Excel workbook
```

## Project 2: Sales Data Analysis with Pandas
A sample sales dataset (250 orders, 4 categories, 4 regions, 12 months) is analyzed with pandas to calculate key metrics, identify top products, and summarize trends by category, region, and time period.

**Key findings:** Total sales of $54,966.02 across 250 orders (avg order value $219.86). Furniture drives 67.1% of revenue; the South region leads sales; Q2 was the strongest quarter.

**Files:**
- `make_sales_data.py` — generates the raw sample dataset
- `analyze_sales.py` — main analysis script (metrics, groupings, pivot table)
- `build_sales_excel.py` — builds the formatted Excel deliverable with charts
- `sales_data.csv` — raw sample sales dataset
- `analysis_log.txt` — auto-generated log of all metrics and summaries
- `Sales_Data_Analysis.xlsx` — Excel workbook: summary, raw data, grouped tables, charts
- `Sales_Analysis_Report.docx` — short findings report

**Run it:**
```bash
python make_sales_data.py     # (optional) regenerate raw sample data
python analyze_sales.py       # run the analysis
python build_sales_excel.py   # (optional) rebuild the Excel workbook
```

## Technologies Used
- Python 3.12
- pandas — data manipulation, cleaning, and analysis
- openpyxl — Excel workbook formatting and charts
- NumPy — synthetic data generation

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <YOUR_GITHUB_REPO_LINK>
   cd data-cleaning-internship-task
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy openpyxl
   ```

3. **Run either project** using the commands listed above.

## GitHub Repository Link
<YOUR_GITHUB_REPO_LINK>
# CodeOrbit – E-Commerce Sales Dashboard

## Project Overview

This project is part of the **CodeOrbit Tech Data Analyst Internship – Task 3**.

The objective of this project is to create a simple and easy-to-understand **E-Commerce Sales Dashboard** using **Microsoft Power BI**.

The dashboard summarizes important sales information and presents it through KPI cards, charts, and a Top 10 Products table.

##  Tools Used

- Microsoft Power BI Desktop
- CSV Dataset
- DAX Measures

##  Dataset

Dataset used:

`ecommerce_sales_analysis(1).csv`

The dataset contains e-commerce product information including:

- Product ID
- Product Name
- Category
- Price
- Review Score
- Review Count
- Monthly Sales from Month 1 to Month 12

##  Dashboard Components

The dashboard contains the following visualizations:

### 1. Total Sales
Displays the overall sales quantity across all products and months.

**Total Sales: 6M**

### 2. Total Revenue
Displays the total revenue generated from the products.

**Total Revenue: 1.49bn**

### 3. Category-wise Sales
A bar chart showing total sales for each product category.

Categories include:

- Books
- Toys
- Sports
- Electronics
- Health
- Clothing
- Home & Kitchen

### 4. Monthly Sales
A line chart showing the sales trend from Month 1 to Month 12.

### 5. Top 10 Products
A table displaying the top 10 products based on Total Sales.

##  Key Objectives

- Analyze e-commerce sales data
- Identify high-performing product categories
- Understand monthly sales trends
- Identify the top-selling products
- Present business insights through an interactive dashboard

##  Project Files

```text
CodeOrbit_Task3_Ecommerce_Sales_Dashboard/
│
├── ecommerce_sales_analysis(1).csv
├── CodeOrbit_Task3_Ecommerce_Sales_Dashboard.pbix
└── README.md
