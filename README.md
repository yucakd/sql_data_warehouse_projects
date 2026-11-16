# SQL Server Data Warehouse & Analytics Project

Turn raw ERP and CRM data into trusted, analysis-ready insights. This project delivers a modern data warehouse on **SQL Server**, followed by SQL-based analytics and reporting views that answer key business questions.

---

## 🚀 Project Overview

Stakeholders need accurate, consolidated data to make decisions. This project closes the gap between raw operational data and business intelligence in two phases:

1. **Data Engineering**: build a centralized SQL Server data warehouse by ingesting, cleansing, and integrating the ERP and CRM source systems.
2. **Data Analysis & BI**: build SQL analytical views on top of the warehouse to surface actionable insights.

| | |
|---|---|
| **Platform** | SQL Server |
| **Teams** | Data Engineering, Data Analysis |
| **Sources** | ERP and CRM (CSV files) |
| **Scope** | Latest snapshot only (no historization or SCD) |

---

## 🏗️ Part 1: Data Warehouse (Data Engineering)

### Objective
Consolidate sales data from the ERP and CRM systems into a single, high-performance data model that supports analytical reporting and informed decision-making.

### ETL Flow

```
 ERP (CSV) ─┐
            ├──►  Ingest  ──►  Cleanse  ──►  Integrate  ──►  Analytical Model
 CRM (CSV) ─┘     (load)      (fix quality    (combine        (user-friendly,
                                issues)        sources)        query-optimized)
```

### Scope & Specifications

- **Data Sources**: import data from two source systems, ERP and CRM, provided as CSV files.
- **Data Quality & Cleansing**: resolve anomalies, missing values, and other data quality issues before the data is used for analysis.
- **Data Integration**: merge both sources into one unified model designed for fast analytical queries and ease of use.
- **Scope Limitation**: only the latest dataset snapshot is handled. Historization and slowly changing dimensions (SCD) are out of scope for this iteration.
- **Documentation**: the data model schema is documented clearly so that both business stakeholders and analytics teams can understand and use it.

### Deliverables
- ETL scripts for ingestion, cleansing, and integration
- A unified analytical data model
- Data model documentation for business and analytics users

---

## 📊 Part 2: Analytics & Reporting (Data Analysis)

### Objective
Build SQL-based analytics and reporting views that deliver detailed, actionable insights and give stakeholders the metrics they need to guide strategic growth.

### Analytical Focus Areas

| Focus Area | What It Answers |
|---|---|
| **Customer Behavior** | Purchasing patterns, customer segmentation, and lifetime value: who drives revenue? |
| **Product Performance** | Top-selling items, category performance, and inventory turnover: how can the product offering be optimized? |
| **Sales Trends** | Revenue trajectory, seasonal fluctuations, and regional performance over time: where are the future opportunities? |

---

## 🧰 Tech Stack

- **SQL Server** (data warehouse and analytical queries)
- **T-SQL** (ETL, data modelling, reporting views)
- **CSV** (ERP and CRM source files)

---


## ✅ Summary

By the end of this project you will have:

- A centralized SQL Server data warehouse built from ERP and CRM data
- Cleansed, integrated data in a query-optimized analytical model
- Clear schema documentation for all stakeholders
- SQL reporting views covering customer behavior, product performance, and sales trends
