# 🚗 Automobile Sales & Market Insights Report: Data-Driven Strategy 📈

## Project Overview

This repository hosts the complete analysis of a three-year sales dataset (2003–2005) for an automobile company. The project transformed over **$10M in raw sales transaction data** into actionable business intelligence. Our core methodology combined **Python ETL** for data validation and engineering with **Tableau** for creating dynamic, executive-level dashboards focused on revenue optimization, risk mitigation, and product performance tracking.

---

## What We Did: Dataset, Methodology & Analysis Process 💻

### The Dataset
The foundation of this project is the **`DS1_C6_S6_Sales_Data.csv`** file, which is a detailed ledger of sales transactions. The dataset enabled multi-dimensional analysis by including crucial metrics such as:

* **Financial Indicators:** `SALES`, `PRICEEACH`, `MSRP` (used to model profitability and optimal discount levels).
* **Product Details:** `PRODUCTLINE` (e.g., Classic Cars, Vintage Cars) and `PRODUCTCODE` (used for inventory and product lifecycle analysis).
* **Geographic/Customer Data:** `COUNTRY` and `CUSTOMERNAME` (crucial for assessing market concentration and risk dependency).

### Methodology & Workflow
Our analysis followed a rigorous four-step process:

1.  **Data Cleaning & Engineering (Python):** The **`Tableau_Python_Cleaning.ipynb`** notebook was used to address data quality issues (e.g., missing values, type conversions) and engineer features like profit margins, ensuring the resulting **`Sales_Dataset_Tableau(cleaned).csv`** was optimized for BI tools.
2.  **Time-Series Analysis:** Examined `ORDERDATE` and `YEAR_ID` to track sales growth patterns, identify the **$3.91M peak in 2004** (representing **35% year-over-year growth**), and forecast recovery trends.
3.  **Customer/Geographic Segmentation:** Used `COUNTRY` and `CUSTOMERNAME` fields to segment sales, revealing the over-reliance on the US market and the top-performing customer, which contributed **9% of total revenue**.
4.  **Interactive BI Development (Tableau):** Created **six interconnected Tableau Dashboards** (spanning Sales, Forecasting, Pricing, and KPIs) designed for easy exploration by executive users and sales managers. 📊

---

## Key Findings & Strategic Impact 💡

The analysis delivered specific, high-value insights directly tied to business strategy:

* **Revenue Backbone:** **Classic Cars and Vintage Cars** drive the business, contributing nearly **60%** of total sales, demanding focused stock and marketing efforts. 💰
* **Optimal Pricing Strategy:** Deals featuring **10–15% discounts** were statistically proven to deliver the highest balance of sales volume and profitability, guiding future promotional campaigns. 🏷️
* **Risk Mitigation:** Successfully identified a major market concentration risk, leading to the strategic recommendation to **diversify the customer base** and aggressively pursue **geographic expansion into Europe**. 🌎
* **Operational Excellence:** The findings informed strategies for **stock management improvements** and targeted product support, moving resources away from weak-performing lines.

---

## Technical Stack & Repository Files 🛠️📁

| File Name | Tool / Technology | Description |
| :--- | :--- | :--- |
| `Tableau_Python_Cleaning.ipynb` | Python (Pandas, NumPy) 🐍 | Full ETL script for data cleaning, validation, and feature engineering. |
| `DS1_C6_S6_Sales_Data.csv` | Raw Source Data | The original, unfiltered sales transaction dataset (2003-2005). |
| `Project 1.twbx`/`Project 2.twbx` | Tableau Workbooks | Contains all **6 interactive executive dashboards** and final visualizations. |
| `Automobile-Sales-and-Market-Insights-Report.pptx` | PowerPoint | The final presentation slide deck summarizing all key findings and executive recommendations. 🎤 |

### Environment Setup
To replicate the analysis:
1.  Install Python dependencies: `pandas`, `numpy`, and `matplotlib` (if used for internal checks).
2.  Tableau Workbooks (`.twbx`) can be opened directly using **Tableau Desktop**.
3.  Run the **`Tableau_Python_Cleaning.ipynb`** notebook to generate the cleaned CSV file before connecting it to new Tableau visualizations.
