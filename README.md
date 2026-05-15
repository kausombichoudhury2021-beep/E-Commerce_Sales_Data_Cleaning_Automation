# E-Commerce Sales Data Cleaning Automation

## Developer
**Kausombi Choudhury** *Aspiring Data Analyst | Safety Command Executive*

---

## Project Overview
This project demonstrates an automated **ETL (Extract, Transform, Load)** pipeline built with Python. It takes a "messy" dataset of 500+ e-commerce sales records and automates the cleaning process to produce an audit-ready CSV file.

## The Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Warnings
- **Platform:** Jupyter Notebook / Anaconda

## Repository Structure
- `raw_sales_data_500.csv`: The initial messy dataset containing duplicates, errors, and inconsistent formats.
- `E-Commerce_Sales_Data_Cleaning_Automation.ipynb`: The Python notebook containing the transformation logic.
- `final_cleaned_data_500.csv`: The polished, final output ready for analysis.

## Key Automation Features
1. **Warning Suppression:** Implemented `warnings.filterwarnings` to ensure a clean, professional output for stakeholders.
2. **Date Standardization:** Automated conversion of mixed date formats into a unified standard.
3. **Financial Sanitization:** Handled text-based errors (e.g., "ERROR") in sales columns using `pd.to_numeric`.
4. **Data Deduplication:** Identified and removed over 100 redundant rows.
5. **Product Normalization:** Standardized naming conventions using string manipulation.

## Business Impact
By automating these manual tasks, this script saves approximately 2–3 hours of manual data entry work per reporting cycle, ensuring 100% data integrity for downstream Power BI dashboards or SQL databases.
