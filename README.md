# Data Warehouse & Analytics Project

Welcome to my Data Warehouse & Analytics Project! 🚀

This portfolio project demonstrates an end-to-end data warehousing and analytics solution, from raw data ingestion and transformation to analytical modeling and business insights.

The project follows modern data engineering practices using SQL, ETL, Medallion Architecture, dimensional modeling, and analytics.

---

# 📖 Project Overview

This project covers four key areas:

Data Architecture — Designing a modern data warehouse using Medallion Architecture.
ETL Pipelines — Extracting, transforming, and loading data from ERP and CRM sources.
Data Modeling — Building analytical fact and dimension tables using a star schema.
Analytics & Reporting — Developing SQL-based analysis to generate actionable business insights.

---

# 🚀 Data Engineering
## Objective

### Build a modern SQL data warehouse that consolidates sales data from multiple source systems and provides a reliable foundation for analytics and reporting.

## Requirements
- **Data Sources**: ERP and CRM systems provided as CSV files.
- **Data Quality**: Identify, cleanse, standardize, and resolve data quality issues.
- **Data Integration**: Combine data from multiple sources into a consistent analytical model.
- **Data Scope**: Focus on the latest available dataset; historical tracking is outside the project scope.
- **Documentation**: Document the data architecture, data flow, data model, and data definitions.

---

# 📊 Analytics & Reporting
Objective

Develop SQL-based analytics to provide insights into:
- Customer Behavior
- Product Performance
- Sales Trends

The analysis focuses on key business metrics and trends to support data-driven decision-making.

For detailed requirements, see docs/requirements.md.

---

# 🏗️ Data Architecture

The project follows a Medallion Architecture consisting of Bronze, Silver, and Gold layers:

### 🥉 Bronze Layer — Raw Data
- Ingests ERP and CRM data from CSV files.
- Stores source data in its original form.
- No transformations are applied.
### 🥈 Silver Layer — Cleaned Data
- Cleans and validates source data.
- Standardizes and normalizes fields.
- Applies data transformations and quality rules.
- Prepares data for analytical modeling.
### 🥇 Gold Layer — Business-Ready Data
- Integrates and transforms business data.
- Applies business logic and aggregations.
- Provides analytical models optimized for reporting and analysis.
- Uses dimensional modeling, including fact and dimension tables.

---

# 📂 Repository Structure
data-warehouse-project/
│
├── datasets/                           # Source ERP and CRM datasets
│
├── docs/                               # Project documentation and diagrams
│   ├── etl.drawio                      # ETL approaches and methods
│   ├── data_architecture.drawio        # Overall data architecture
│   ├── data_catalog.md                 # Data fields and metadata
│   ├── data_flow.drawio                # End-to-end data flow
│   ├── data_models.drawio              # Analytical data models
│   ├── naming-conventions.md           # Naming standards
│
├── scripts/                            # SQL ETL and transformation scripts
│   ├── bronze/                         # Raw data ingestion
│   ├── silver/                         # Data cleansing and transformation
│   ├── gold/                           # Analytical models and business logic
│
├── tests/                              # Data quality and validation scripts
│
├── README.md                           # Project documentation
├── LICENSE                             # MIT License
├── .gitignore                          # Git ignore rules
└── requirements.txt                    # Project dependencies

# 🛡️ License

This project is licensed under the MIT License.

---

# 🌟 About Me

Hi, I'm Jeriel, a BI professional passionate about turning data into clear, meaningful insights and building analytics solutions that are both useful and engaging.
