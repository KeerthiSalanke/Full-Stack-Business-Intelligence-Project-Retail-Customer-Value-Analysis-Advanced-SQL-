This project implements a complete, end-to-end data pipeline on the Microsoft Azure platform, demonstrating proficiency in modern ETL/ELT development and data governance. The primary goal was to take scattered retail data from multiple sources (database and API) and transform it into a single, reliable source for business intelligence.

Architecture & Data Flow
The solution utilizes a Medallion Architecture built on top of Azure Data Lake Storage (ADLS) Gen2 and orchestrated by key Azure services. | Phase | Core Azure Tools Used | Functionality & Key Concepts | | :--- | :--- | :--- | | 1. Data Sources | Azure SQL DB, REST API (JSON) | Ingestion of Transactional Data (SQL) and Customer Data (API). | | 2. Ingestion & Storage | Azure Data Factory (ADF), ADLS Gen2 | ADF orchestrates the pipeline, moving raw, multi-source data into the Bronze Layer of the Data Lake. | | 3. Processing & Curation | Azure Databricks (Spark) | Cleansing, transformation, and creation of the Silver and Gold layers. Advanced SQL analytics (Window Functions, CTEs) are used here. | | 4. Visualization & Insight | Power BI | Connects to the Gold Layer to deliver interactive dashboards. |


Key Technical Skills Demonstrated
This project showcases expertise across the data lifecycle, including both ETL/ELT and analytical skills:

Cloud Data Integration: Designing automated pipelines using Azure Data Factory (ADF).

Data Lake Governance: Implementing the Medallion Architecture (Bronze, Silver, Gold) to ensure data quality and lineage in ADLS Gen2.

Big Data Transformation: Utilizing Azure Databricks/Spark for scalable data cleansing and aggregation.


Advanced Analytics: Performing complex analysis (like Cumulative Analysis, Change-Over-Time Trends, Performance Analysis) using advanced SQL techniques (Window Functions, CTEs).



Business Intelligence: Providing final, curated data optimized for and consumed by Power BI.

3. Project Outcomes
Centralized Data Repository: Established a single source of truth (ADLS Gen2) by consolidating data from disparate sources (SQL DB and API).

Data Reliability: Enforced strict data quality rules through the Silver and Gold layers, making the data business-ready and curated.

Actionable Insights: Delivered Interactive Dashboards in Power BI, providing clear Sales Trends and Customer Metrics for decision-making.

Cloud Transition: Successfully demonstrated the ability to transition from legacy ETL (SSIS) to modern, scalable cloud data engineering practices.
