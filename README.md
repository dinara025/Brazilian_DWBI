# Brazilian_DWBI

A comprehensive data warehousing and business intelligence solution implementing ETL processes, dimensional modeling, SSAS cubes, and Power BI reporting for a Brazilian retail sales analytics scenario.

## 🌟 Project Overview

This project demonstrates a complete **Data Warehousing and Business Intelligence** solution for a fictional retail company. The system processes sales data from multiple sources, transforms it through SSIS packages, loads it into a dimensional data warehouse, creates analytical cubes in SSAS, and delivers insights through Power BI dashboards.

### Key Features:
- **Multi-source ETL pipeline** (CSV, SQL databases)
- **Star schema data warehouse** with slowly changing dimensions
- **SSAS cubes** with hierarchies and measures
- **Power BI reports** with drill-down and interactive features
- **OLAP operations** demonstrated through Excel

## 📂 Dataset Description

We're using an enhanced **Brazilian ecommerce dataset** with:
- 1+ year of transactional data (500,000+ records)
- Multiple product categories and stores
- Customer demographics
- Promotional events calendar

## 🏗 Solution Architecture

```mermaid
graph TD
    A[Source Systems] --> B[ETL Process]
    B --> C[Data Warehouse]
    C --> D[SSAS Cubes]
    D --> E[Power BI Reports]
    D --> F[Excel Analytics]
