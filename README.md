# Superstore Sales Data Cleaning & Preprocessing Project

## Project Overview

This project focuses on cleaning and preprocessing a retail sales dataset using Microsoft Excel.  
The objective of this project was to improve data quality, standardize formatting, remove inconsistencies, and prepare the dataset for SQL analysis and Power BI dashboard development.

The dataset used in this project contains retail sales transaction data including customer details, product information, sales, profit, shipping details, and regional performance.

---

# Project Objective

The main goal of this project was to:

- Clean raw retail sales data
- Remove duplicate records
- Standardize date formatting
- Improve data consistency
- Create analytical columns for business insights
- Prepare structured data for further analytics and visualization

---

# Tools Used

| Tool | Purpose |
|------|----------|
| Microsoft Excel | Data cleaning and preprocessing |

---

# Data Cleaning Steps Performed

## 1. Duplicate Removal
- Identified and removed duplicate rows from the dataset.

## 2. Date Format Standardization
- Converted `Order Date` and `Ship Date` columns into proper datetime format.

## 3. Data Consistency Improvements
- Checked inconsistent values and standardized formatting.

## 4. Text Cleaning
- Removed extra spaces using Excel functions like `TRIM()`.

## 5. Column Review
- Reviewed unnecessary columns for removal to improve dataset efficiency.

## 6. Data Validation
- Verified dataset structure and formatting before SQL import.

---

# New Analytical Columns Created

| Column Name | Purpose |
|-------------|----------|
| Order_Year | Used for yearly sales trend analysis |
| Order_Month | Used for monthly trend analysis |
| Month_Number | Used for proper month sorting |
| Profit_Margin | Used to analyze profitability efficiency |
| Shipping_Days | Used to evaluate delivery performance |

---

# Why Data Cleaning Was Important

Data cleaning is a critical step in the data analytics process because inaccurate or inconsistent data can lead to incorrect analysis and poor business decisions.

After cleaning, the dataset became:
- Structured
- Consistent
- Analysis-ready
- Suitable for SQL and Power BI

---

# Dataset Files

## Raw Dataset
- Original retail sales dataset before cleaning

## Cleaned Dataset
- Final cleaned dataset prepared for analytics

---

# Project Folder Structure
```text
superstore-data-cleaning-analysis/
│
├── Raw_Dataset/
├── Cleaned_Dataset/
├── Screenshots/
├── Documentation/
└── README.md
