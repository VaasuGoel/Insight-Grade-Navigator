# Insight-Grade-Navigator
This project implements a comprehensive data analysis solution using Azure Data Lake Storage, Azure Data Factory, and Power BI to integrate, process, and visualize student marks data. The goal is to provide actionable insights into academic performance through efficient data handling and insightful visualizations.

## Project Overview:
This repository contains documentation showcasing the implementation of Azure Data Lake Storage (ADLS) Gen2, a data analysis pipeline for student marks, Azure Synapse, and Power BI dashboards designed to provide insights into academic performance. The project demonstrates end-to-end data processing, integration, and visualization using Azure technologies and Power BI.

## Key Components:
### Data Files:
Contains sample datasets representing student marks and performance records.

### Azure Data Factory (ADF) Data Flow:
Includes configurations for integrating and transforming marks data from various sources stored in Azure Data Lake Storage.

### Synapse SQL Pool Integration:
Scripts and configurations for loading transformed marks data into an Azure Synapse SQL pool for efficient querying and analysis.

### Power BI Reports:
Power BI report files that showcase interactive visualizations and insights derived from the processed marks data, enabling detailed analysis of student performance.

## Technologies Used:
Azure Data Lake Storage (ADLS) Gen2, Azure Data Factory (ADF), Azure Synapse Analytics, Power BI.

## Process:
1.Prepare Sample Data Files:
Create and format sample CSV files representing student marks, including fields such as student ID, subject, marks obtained, and date of assessment.

2.Upload Data to Azure Data Lake Storage (ADLS) Gen2:
Log into your Azure account and navigate to the Azure Data Lake Storage service.
Create a container and upload the sample CSV files containing the student marks data.

3.Configure Azure Data Factory (ADF):
Set up an Azure Data Factory instance in your Azure portal.
Create a data pipeline to ingest the data from the ADLS Gen2 container.
Use data flow configurations to transform the raw marks data (e.g., aggregating marks, cleaning data, and filtering irrelevant records).

4.Load Transformed Data into Azure Synapse SQL Pool:
Set up an Azure Synapse Analytics workspace and create a dedicated SQL pool for storage.
Create scripts in ADF to sink the transformed data into the Synapse SQL pool for efficient querying and analysis.

5.Create Power BI Reports:
Open Power BI Desktop and connect to the Azure Synapse SQL pool as a data source.
Import the transformed marks data into Power BI.
Develop interactive reports and dashboards that visualize insights, such as average marks per subject, performance trends over time, and comparisons between different student cohorts.
