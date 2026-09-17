# 🏢 Data Warehouse and Analytics Project

![SQL](https://img.shields.io/badge/SQL-Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a complete, end-to-end **data warehousing and analytics solution** — from designing a modern data architecture to generating actionable business insights. Built as a portfolio project, it highlights industry best practices in **Data Engineering** and **Data Analytics**.

---

## 📑 Table of Contents

- [Data Architecture](#️-data-architecture)
- [Project Overview](#-project-overview)
- [Repository Structure](#-repository-structure)
- [Tools & Resources](#️-tools--resources)
- [Project Requirements](#-project-requirements)
- [Getting Started](#-getting-started)
- [License](#-license)

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture**, organizing data into three layers — **Bronze**, **Silver**, and **Gold**:

| Layer | Description |
|-------|-------------|
| 🥉 **Bronze** | Stores raw data exactly as received from source systems (CSV → SQL Server), with no transformations applied. |
| 🥈 **Silver** | Cleanses, standardizes, and normalizes data to make it analysis-ready. |
| 🥇 **Gold** | Business-ready data, modeled into a **star schema**, optimized for reporting and analytics. |

---

## 📖 Project Overview

This project covers the full data lifecycle:

1. **Data Architecture** — Designing a modern data warehouse using the Bronze, Silver, and Gold layers.
2. **ETL Pipelines** — Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling** — Building fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting** — Writing SQL-based reports and dashboards to generate business insights.

🎯 This repository is a great reference for anyone looking to build skills in:

`SQL Development` · `Data Architecture` · `Data Engineering` · `ETL Development` · `Data Modeling` · `Data Analytics`

---

## 📂 Repository Structure

```
sql-data-warehouse-project/
│
├── Datasets/                  # Raw source data (CRM & ERP CSV files)
│   ├── source_crm/
│   └── source_erp/
│
├── Scripts/                   # SQL scripts organized by layer
│   ├── bronze/                 # Raw data ingestion (DDL + load procedures)
│   ├── silver/                 # Data cleaning & transformation
│   └── gold/                   # Business-ready views (star schema)
│
├── Test/                      # Data quality & validation scripts
│
├── README.md                  # Project overview (this file)
├── requirements.txt           # Tools & setup requirements
└── gitignore.txt              # Ignored files and folders
```

---

## 🛠️ Tools & Resources

Everything used in this project is **free**:

| Tool | Purpose |
|------|---------|
| [SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) | Lightweight database engine to host the warehouse |
| [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms) | GUI for managing and querying the database |
| [Git & GitHub](https://github.com/) | Version control and collaboration |
| [Draw.io](https://www.drawio.com/) | Designing architecture, data flow, and model diagrams |
| [Notion](https://www.notion.com/templates/sql-data-warehouse-project) | Project planning and documentation |

---

## 🚀 Project Requirements

### 📌 Data Engineering — Building the Warehouse

**Objective:** Develop a modern data warehouse using SQL Server to consolidate sales data and enable analytical reporting.

**Specifications:**
- **Data Sources** — Import data from two systems, ERP and CRM, provided as CSV files.
- **Data Quality** — Clean and resolve data quality issues before analysis.
- **Integration** — Combine both sources into a single, user-friendly data model.
- **Scope** — Focus on the latest dataset only; historical tracking is out of scope.
- **Documentation** — Provide clear documentation of the data model for both business and technical stakeholders.

### 📊 Data Analytics — BI & Reporting

**Objective:** Deliver SQL-based analytics that provide insight into:
- Customer Behavior
- Product Performance
- Sales Trends

These insights help stakeholders make informed, data-driven business decisions.

---

## ⚙️ Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/Kar205tik/sql-data-warehouse-project.git
   ```
2. Install the tools listed in [`requirements.txt`](./requirements.txt).
3. Run the scripts in order: `Scripts/bronze` → `Scripts/silver` → `Scripts/gold`.
4. Run the checks in the `Test/` folder to validate data quality.

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use and adapt it for learning or portfolio purposes.

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
