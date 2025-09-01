Problem Statement

Retail companies like Walmart handle massive volumes of weekly sales data across multiple stores and departments. Understanding sales patterns, especially around holidays, and being able to forecast future sales are critical for inventory management, staffing, and revenue optimization.

The goal of this project is to perform an end-to-end analysis and forecasting of Walmart’s weekly sales data using a mix of tools:

Excel → Initial exploratory analysis, summary statistics, and quick trend checks.

SQL → Query-based analysis for extracting insights (top customers, duplicate orders, sales by month, etc.).

Python → In-depth analysis of holiday impact on sales, store type/size performance, and a simple forecasting model using rolling averages.

Power BI → Interactive dashboard for visual storytelling, combining holiday vs. non-holiday performance, store-level insights, and trend monitoring.

This project combines business intelligence with data analytics to give stakeholders actionable insights and forecasting capability.

# 🛒 Walmart Sales Analysis & Forecasting (End-to-End Project)

This project analyzes Walmart’s historical sales data to study **holiday impacts, store performance, and future sales forecasting**.  
It combines **Excel, SQL, Python, and Power BI** to provide both analytical insights and interactive dashboards.  

---

## 📂 Dataset
- **train.csv** → Weekly sales by store, department, and date.  
- **stores.csv** → Metadata about stores (type and size).  

---

## 🎯 Objectives
1. Perform **exploratory analysis in Excel** for summary statistics and early insights.  
2. Write **SQL queries** for targeted business questions (top customers, duplicate orders, monthly sales trends).  
3. Use **Python (Pandas + Matplotlib)** to:  
   - Compare holiday vs. non-holiday weekly sales.  
   - Analyze sales by holiday type (Thanksgiving, Christmas, etc.).  
   - Study the effect of **store type and store size** on holiday sales.  
   - Build a **rolling average forecasting model** for Store 1’s weekly sales.  
4. Build an **interactive Power BI dashboard** for visualization and reporting.  

---

## 🛠️ Tools & Tech Stack
- **Excel** → Initial data analysis  
- **SQL** → Query-based analysis  
- **Python** → Pandas, Matplotlib (EDA + Forecasting)  
- **Power BI** → Dashboard creation  

---

## 📊 Analysis & Forecasting Steps
### 1. Excel (Initial Analysis)
- Checked for missing values and duplicates.  
- Performed summary statistics and pivot table aggregations.  

### 2. SQL Queries
- Extracted **top customers** by sales.  
- Identified **duplicate orders**.  
- Retrieved **monthly sales reports**.  

### 3. Python Analysis
- **Holiday vs. Non-Holiday Sales**  
  Compared average sales and visualized trends.  

- **Sales by Holiday Type**  
  Thanksgiving showed the highest spikes.  

- **Sales by Store Type & Size**  
  Larger stores and Type A stores outperformed others during holidays.  

- **Forecasting for Store 1**  
  Applied a **4-week rolling average** to predict next week’s sales.  

### 4. Power BI Dashboard
- KPIs: Total sales, holiday vs. non-holiday sales comparison.  

- Slicers for  time period.  
- Visuals:  bar charts (holiday impact, store size analysis).  


<img width="1362" height="658" alt="Screenshot 2025-09-01 090111" src="https://github.com/user-attachments/assets/b725c0e0-6a09-4332-afdf-0e0fee6fbdb9" />

