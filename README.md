# 💊 Pharmacy Sales & Profitability Analytics  
**DataDNA – Onyx Data Challenge (Jan–Feb 2026)**  

An end-to-end business intelligence project analyzing pharmacy retail performance across multiple European countries.  
The dashboard uncovers **revenue drivers, profitability patterns, and regional performance insights** to support strategic decision-making.

---
## 📸 Dashboard Preview

![Dashboard Preview](<img width="565" height="317" alt="image (16)" src="https://github.com/user-attachments/assets/9944a932-e74e-4a45-80dd-f9338d706a8c" />)

![Dashboard Preview](<img width="557" height="316" alt="image (20)" src="https://github.com/user-attachments/assets/8e107500-acf6-43d8-9593-636c7ad281eb" />
)
![Dashboard Preview](<img width="571" height="319" alt="image (19)" src="https://github.com/user-attachments/assets/eafc44a7-8d59-4cba-874a-48300707c48e" />
)

## 📑 Table of Contents

1. [Project Overview](#project-overview)
2. [Objective](#objective)
3. [Dashboard Overview](#dashboard-overview)
4. [Repository Structure](#repository-structure)
5. [Data Description](#data-description)
6. [Key Insights](#key-insights)
7. [Key Measures & Calculations](#key-measures--calculations)
8. [How to Use](#how-to-use)
9. [Tools & Technologies](#tools--technologies)
10. [Business Value](#business-value)
11. [License](#license)

---

## 📊 Project Overview

This project analyzes daily sales data from a European pharmacy chain to evaluate **sales performance, profit margins, and geographic trends**.

The Power BI report was designed to mirror how executives consume information —  
clear KPIs, quick comparisons, and the ability to drill into performance drivers.

It answers key questions such as:

- How is the business performing overall?
- Which regions and stores drive revenue and profitability?
- What product categories contribute most to margin?

---

## 🎯 Objective

The objective of this project was to build an interactive analytics report that:

- Compares **revenue and profit across countries and regions**
- Identifies **top-performing stores and product categories**
- Tracks **performance trends over time**
- Provides decision-makers with a clear view of business performance

---

## 🖥️ Dashboard Overview

The Power BI report contains **three interactive pages**:

### 1️⃣ Executive Overview
- Revenue, Profit, and Margin KPIs
- Country performance comparison
- Monthly trend analysis

### 2️⃣ Regional & Store Performance
- Revenue and profit by region
- Store-level performance comparison
- Analysis by store size, age, and location

### 3️⃣ Product & Category Insights
- Revenue contribution by category
- Top-performing products and brands
- Profitability analysis by product

---

## 📁 Repository Structure


---

## 🧾 Data Description

The dataset consists of transactional sales records including:

- Transaction date
- Country and region
- Pharmacy/store details
- Product category and brand
- Revenue and profit values

The data model follows a **star schema structure** with fact and dimension tables for efficient analysis.

---

## 🔍 Key Insights

- Germany leads in both revenue and profitability, followed by France, Italy, and Belgium
- Higher revenue is associated with **urban locations, older stores, and mid-sized outlets**
- Prescription, OTC, and Wellness categories drive the majority of total revenue
- Older stores, urban locations, and mid-sized outlets consistently perform better  
- Top revenue-generating product:
  **NeuroMed Corticosteroid Cream 200 mg (Germany)**

---

## 🧮 Key Measures & Calculations

Key DAX measures created for this analysis include:

- **Total Revenue**
- **Total Profit**
- **Profit Margin %**
- **Year-over-Year Growth**
- **Month-over-Month Change**
- **Revenue Contribution by Category**
Some of the main DAX measures used in this report:
## DAX
Total Revenue = SUM(Sales[Revenue])
Revenue Last Month = CALCULATE([Total Revenue], PREVIOUSMONTH(Sales[Date]))
MoM Difference = [Total Revenue] - [Revenue Last Month]
Revenue Margin = DIVIDE([Profit], [Revenue])
These measures enable dynamic filtering and performance tracking across all report pages.

---

## ▶️ How to Use

1. Download the `.pbix` file from the **dashboard** folder
2. Open using **Power BI Desktop**
3. Use slicers and filters to explore the data
4. Hover over visuals to view detailed tooltips

---

## 🛠️ Tools & Technologies

- **Power BI** → Data modeling & visualization  
- **DAX** → Business calculations  
- **Excel / CSV** → Data source  
- **GitHub** → Documentation and version control  

---

## 💼 Business Value

This dashboard demonstrates how analytics can support pharmaceutical retail leaders by:

- Identifying high-performing markets
- Optimizing product mix
- Monitoring profitability trends
- Supporting data-driven expansion strategies

The report is designed to replicate real-world executive reporting workflows.

---

## 📄 License

This project is for **educational and portfolio purposes only** as part of the DataDNA Onyx Data Challenge.


