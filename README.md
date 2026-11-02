# Global Superstore Sales Analytics & Data Engineering Pipeline

An end-to-end data engineering and analytics project built using **Azure Cloud (ADLS Gen2, Databricks)**, **PySpark**, and **Power BI**. This project demonstrates medallion architecture data processing, star schema modeling, and an enterprise-grade dark-themed executive dashboard.

---

## 🏗️ Architecture & Workflow (Medallion Architecture)

* **Bronze Layer (Raw):** Ingested raw transactional CSV data from source into Azure Data Lake Storage (ADLS) Gen2.
* **Silver Layer (Cleaned):** Processed raw data using Python/Pandas in Databricks, removed duplicates, handled missing values, and standardized formatting.
* **Gold Layer (Modelled):** Designed an optimized **Star Schema** consisting of a Fact table (`fact_sales`) and Dimension tables (`dim_customer`, `dim_product`) for high-performance analytics.

---

## 🛠️ Tech Stack

* **Data Engineering & Cloud:** Azure Data Lake Storage (ADLS Gen2), Azure Databricks, PySpark, Python, Git.
* **Data Modeling:** Star Schema (Fact & Dimension Tables).
* **Data Visualization & BI:** Power BI Desktop (Dark Theme UI, Custom Top N Filters, Map Visuals).
* **Security:** Environment variables (`os.getenv`) for secure credential management and GitHub Secret Scanning compliance.

---

## 📊 Power BI Dashboard Highlights

* **Dark-Themed UI:** Designed with a professional dark gradient background and high-contrast KPI cards.
* **Key Metrics:** Total Sales, Order Counts, and YoY trends.
* **Interactive Visuals:** 
  * Sum of Sales by Year
  * Top 5 Customers (`Customer Name`)
  * Top 5 Sub-Categories (`Sub-Category`)
  * Ship Mode Distribution (Donut Chart)
  * Regional Sales Map (`Map Visual` with dark skin)

---

## 🚀 How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/shrivastavaamancs-sys/global-superstore-analytics.git](https://github.com/shrivastavaamancs-sys/global-superstore-analytics.git)