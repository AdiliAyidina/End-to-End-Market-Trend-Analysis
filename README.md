# Unlocking Market Insights: A Comprehensive EDA of Global Automotive Sales
An end-to-end Exploratory Data Analysis project analyzing transaction records across 19 countries. Key highlights include data cleaning of geographical inconsistencies, identification of Q4 seasonality patterns, and strategic recommendations for high-value account management (KAM) based on revenue 'burst points'.

## 📌 Project Overview
This repository contains a comprehensive **Exploratory Data Analysis (EDA)** on global vehicle sales data. The project analyzes transaction records from January 2003 to June 2005, covering various product lines including classic cars, vintage cars, motorcycles, planes, trucks, buses, and trains.

The primary goal is to uncover market trends, regional performance, and the relationship between pricing strategies and order volumes across 19 countries.

## 📊 Key Business Questions Addressed
- What are the sales trends over the 3-year period?
- Which product lines and countries drive the highest revenue?
- How does the Unit Price (PRICEEACH) correlate with the Quantity Ordered?
- Are there significant regional disparities in sales performance?

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas (Data Manipulation), Seaborn & Matplotlib (Visualization), Scikit-learn (Statistical Logic).
- **Environment:** Jupyter Notebook

## 🧪 Data Cleaning & Transformation
A significant portion of this project focused on ensuring data quality:
- **Missing Value Imputation:** Handled missing values in geographic columns like `TERRITORY`.
- **Regional Reclassification:** Corrected inconsistencies in the `TERRITORY` column (e.g., remapping USA/Canada to 'Americas' and standardizing APAC regions).
- **Feature Engineering:** Dropped irrelevant CRM attributes (Address lines, Phone numbers, etc.) to focus on core analytical metrics: `SALES`, `QUANTITYORDERED`, and `PRODUCTLINE`.

## 📈 Insights & Findings
*Selected highlights from the analysis:*
1. **Regional Dominance:** The **Americas** and **EMEA** represent the largest market shares, with the USA being a critical revenue driver.
2. **Product Performance:** Classic Cars consistently outperform other categories in both sales volume and total revenue.
3. **Seasonality:** Identified "Burst Points" in revenue, specifically 81 high-value orders that disproportionately impact global profitability.
4. **Strategic Recommendation:** Focus on high-value account management (KAM) for top-tier orders and introduce "Premium" variants to maximize unit profit in underperforming regions.

## 🚀 How to Run
