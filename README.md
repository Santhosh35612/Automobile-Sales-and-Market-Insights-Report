# 🚗 Automobile Sales & Market Insights Report: Market Strategy & Risk Mitigation 📈

## Project Overview

### Problem Statement
Following a significant sales peak in 2004, the company faced a sharp decline and high revenue dependency on a small customer base and limited geographic market (primarily the US). The core problem was to conduct a comprehensive analysis of the **\$10M+ sales data** to **diagnose the decline**, quantify **market concentration risk**, and develop actionable strategies for sustainable growth and recovery.

### Objective
To execute a full-spectrum sales analysis—covering product performance, pricing elasticity, and customer segmentation—to provide executive management with data-driven recommendations on optimizing discount strategy, diversifying the customer base, and guiding necessary stock management improvements.

---

## Data & Analysis Methodology 💻

### The Dataset
The analysis is based on the **`DS1_C6_S6_Sales_Data.csv`**, a detailed transaction-level record from 2003–2005. Key features were instrumental in driving the analysis:

| Feature Category | Key Columns Used | Purpose |
| :--- | :--- | :--- |
| **Financial & Profitability** | `SALES`, `PRICEEACH`, `DEALSIZE` | Modeling pricing elasticity and identifying the most profitable deal structures. |
| **Product Performance** | `PRODUCTLINE`, `PRODUCTCODE` | Quantifying revenue contribution and market share for high-value product lines. |
| **Market Risk** | `COUNTRY`, `CUSTOMERNAME`, `TERRITORY` | Assessing geographic and customer concentration risk and identifying growth territories. |

### Analytical Techniques Applied

1.  **Data Cleaning & Engineering (Python):** Utilized the **`Tableau_Python_Cleaning.ipynb`** notebook with **Pandas** to perform ETL, which included data type conversions, handling missing values, and validating data integrity to create the clean dataset (`Sales_Dataset_Tableau(cleaned).csv`).
2.  **Time-Series & Trend Analysis:** Focused on date and time features to track sales performance, successfully identifying the peak sales period and forecasting recovery trends.
3.  **Product Contribution & Segmentation:** Segmented sales by `PRODUCTLINE` to quantify the revenue dominance of **Classic and Vintage Cars**.
4.  **Business Intelligence (BI) Development:** Developed **six interactive Tableau Dashboards** (in `Project 1.twbx` and `Project 2.twbx`) covering Sales, Forecasting, Pricing, and KPIs, providing a dynamic executive reporting tool. 📊

---

## Key Findings & Strategic Impact 💡

The analysis delivered specific, high-value insights directly tied to business strategy:

### Quantitative Insight Summary

| Insight Category | Key Finding | Strategic Implication |
| :--- | :--- | :--- |
| **Revenue Drivers** | **Classic/Vintage Cars** account for $\approx 60\%$ of total sales. 💰 | Prioritize stock and operational support for these high-margin product lines. |
| **Sales Performance** | Sales peaked at **\$3.91M in 2004** ($\approx 35\%$ YOY growth). | Focus recovery efforts on replicating successful strategies from the peak period. |
| **Pricing Optimization** | **$10-15\%$ discounts** yield the optimal balance of volume and profitability. | Standardize promotional strategies around this proven discount range. |
| **Market Concentration** | Heavy reliance on the **US market** and one top customer ($\approx 9\%$ revenue). | Urgently diversify the customer base and expand aggressively into European markets. 🌎 |

### Executive Recommendations
* **Diversify Risk:** Implement strategies to reduce dependency on top customers and expand geographic footprint to reduce concentration risk.
* **Optimize Promotions:** Standardize the optimal discount structure to maximize both sales and margin simultaneously.
* **Improve Operations:** Prioritize **stock management** and fulfillment efficiency for the core product lines to capitalize on demand.

---

## Technical Stack & Repository Files 🛠️📁

| File Name | Tool / Technology | Description |
| :--- | :--- | :--- |
| `Tableau_Python_Cleaning.ipynb` | Python (Pandas, NumPy) 🐍 | Full ETL script for data cleaning, validation, and feature engineering. |
| `DS1_C6_S6_Sales_Data.csv` | Raw Source Data | The original, unfiltered sales transaction dataset (2003-2005). |
| `Project 1.twbx`/`Project 2.twbx` | Tableau Workbooks | Contains all **6 interactive executive dashboards** and final visualizations. |
| `Automobile-Sales-and-Market-Insights-Report.pptx` | PowerPoint | The final presentation slide deck summarizing all key findings and executive recommendations. 🎤 |
