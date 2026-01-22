---
title: "FUTURE_DS_01 Project"
author: "Edward Mwangi Gatiya"
date: "2026-01-22"
description: "Data science project with dashboards, datasets, and visualizations."
---

# Business Sales Performance Analytics (Power BI)

## 📌 Project Overview
This project focuses on analyzing business sales data to uncover revenue trends, top-selling products, customer behavior, and regional performance.  
The analysis is designed to simulate a real-world business consulting scenario, where insights are translated into **actionable recommendations** for decision-makers.

This project was completed as part of the **Future Interns – Data Science Internship Program**.

---

## 🎯 Business Objectives
The analysis aims to answer the following key business questions:

- Which products generate the most revenue?
- How do sales trends change over time?
- Which regions contribute the most to total revenue?
- What insights can help the business grow faster and more efficiently?

---

## 📂 Dataset Information
- **Dataset:** Online Retail Dataset (Kaggle)
- **Type:** E-commerce transactional data
- **Period Covered:** 2010 – 2011
- **Records:** Invoices, products, quantities, prices, customers, and countries

⚠️ The dataset is provided in **compressed (.zip) format** due to GitHub file size limits.  
Extract the CSV file locally before use.

---

## 🧹 Data Cleaning & Preparation
The following data cleaning steps were performed:

- Removed cancelled transactions (Invoice numbers starting with "C")
- Removed records with negative or zero quantities and prices
- Converted date fields to proper datetime format
- Created calculated fields such as **Revenue**
- Extracted time-based features (Year, Month)

---

## 📊 Key Metrics & KPIs
The dashboard focuses on the following business-critical KPIs:

- **Total Revenue**
- **Total Orders**
- **Total Customers**
- **Total Quantity Sold**
- **Average Order Value (AOV)**

---

## 📈 Dashboard Overview
The Power BI dashboard provides an interactive view of sales performance across time, products, and regions.

### 🔹 Main Dashboard View
![Dashboard Overview](images/dashboard_overview.png)

---

## 🔍 Key Insights
Some of the major insights derived from the analysis include:

- Revenue is highly concentrated in a small number of products, following the Pareto (80/20) principle.
- The United Kingdom contributes the majority of total revenue, indicating geographic concentration.
- Sales show strong seasonal patterns, with noticeable peaks during certain months.
- A relatively small group of customers contributes a significant share of total revenue.

---

## 💡 Business Recommendations
Based on the insights, the following recommendations are proposed:

- Diversify market focus by targeting high-performing non-UK regions.
- Prioritize inventory planning around peak sales periods.
- Leverage top-selling products for bundling and promotional strategies.
- Develop loyalty programs for high-value repeat customers.

---

## 🛠️ Tools & Technologies
- **Power BI** – Data modeling and dashboard creation
- **Microsoft Excel / CSV** – Data source
- **GitHub** – Project documentation and version control

---

## 📁 Repository Structure
```plaintext
FUTURE_DS_01/
├── data/
│   └── online_retail_dataset.zip
├── dashboard/
│   └── sales_dashboard.pbix
├── images/
│   └── dashboard_overview.png
└── README.md
