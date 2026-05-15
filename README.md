# E-Commerce Sales Data Cleaning Automation

## 📌 Project Overview
In the e-commerce industry, sales data is often collected from multiple sources, leading to inconsistencies, duplicates, and formatting errors. This project automates the **End-to-End (E2E) cleaning process** using Python and Pandas, transforming 500+ rows of "dirty" data into an audit-ready dataset.

## 🛠️ Skills & Tools Used
- **Language:** Python
- **Libraries:** Pandas, NumPy
- **Environment:** Jupyter Notebook / Anaconda
- **Techniques:** Data Sanitization, Date Standardization, Deduplication, String Manipulation.

## 📁 Repository Structure
- `E-Commerce_Sales_Data_Cleaning_Automation.ipynb`: The primary Python notebook containing the automation logic.
- `raw_sales_data_500.csv`: The initial messy dataset (simulated).
- `final_cleaned_sales_data.csv`: The final output after the pipeline execution.

## 🚀 Key Features
1. **Automated Deduplication:** Identified and removed 100+ duplicate records.
2. **Date Standardization:** Unified multiple formats (DD-MM-YYYY, YYYY-MM-DD) into a single ISO standard.
3. **Sales Sanitization:** Converted text-based errors (e.g., "ERROR") into numerical values for financial analysis.
4. **Product Normalization:** Cleaned inconsistent product names (e.g., 'laptop' vs 'LAPTOP') into professional title-case categories.

## 📊 Results
The pipeline successfully processed the raw data, reducing errors by **100%** and ensuring the final CSV is ready for ingestion into Power BI or SQL databases for reporting.

---
*Created by Kausombi as part of a Data Analyst Portfolio transition.*
