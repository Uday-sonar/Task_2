# 📊 Super Store Sales Analysis (Power BI)

This project features a comprehensive **Power BI Dashboard** designed to analyze retail performance across different regions, categories, and customer segments. [cite_start]The dashboard transforms raw transactional data into actionable insights regarding profitability, sales trends, and shipping efficiency. 

## Table of Contents
- [Objective](#objective)
- [Tech Stack](#tech-stack)
- [Dashboard Components](#dashboard-components)
- [Key Insights](#key-insights)
- [Power BI Features Used](#power-bi-features-used)
- [Outcome](#outcome)

---

## 📌 Objective
[cite_start]The goal of this dashboard is to provide a 360-degree view of the Super Store's operations.  [cite_start]It enables stakeholders to track Year-over-Year (YoY) growth, identify high-performing product sub-categories, and visualize geographic sales distribution. [cite: 18, 21, 45, 73]

**Key Metrics Tracked:**
* *Total Sales**: $1.57M 
* **Total Profit**: $175.26K 
* **Total Quantity Sold**: 22K units 
* **Average Delivery Days**: 3.93 

---

## 🛠 Tech Stack
* **Tool**: Power BI Desktop 
* **Data Source**: Super Store Dataset 
* **Visuals**: Map integration, Donut charts, YoY Line/Area charts, and Bar charts 

---

## ⚙️ Dashboard Components

### 1. Executive Summary (KPIs)
The top section displays high-level cards for quick reference:
* **Sales**: $1.57M 
* **Quantity**: 22K 
* **Profit**: $175.26K 
* **Shipping Average**: 3.93 

### 2. Temporal Analysis (YoY Trends)
* **Monthly Profits by YoY**: A line chart comparing performance across months for 2019 and 2020.
* **Monthly Sales by YoY**: An area chart showing seasonal revenue fluctuations.

### 3. Segmentation & Logistics
***Sales by Payment Mode**: Breakdown showing **COD** (42.62%), **Online** (35.38%), and **Cards** (21.99%). 
* **Sales by Ship Mode**: Analysis of shipping preferences, with **Standard Class** leading at $0.42M.
* **Sales by Segment**: **Consumer** (48.09%), **Corporate** (32.55%), and **Home Office** (19.35%). 

### 4. Product & Geography
* **Profit and Sales by State**: A geospatial map highlighting regional performance across North America. 
* **Sales by Category**: Comparison between **Office Supplies** ($0.64M), **Technology** ($0.47M), and **Furniture** ($0.45M).
***Sales by Sub-Category**: Detailed bar chart featuring top items like **Phones** ($0.20M) and **Chairs** ($0.18M).

---

## 📦 Project Structure
```plaintext
superstore-sales-powerbi/
│
├── Super_Store_Raw_Data.csv    # Raw transactional data
├── Sales_Performance.pbix      # Power BI project file
├── Documentation/              # Metadata and DAX measures
└── README.md                   # Project Overview
