# Pharmacy-Sales-Profitability-Intelligence-Report
This repository contains a **Power BI report** analyzing daily sales data from a European pharmacy chain.   The goal was to uncover revenue, margin, and geographic performance trends, providing actionable insights for strategic decision-making in pharmaceutical retail.

# Pharmacy Sales & Profitability Analytics

**January–February 2026 | DataDNA – Onyx Data Challenge**  

This repository contains a **Power BI report** analyzing daily sales data from a European pharmacy chain.  
The goal was to uncover revenue, margin, and geographic performance trends, providing actionable insights for strategic decision-making in pharmaceutical retail.

---

## 🏆 Objective

- Analyze revenue, profit, and margin trends across multiple countries, regions, and pharmacies  
- Understand which product categories and brands drive results  
- Identify high-performing and underperforming outlets for operational optimization  
- Support leadership with a clear, interactive dashboard for strategic decisions

---

## 📁 Repository Contents
---

## 📊 Dashboard Overview

The report is a **3-page Power BI dashboard** that includes:

1. **Overview Page**  
   - High-level revenue and profit comparison  
   - Key KPIs for quick decision-making

2. **Regional Performance Page**  
   - Country and store-level analysis  
   - Comparison of revenue, margin, and trend performance  

3. **Product Insights Page**  
   - Top-performing products, categories, and brands  
   - Contribution to revenue and profitability
   - 
---

## 🔍 Key Insights

- Germany leads in both revenue and profitability, followed by France, Italy, and Belgium  
- Older stores, urban locations, and mid-sized outlets consistently perform better  
- Prescription, OTC, and Wellness categories drive the largest share of total revenue  
- Top revenue-generating product: **NeuroMed Corticosteroid Cream 200mg (Germany)**  

---

## 🧮 Key Measures & Calculations

Some of the main DAX measures used in this report:

```DAX
Total Revenue = SUM(Sales[Revenue])
Revenue Last Month = CALCULATE([Total Revenue], PREVIOUSMONTH(Sales[Date]))
MoM Difference = [Total Revenue] - [Revenue Last Month]
Revenue Margin = DIVIDE([Profit], [Revenue])


