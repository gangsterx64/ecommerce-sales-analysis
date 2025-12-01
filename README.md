# 🧠 E-Commerce Sales Analytics Dashboard
### Business Performance Insights using Python + Power BI

This project analyzes real-world e-commerce sales data to uncover **what drives revenue growth** and provide **actionable business insights**.

It includes **data cleaning, KPI analysis, visualizations, and dashboard design**, making it an ideal portfolio project for **Data Analyst / Business Analyst / Financial Analyst** roles.

---

## 📌 1. Project Overview

The goal of this project is to answer key business questions:

⭐ **Which products generate the highest revenue?**  
🛒 **Who are the top customers contributing most to sales?**  
📅 **How is monthly revenue trending over time?**  
🏷️ **Which categories (if available) yield the best margins?**  
🔁 **What is the repeat purchase / retention pattern?**

This is a **non-ML, business intelligence–focused** project.

---

## 🧼 2. Data Cleaning & Preparation

The dataset contains transaction-level sales records.

### Cleaning steps include:

- Removing missing **CustomerID** and **Description**
- Fixing inconsistent text fields
- Converting **InvoiceDate** to datetime
- Creating derived metrics:


## 📊 3. KPIs Analyzed

### 🔝 Top 10 Products by Revenue
![top 10 product by revenue](top_product.png)

### 🧑‍🤝‍🧑 Top 10 Customers
![Top 10 Customers](top_customers.png)

### 📅 Monthly Revenue Trend
Spot seasonality & revenue cycles.
![Monthly Revenue](monthly_revenue.png)

### 💰 Profit Margin (If category / cost available)
Profit Margin is 40%

### 🔁 Retention Indicator
Returning Customers is 98.34%.

---

## 📉 4. Visualizations (Python)

The analysis script generates:

- **Monthly Revenue Trend** (line chart)
- **Top 10 Products** (bar chart)
- **Top 10 Customers** (bar chart)

Outputs are saved inside the `/visuals` folder.

---

## 📈 5. Power BI Dashboard

The dashboard includes:

- Executive Summary  
- Sales Performance Overview  
- Product Insights  
- Customer Insights  
- Time-Series Revenue View  

A clean custom background/theme is recommended for a professional look.

---

## 📁 6. Project Structure

Business Performance Dashboard (E-Commerce Sales Analytics)/
│
├── data/
│   └── data.csv                  # The raw dataset used for the analysis   
│   └── cleaned_Data              # Output: Top customer ranking
│
├── notebook/
│   └── Data_Cleaning.py          # Python code for data cleaning and initial visualization
│
├── Power Bi/
│   └── main_01.pbix              # Power BI Dashboard
│
├── visuals/
│   ├── monthly_revenue.png       # Output: Time-series revenue chart
│   ├── top_products.png          # Output: Top SKU ranking
│   └── top_customers.png         # Output: Top customer ranking
│
└── README.md                     # This documentation file

│
├── analysis_summary/                   
│   └── summary.txt                     # Short written analysis
│
└── README.md                           # Project documentation
