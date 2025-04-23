# sql-data-analytics-project
A comprehensive collection of SQL scripts for data exploration, analytics, and reporting. These scripts cover various analyses such as database exploration, measures and metrics, time-based trends, cumulative analytics, segmentation, and more.
This repository contains SQL queries designed to help data analysts and BI professionals quickly explore, segment, and analyze data within a relational database. Each script focuses on a specific analytical theme and demonstrates best practices for SQL queries.

# SQL Data Exploration Project

This project contains a sequence of structured SQL scripts that progressively explore and analyze a relational database. It is intended for educational or analytical purposes and follows a modular structure that builds in complexity over time.

---

## 📁 Project Structure

| File Name                           | Description |
|------------------------------------|-------------|
| `00_init_database.sql`             | Initializes the database schema and loads initial data. |
| `01_database_exploration.sql`      | Explores the general structure and content of the database. |
| `02_dimensions_exploration.sql`    | Analyzes dimensional tables (e.g., products, customers, regions). |
| `03_date_range_exploration.sql`    | Identifies the range and distribution of dates in the dataset. |
| `04_measures_exploration.sql`      | Investigates key measures and their statistical profiles. |
| `05_magnitude_analysis.sql`        | Detects outliers and values of significant magnitude. |
| `06_ranking_analysis.sql`          | Ranks entities (products, customers, etc.) based on KPIs. |
| `07_change_over_time_analysis.sql` | Tracks changes and trends across time periods. |
| `08_cumulative_analysis.sql`       | Cumulative aggregation and running total analysis. |
| `09_performance_analysis.sql`      | Evaluates entity performance using defined metrics. |
| `10_data_segmentation.sql`         | Segments data into logical groups for targeted analysis. |
| `11_part_to_whole_analysis.sql`    | Analyzes relationships between parts and the whole (e.g., category shares). |
| `12_report_customers.sql`          | Creates structured reports focused on customer behavior and value. |
| `13_report_products.sql`           | Produces detailed reports on product performance and contribution. |

---

## 📌 How to Use

1. Clone or download this repository.
2. Set up your SQL environment (PostgreSQL, MySQL, etc.).
3. Run each script in order, starting from `00_init_database.sql` to `13_report_products.sql`.
4. Modify queries as needed to fit your own schema or data needs.

---

## 🛠 Requirements

- SQL-compatible database (PostgreSQL, MySQL, SQLite, etc.)
- SQL editor or client (DBeaver, DataGrip, pgAdmin, etc.)
- Permissions to create and modify database schemas

---

## 🎯 Objectives

- Explore database schema and contents
- Analyze measures and dimensions
- Perform time-based and cumulative analysis
- Segment data and generate analytical reports
- Improve SQL skills and data analysis workflow

---
