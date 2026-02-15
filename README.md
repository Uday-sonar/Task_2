# Task_2

# 📊 Super Store Sales Analysis (Power BI)

This project features a comprehensive **Power BI Dashboard** designed to analyze retail performance across different regions, categories, and customer segments. The dashboard transforms raw transactional data into actionable insights regarding profitability, sales trends, and shipping efficiency.

## Table of Contents
- [Objective](#objective)
- [Tech Stack](#tech-stack)
- [Dashboard Components](#dashboard-components)
- [Key Insights](#key-insights)
- [Power BI Features Used](#power-bi-features-used)
- [Outcome](#outcome)

---

## 📌 Objective
The goal of this dashboard is to provide a 360-degree view of the Super Store's operations. It enables stakeholders to track Year-over-Year (YoY) growth, identify high-performing product sub-categories, and visualize geographic sales distribution.

**Key Metrics Tracked:**
* [cite_start]**Total Sales:** $1.57M [cite: 13]
* [cite_start]**Total Profit:** $175.26K [cite: 26]
* [cite_start]**Total Quantity Sold:** 22K units [cite: 14]
* [cite_start]**Average Delivery Time:** 3.93 days [cite: 27]

---

## 🛠 Tech Stack
* **Tool:** Power BI Desktop
* **Data Source:** Super Store Excel/CSV Dataset
* **Visuals:** Map integration, Donut charts, YoY Line/Area charts, and Bar charts

---

## ⚙️ Dashboard Components

### 1. Executive Summary (KPIs)
The top section displays high-level cards for quick reference:
* [cite_start]**Sales:** $1.57M [cite: 13]
* [cite_start]**Quantity:** 22,000 [cite: 14]
* [cite_start]**Profit:** $175,260 [cite: 26]
* [cite_start]**Shipping Average:** 3.93 [cite: 27]

### 2. Temporal Analysis (YoY Trends)
* [cite_start]**Monthly Profits by YoY:** A line chart comparing 2019 and 2020 performance[cite: 18, 19].
* [cite_start]**Monthly Sales by YoY:** An area chart showing seasonal fluctuations in revenue[cite: 44, 45].

### 3. Segmentation & Logistics
* [cite_start]**Sales by Payment Mode:** Breakdown showing **COD** (42.62%), **Online** (35.38%), and **Cards** (21.99%)[cite: 2, 3, 4, 12].
* [cite_start]**Sales by Ship Mode:** Analysis of shipping preferences, with **Standard Class** leading at $0.42M[cite: 62, 63, 68].
* [cite_start]**Sales by Segment:** Consumer (48.09%), Corporate (32.55%), and Home Office (19.35%)[cite: 39, 41, 43, 46].

### 4. Product & Geography
* [cite_start]**Profit and Sales by State:** A geospatial map highlighting regional performance[cite: 21].
* [cite_start]**Sales by Category:** Comparison between Office Supplies ($0.64M), Technology ($0.47M), and Furniture ($0.45M)[cite: 72, 76, 81, 85].
* [cite_start]**Sales by Sub-Category:** Detailed bar chart featuring top items like **Phones** ($0.20M) and **Chairs** ($0.18M)[cite: 73, 77, 79].

---

## 📦 Project Structure
```plaintext
superstore-sales-powerbi/
│
├── Super_Store_Raw_Data.csv    # Raw transactional data
├── Sales_Performance.pbix      # Power BI project file
├── Documentation/              # Metadata and DAX measures
└── README.md                   # Project Overview
