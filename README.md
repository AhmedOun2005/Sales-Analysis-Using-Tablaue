# 📊 Tableau Dashboards Preview

The interactive workbook consists of **three distinct dashboards**, each designed to isolate specific performance dimensions and provide multi-level analytical insights.

---

# 1. 📈 High-Level Overview Dashboard

Provides an executive summary of overall business performance across the complete historical timeline.

## 🔑 KPI Metrics
- Total Sales: **$6.11M**
- Total Unique Orders: **1,856**
- Top Product Line: **Motorcycles**
- Average Unit Price: **$3,523.8**

## 📊 Core Elements
- Product line order distribution (Vintage Cars leading with 607 orders)
- Treemap visualization of total sales by product line
- Deal size segmentation (Small, Medium, Large)
- Historical trend analysis of sales fluctuations

---

# 2. 📉 Temporal Analysis (Analysis by Date)

Focuses on seasonality patterns, monthly performance trends, and revenue variance analysis.

## 📊 Core Elements
- Monthly trend analysis of:
  - Total Sales
  - Order Counts
  - Total MSRP Value
- 12-month comparative time-series visualization
- Seasonal peak detection (Q4 holiday surge)
  - November peak revenue: **$1.29M**

## 📌 Variance Analysis
- Measures difference between actual sales and MSRP
- Highlights discounting behavior and pricing efficiency

---

# 3. 🌍 Geographic Distribution (Location Analysis)

Analyzes performance across regions to identify high-performing markets and operational clusters.

## 📊 Core Elements
- Top 10 revenue-generating cities
  - Madrid leading with **$632K sales**
- Country-level order density comparison
- Interactive world map showing sales and fulfillment clusters
- Geographic performance segmentation

---

# 🛠️ Tech Stack & Architecture

| Layer | Technology |
|------|------------|
| Database Engine | Microsoft SQL Server (T-SQL) |
| BI Tool | Tableau Desktop |
| Data Logic | Subqueries, Window Functions, Aggregations |
| Optimization | Intermediate Tables, Performance Tuning |

---

# 🗄️ Database Architecture & SQL Pipeline

The SQL pipeline follows a structured workflow:
- Data backup and staging
- Business-focused analytical queries
- Performance optimization using intermediate tables
- Schema normalization into relational models

---
