
# Blinkit Sales Analysis Dashboard 

## Project Summary

Analysis of Blinkit sales data to evaluate overall performance, customer preferences, outlet trends, and product-level insights using SQL and Power BI.

---

## Overview

This project focuses on analyzing Blinkit’s sales data to understand revenue distribution, item performance, outlet characteristics, and customer ratings. The analysis includes data cleaning using SQL, KPI calculation, and the creation of an interactive Power BI dashboard for business insights.

---

## Problem Statement

Blinkit operates across multiple outlets, item categories, and customer segments. Raw transactional data does not clearly highlight sales drivers or performance gaps. This project aims to analyze and visualize Blinkit sales data to support data-driven decision-making related to products, outlets, and customer preferences.

---

## Dataset

* Blinkit sales dataset (CSV format)
* Includes:

  * Item details and item type
  * Item fat content
  * Total sales
  * Outlet size, type, and location
  * Outlet establishment year
  * Item ratings and visibility

---

## Files & Directories

* **blinkit_data.csv** → Raw and cleaned dataset
* **Blinkit Analysis Dashboard.pbix** → Power BI dashboard file
* **README.md** → Project documentation

---

## Tools & Technologies

* **SQL** – Data cleaning, transformation, and KPI calculation
* **Power BI** – Dashboard creation and visualization

---

## Data Analysis Approach

### Data Cleaning (SQL)

* Standardized `Item_Fat_Content` values (LF, low fat → Low Fat; reg → Regular)
* Ensured consistency for accurate aggregation and reporting

### KPI Analysis (SQL)

Calculated key business metrics:

* Total sales
* Average sales
* Number of items sold
* Average customer rating

### Sales Analysis (SQL & Power BI)

* Total sales by item fat content
* Total sales by item type
* Sales distribution by outlet location
* Sales by outlet establishment year
* Percentage contribution of sales by outlet size
* Performance metrics by outlet type

---

## Key Insights

* Low Fat items contribute a significant portion of total sales
* Certain item types generate consistently higher revenue
* Medium and Large outlets contribute the highest sales share
* Older outlets show stable sales performance over time
* Tier-wise outlet locations show noticeable differences in sales
* Average customer ratings remain consistent across outlet types

---

## Dashboard / Output

An interactive Power BI dashboard presenting:

* Overall sales KPIs
* Sales by item type and fat content
* Outlet size and location performance
* Sales trends by establishment year
* Outlet-wise performance comparison

---

## How to Run the Project

1. Open the Blinkit dataset (`.csv`) in any SQL environment
2. Execute the provided SQL queries for data cleaning and KPI generation
3. Open the Power BI file (`.pbix`) in Power BI Desktop
4. Refresh the data and explore the interactive dashboard

---

## Results & Conclusion

This project demonstrates how retail sales data can be transformed into actionable insights through structured SQL analysis and interactive dashboards. It highlights key sales drivers across products and outlets, supporting better business and inventory decisions.

---

## Future Work

* Add time-series sales forecasting
* Perform customer segmentation analysis
* Integrate real-time data refresh
* Add profitability analysis at item level

---

## Author & Contact

**Ujwal Katre**
📧 Email: [ujwalkatre2004@gmail.com](mailto:ujwalkatre2004@gmail.com)
🔗 GitHub: [https://github.com/katreujwal2004](https://github.com/katreujwal2004)

---

