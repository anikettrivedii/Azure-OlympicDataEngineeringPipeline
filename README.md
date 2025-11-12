# Azure-OlympicDataEngineeringPipeline

## 🔍 Project Overview  
This project presents an **end-to-end data engineering and analytics solution** for the Tokyo Olympic Games dataset, built entirely on the Azure Databricks + Azure Data Factory ecosystem.  
It demonstrates how to ingest raw event and athlete data, transform it at scale, store it in a high-performance data warehouse, and generate actionable insights via visualization tools.  
This serves as a practical showcase of cloud-native data engineering best practices and analytics capabilities.

## 🏗 Architecture  
- **Azure Data Factory (ADF):** Orchestrates data ingestion pipelines, moves data from raw storage into processing layers.  
- **Azure Databricks:** Performs distributed data processing (Spark) — cleansing, transforming, aggregating Olympic data.  
- **Azure Storage (Data Lake Gen2):** Raw and processed data storage layers (bronze/silver/gold).  
- **Azure SQL Database / Synapse Analytics:** Hosts cleaned, transformed data for analytics and reporting.  
- **Power BI / Dashboarding:** Generates dynamic visual insights from the transformed dataset.

## 🧰 Technologies Used  
- Azure Data Factory  
- Azure Databricks (Apache Spark, PySpark)  
- Azure Storage – Data Lake Gen2  
- Azure SQL Database / Azure Synapse Analytics  
- Power BI (or equivalent visualization tool)  
- Python, SQL, Spark scripting  
- Medallion architecture (Bronze → Silver → Gold layers)

## 🚀 Getting Started  
### Prerequisites  
- Active Azure subscription (free trial or paid)  
- Provisioned Azure Data Factory instance  
- Azure Databricks workspace with cluster access  
- Azure Storage account (Gen2)  
- Azure SQL Database or Synapse workspace  
- Basic familiarity with Python, PySpark, SQL, and Azure portal  

### Setup & Usage  
1. Clone this repository to your local machine or workspace.  
2. Upload or link to the raw Olympic dataset(s).  
3. In ADF, configure Linked Services and Pipelines for data ingestion (raw → bronze).  
4. In Databricks, launch notebooks to clean and transform data (bronze → silver/gold).  
5. Persist the final structured tables into your SQL/Synapse database for analytics.  
6. Connect Power BI (or other BI tool) to generate dashboards and visuals from the cleaned dataset.  
7. Monitor and schedule pipelines for updated runs if you wish to refresh the dataset periodically.

## 📊 Data Ingestion & Processing Workflow  
- Raw data ingestion via ADF from source(s) (CSV/API) into Azure Storage.  
- Transformation and enrichment in Databricks: deduplication, normalization, join of athlete/team entries, medal counts, gender distribution.  
- Storage in structured tables (e.g., Athletes, Teams, Medals) in Azure SQL/Synapse.  
- Creation of dashboards showing: medal tallies by country, athlete gender trends, sport-wise performance across Games.

## ✅ Outcome & Impact  
This project demonstrates how to build a **scalable, maintainable cloud data pipeline** that transforms large volumes of unstructured or semi-structured sports data into actionable insights. For a recruiter or hiring manager, this showcases your ability to:  
- Design and implement an end-to-end data engineering solution in the cloud  
- Work with modern data architectures (bronze/silver/gold layering)  
- Integrate multiple Azure services (ADF, Databricks, Storage, SQL/Synapse)  
- Produce analytics and visualization that highlight domain insights (sports data in this case)  

## 👤 Author  
@YourUsername (or Baby)  
Freshers Data Analyst / Data Engineer – Portfolio Project  

