# End-to-End SaaS Churn & Retention Analytics Project

An end-to-end data analytics project that cleans raw user logs, queries core SaaS metrics, and builds an executive Tableau dashboard to mitigate customer churn.

---

## Project Pipeline & Tech Stack

### 1. Data Preprocessing & Cleaning (`Python`)
* Used **Python (Pandas)** to clean, handle missing values, and normalize raw activity and subscription log data.
* Standardized date/time formats and prepared structured tables for SQL database loading.

### 2. Business Logic & Data Aggregation (`SQL`)
* Built production-grade **PostgreSQL** queries using **CTEs**, **Window Functions** (`SUM() OVER`, `ROW_NUMBER()`), and **Aggregate Joins**.
* Calculated key SaaS business metrics: Monthly Recurring Revenue (MRR), Churn Rate, and Support Ticket Escalation trends.

### 3. Interactive Visualization (`Tableau`)
* Designed an executive Tableau dashboard featuring Action Filters and Parameter Controls.
* Prioritized **$21.2M in At-Risk MRR** for customer success outreach and identified Support Issues ($13.0M) as the primary churn driver.

---

## Dashboard Link & Visuals
**Interactive Tableau Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/seonhye.yun/viz/Saassubscriptionandchurn/1)

---

## Repository Structure
* `01_data_cleaning.py`: Python script for raw data cleaning & preprocessing
* `02_churn_metrics.sql`: SQL queries for metric aggregation and business logic
* `03_data_visualization.tbl`: Tableu for dashboard and data visualization
