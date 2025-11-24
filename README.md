# BMW Sales & Performance Dashboard – Power BI Project

## 📌 Project Overview

This project focuses on building an interactive Power BI dashboard to analyze BMW’s global sales performance, revenue trends, customer insights, and model-wise performance. The goal is to support data-driven decision-making with clear visual KPIs.

# 📂 Project Steps

# 1️⃣ Data Collection

  * Gathered BMW sales, revenue, product, and customer datasets.

  * Included fields like model, region, sales units, revenue, customer segment, and date.


# 2️⃣ Data Cleaning & Preparation (Power Query)

  * Removed duplicates and null values.

  * Standardized model names and region fields.

  * Created a date table for time-intelligence analysis.

  * Performed data type corrections and column splitting.


# 3️⃣ Data Modeling

### Built a star schema with:

  * Fact table: Sales_Fact

  * Dimension tables: Date, Region, Product, Customer

### Created relationships using keys (ModelID, CustomerID, DateID).

### Ensured proper one-to-many relationships for clean reporting.


# 4️⃣ DAX Measures Creation

### Key measures developed:

  * Total Sales Units

  * Total Revenue

  * Average Revenue per Model

  * YoY Growth %

  * Top/Bottom Selling Models

  * Region-wise Sales Comparison


# 5️⃣ Dashboard Design

### Designed multiple report pages:

  * Executive KPI Summary

  * Model Performance Page (Top models, trend lines, comparisons)

  * Region Performance Page (Map visuals, region trends)

  * Customer Insights Page (Segments, buying patterns)

### Used advanced visuals:

  * Line charts, bar charts, clustered bars

  * Matrix table

  * Slicers for interactive filtering

  * Map visual for global view


# 6️⃣ Insights Delivered

  * Identified top-selling BMW models and low-performing models.

  * Highlighted high-revenue regions and seasonal trends.

  * Showed customer patterns by segment and region.

  * Helped in forecasting and performance tracking.

# 7️⃣ Final Output

### A dynamic, interactive Power BI dashboard enabling:

  * Real-time insights

  * Drill-through and cross-filtering

  * Clear KPIs for leadership teams
