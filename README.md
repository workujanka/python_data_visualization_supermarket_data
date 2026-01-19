# 🛒 Supermarket Sales Analytics

This repository contains an end‑to‑end exploratory analysis of supermarket transaction data, combining automated data profiling with manually curated visual insights. The project focuses on understanding sales performance, customer behavior, product profitability, and operational patterns across branches and cities.

---

## 📊 Visual Analytics (Core of the Project)

The `images/` directory contains the primary outputs of this project—clear, business‑ready visualizations designed for dashboards, presentations, and decision‑making. Key charts include:

- **Sales_by_Branch.png** — Branch‑level sales comparison  
- **Sales_by_City.png** — City‑level performance insights  
- **Revenue_by_Product_Line.png** — Revenue contribution by product category  
- **Quantity_Sold_by_Product_Line.png** — Units sold across product lines  
- **Profit_by_Product_Line.png** — Profitability distribution  
- **Sales_by_Hour_of_the_Day.png** — Peak shopping hours  
- **Sales_by_Day_of_the_Week.png** — Weekly sales patterns  
- **Sales_by_Month.png** — Monthly sales trends  
- **Average_Spending_by_Customer_Type.png** — Member vs Normal spending  
- **Average_Spending_by_Gender.png** — Gender‑based spending behavior  
- **Product_Line_Preference_by_Customer_Type.png** — Category preferences  
- **Payment_Method_Preference.png** — Payment method usage  
- **Cost_of_Goods_Sold_by_Product_Line.png** — COGS breakdown  

These visuals form the backbone of the analysis and summarize the most actionable insights from the dataset.

---

## 📁 Dataset

**File:** `supermarket_sales.csv`  
The dataset contains over 1,000 transactions with fields such as:

- Branch, City, Product Line  
- Customer Type, Gender  
- Unit Price, Quantity, Tax, Total  
- Date, Time, Payment Method  
- COGS, Gross Income, Rating  

This structure supports both descriptive and diagnostic analytics.

---

## 🧪 Automated Data Profiling

A detailed **YData Profiling report** is included in:

notebooks/supermarket_report_v6.html


This report provides:

- Variable‑level summaries  
- Missing‑value analysis  
- Correlation matrices  
- Distribution plots  
- Interaction and pairwise comparisons  
- Data quality warnings  

It serves as a technical reference for anyone who wants to explore the dataset beyond the curated visualizations.

---

## 🎯 Project Objectives

- Identify high‑performing product lines and regions  
- Understand customer behavior across demographics  
- Analyze time‑based sales patterns for operational planning  
- Explore profitability and cost structures  
- Provide clean, beginner‑friendly visual summaries  

---

## 🧰 Tools & Methods

- Python (Pandas, Matplotlib, Seaborn)  
- YData Profiling for automated EDA  
- Time‑series and categorical breakdowns  
- Visualization‑driven insights  

---

## 📌 Summary

This project blends automated profiling with handcrafted visual analytics to deliver a clear, accessible overview of supermarket sales behavior. The `images/` folder provides ready‑to‑use charts, while the YData profiling report offers deeper technical insight for further exploration.
