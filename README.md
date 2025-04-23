# 📊 SQL Data Analytics Project

A comprehensive collection of modular SQL scripts designed for **data exploration, analytics, and business intelligence reporting**. This project simulates a full workflow used by data analysts and BI professionals to understand and generate insights from a **retail-style relational database**.

Each script in this repository focuses on a different analytical objective—starting from schema setup, progressing through measures, dimensions, and time series, and concluding with actionable reporting.

---
## 📦 Dataset Overview: Medallion Architecture

This project follows a **Medallion Architecture**, organizing data into three layers of transformation:

### 🥉 Bronze Layer – Raw Source Data

Raw, unprocessed exports from **CRM and ERP systems**, containing customer, product, pricing, and sales data. These files represent the initial ingestion point and reflect real-world complexity and inconsistency.

---

### 🥈 Silver Layer – Cleaned & Standardized Data

Intermediate datasets created by **cleaning**, **normalizing**, and **joining** Bronze data. These represent a structured and consistent schema, ready for modeling and aggregation.

---

### 🥇 Gold Layer – Analytics-Ready Data

Final, business-ready datasets used in all SQL analyses and reporting scripts. These tables are structured in a **dimensional model** (star schema) and include both base and aggregated data:

| Table Name                  | Source File              | Description |
|----------------------------|--------------------------|-------------|
| `dim_customers`            | `gold.dim_customers.csv` | Clean customer dimension table used for segmentation and reporting |
| `dim_products`             | `gold.dim_products.csv`  | Product dimension table used for performance analysis |
| `fact_sales`               | `gold.fact_sales.csv`    | Core fact table containing transactional sales data |
| `report_customers`         | `gold.report_customers.csv` | Aggregated customer performance metrics |
| `report_products`          | `gold.report_products.csv` | Aggregated product-level insights and KPIs |


---

Each layer reflects a step in the **data refinement process**: from ingestion (Bronze), through transformation (Silver), to final consumption (Gold).


## 🗂️ Project Structure
All SQL queries in this project are executed on the **Gold Layer** datasets — fully cleaned, standardized, and modeled for analytics.
| File Name                           | Description |
|------------------------------------|-------------|
| `00_init_database.sql`             | Initializes the schema and loads initial data. |
| `01_database_exploration.sql`      | Explores the structure and general content of the database. |
| `02_dimensions_exploration.sql`    | Analyzes key dimension tables (customers, products). |
| `03_date_range_exploration.sql`    | Reviews date ranges and distribution of transactions over time. |
| `04_measures_exploration.sql`      | Inspects metrics (e.g., sales amount, quantity) using statistical summaries. |
| `05_magnitude_analysis.sql`        | Highlights outliers or unusually large values. |
| `06_ranking_analysis.sql`          | Ranks top-performing entities based on KPIs. |
| `07_change_over_time_analysis.sql` | Assesses changes across time periods (e.g., YoY, MoM). |
| `08_cumulative_analysis.sql`       | Cumulative aggregations (running totals, growth). |
| `09_performance_analysis.sql`      | Evaluates performance by entity and time. |
| `10_data_segmentation.sql`         | Segments data into clusters or meaningful groups. |
| `11_part_to_whole_analysis.sql`    | Compares parts to whole (e.g., category share). |
| `12_report_customers.sql`          | Structured customer-focused summary report. |
| `13_report_products.sql`           | Product-focused report including sales breakdowns. |

---

## 🚀 Key Outcomes

- Hands-on experience building a retail data warehouse
- Skill development in SQL data exploration, aggregation, and BI reporting
- Business-focused data insights using structured queries

