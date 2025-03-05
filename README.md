
# Azure Ecommerce Data Engineering Project

This project implements a modern data engineering pipeline using Azure Data Factory, Azure Databricks, ADLS Gen2, Synapse Analytics, and MongoDB to ingest, transform, and visualize data from multiple sources.


## 🛠 Skills
Azure Data Factory (ETL orchestration),
Azure Data Lake Storage (ADLS Gen2) (storage for raw and processed data),
Azure Databricks (Spark-based transformations),
MongoDB (reference data for enrichment),
Azure Synapse Analytics (data warehousing and analytics),
Looker (visualization)


## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?


## Optimizations

✔ Automated Data Ingestion – Scheduled ingestion pipelines using Azure Data Factory

✔ Scalable & Distributed Processing – Spark-based transformations in Azure Databricks

✔ Data Enrichment – Uses MongoDB for external reference tables

✔ Cloud Storage – Secure storage with ADLS Gen2

✔ Data Warehousing & Querying – Optimized analytics in Azure Synapse

✔ Interactive Visualizations – Connects with Power BI / Tableau for insights


## Roadmap

Step 1: Configure Azure Data Factory (ADF)
Create Linked Services for data sources (APIs, SQL databases)
Build and schedule pipelines to extract and store raw data in ADLS Gen2

Step 2: Set Up Azure Databricks for Transformation
Create a Databricks cluster with Apache Spark
Develop PySpark notebooks for data transformation
Integrate MongoDB for data enrichment
Store processed data back to ADLS Gen2

Step 3: Load Data into Synapse Analytics
Create Synapse tables for structured storage
Load transformed data from ADLS Gen2 to Synapse

Step 4: Visualization & Reporting
Connect Power BI or Tableau to Synapse
Design dashboards for data visualization

