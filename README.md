# 📊 Sales Data Analysis: Azure Databricks Project

[![Databricks](https://img.shields.io/badge/Platform-Azure%20Databricks-orange)](https://www.databricks.com/)
[![SQL](https://img.shields.io/badge/Language-Spark%20SQL-blue)](https://spark.apache.org/sql/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🌟 Project Overview
This project is an end-to-end data engineering and analysis workflow built using **Azure Databricks**. The goal was to transform raw, fragmented sales data into actionable business insights by leveraging the **Medallion Architecture** (Bronze, Silver, Gold) and Spark SQL.

This repository demonstrates my ability to manage cloud data workspaces, implement relational schemas, and sync production-ready code via **Databricks Repos**.

---

## 🛠️ Tech Stack
* **Platform:** [Azure Databricks](https://github.com/parinthaokar/salesDashboard)
* **Engine:** Spark SQL
* **Storage:** Delta Lake (ACID compliant)
* **Version Control:** Git Integration (Databricks Repos)

---

## 🔍 Key Analysis & Business Logic
Using a series of [SQL Queries](https://github.com/parinthaokar/salesDashboard/tree/main/Queries), I addressed the following business requirements:

* **Profitability Analysis:** Calculated net margins by performing relational joins between `FactSales` and `DimProductCost`.
* **Customer Segmentation:** Identified high-value customers based on total spend and order frequency.
* **Demographic Trends:** Analyzed purchasing patterns across different customer age groups to identify target markets.
* **Top Performers:** Ranked products and customers to highlight the top 10 revenue drivers.

---

## 📈 Dashboard Highlights
The [Dashboards](https://github.com/parinthaokar/salesDashboard/tree/main/Dashboards) section visualizes the processed data to show:
* **Core KPIs:** Total Revenue, Total Orders, and Profit Margins.
* **Sales Over Time:** Temporal trends to identify seasonal peaks.
* **Product Performance:** Category-wise breakdown of sales volume.

---

## 💡 Key Learnings
* **Schema Design:** Implemented a Star Schema within a Lakehouse environment.
* **Data Transformation:** Mastered complex joins and aggregations in Spark SQL.
* **Collaboration:** Integrated GitHub into the Databricks workflow for version-controlled development.

---

## 🚀 Getting Started
1.  **Clone the Repo:** Connect your Databricks workspace to this GitHub repository.
2.  **Environment:** Ensure you have an active Databricks cluster (Standard or Personal).
3.  **Data Ingestion:** Upload your sales CSVs to the DBFS (Databricks File System).
4.  **Execution:** Run the notebooks in the `/Queries` folder to generate the Delta tables.
