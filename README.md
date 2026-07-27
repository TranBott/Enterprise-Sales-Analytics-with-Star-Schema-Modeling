# Enterprise Sales Analytics with Star Schema Modeling

An enterprise-scale Business Intelligence solution built using Power BI. This project focuses on dimensional data modeling, ETL data transformation, and analytical reporting by converting raw operational data into an optimized Star Schema semantic model.

---

## Project Overview

This project transforms a complex dataset of 23 interconnected operational tables into a clean, performance-optimized Star Schema. It establishes centralized business logic, time intelligence capabilities, and role-based data security to support efficient reporting across multiple departments.

---

## Key Features

- **Star Schema Architecture:** Designed a scalable dimensional model using dedicated Fact and Dimension tables.
- **Power Query ETL:** Standardized, cleaned, and transformed raw operational data.
- **DAX Business Logic:** Created reusable measures for core business calculations and time-intelligence analysis.
- **Date Dimension:** Built a centralized calendar table for year-over-year and period-over-period tracking.
- **Row-Level Security (RLS):** Configured role-based access to restrict data visibility securely.

---

## Data Model Structure

### Dimension Tables (Context)
- Dim_Customer
- Dim_Product
- Dim_Date
- Dim_Geography
- Dim_Campaign
- Dim_SalesTarget
- Dim_Flags

### Fact Tables (Metrics)
- Fact_Sales
- Fact_Inventory
- Fact_CampaignSpend
- Fact_PromotionCoverage
- Fact_OrderProcess

---

## Business Insights & Reporting Scope

The data model supports cross-functional analysis across several key operational areas:

- **Sales Performance:** Revenue trends, volume metrics, and sales growth.
- **Inventory Monitoring:** Stock levels, reorder points, and supply tracking.
- **Campaign Effectiveness:** Marketing ROI and promotional channel performance.
- **Customer Analytics:** Regional breakdowns and customer purchasing behavior.
- **Order Tracking:** End-to-end order processing lifecycle monitoring.

---

## Tech Stack & Tools

- Power BI (Desktop & Developer Projects)
- Power Query (ETL)
- DAX (Data Analysis Expressions)
- Microsoft Excel

---

## Project Directory

```text
├── Project.Report/
├── Project.SemanticModel/
└── Enterprise Sales Analytics with Star Schema Modeling.pbip