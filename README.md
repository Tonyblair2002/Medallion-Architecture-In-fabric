# Medallion-Architecture-In-fabric
Building scalable data lakehouse solutions with Microsoft Fabric and Medallion architecture. Turning raw data into actionable Power BI insights

# Microsoft Fabric Medallion Architecture for Analytics

This project was built to transform raw data into stakeholder-ready business insights using Microsoft Fabric. The solution follows a Medallion architecture, where raw data is ingested into the Bronze layer, validated and transformed in the Silver layer, and curated into a Gold layer for semantic modeling and Power BI reporting.

## Project Objectives
- Convert raw operational data into analytics-ready datasets
- Standardize data processing through Bronze, Silver, and Gold layers
- Build reusable semantic models for business reporting
- Deliver stakeholder-ready Power BI dashboards from the Gold layer

## Tech Stack
- Microsoft Fabric
- SQL
- PySpark
- Python
- JSON and CSV files
- Fabric Notebooks
- Data Pipelines
- Semantic Models
- DAX Queries
- Power BI

## Solution Architecture
The platform is organized using a Medallion structure:
- Bronze layer: stores raw ingested data from source files
- Silver layer: applies cleansing, validation, joins, and business transformations
- Gold layer: creates curated, analytics-ready datasets for semantic modeling and reporting

## Outcome
The final solution enables stakeholders to consume consistent, trusted, and report-ready data in Power BI through semantic models and curated Gold-layer datasets.
