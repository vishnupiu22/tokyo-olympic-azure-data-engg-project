# tokyo-olympic-azure-data-engg-project
Tokyo Olympics Data Engineering Project on Azure

Overview

This project involves building an end-to-end ELT pipeline for processing and analyzing the Tokyo Olympics dataset using Azure cloud services. The pipeline integrates data from multiple sources, transforms it, and stores it in a structured format for analysis.

Technologies Used

Azure Data Factory – Ingesting raw data

Azure Data Lake Storage Gen2 – Storing raw and transformed data

Azure Databricks – Data transformation and cleansing

Azure Synapse Analytics – Querying and analyzing transformed data

Data Sources

The project utilizes the following datasets:

Athletes.csv – Contains athlete details

Coaches.csv – Information about coaches

EntriesGender.csv – Event participation data by gender

Medals.csv – Medal statistics for countries and events

Teams.csv – Team compositions and details

Data Processing Pipeline

1. Data Ingestion

Raw datasets were uploaded to Azure Data Lake Storage Gen2.

Azure Data Factory was used to automate data ingestion.

2. Data Transformation ###only some of the transformations are showed in the files.

Azure Databricks was used for data cleaning, filtering, and transformation.

Key transformations included:

Cleaning and standardizing inconsistent values.

Joining datasets to create enriched data tables.

Calculating aggregated statistics (e.g., average entries per gender per discipline).

3. Data Storage & Analysis

Transformed data was stored in Azure Data Lake Storage Gen2.

Azure Synapse Analytics was used for querying and analysis.

Data was explored using SQL queries (e.g., calculating average participation by gender per discipline).

The transformed data was analyzed in Synapse, but no full dashboard was created.

Key Learnings

Leveraging Azure Data Factory for automating ETL workflows.

Using Databricks for large-scale data transformation.

Querying data efficiently in Azure Synapse Analytics.

Understanding event participation trends through structured analysis.

This project demonstrates a complete ELT workflow for handling large-scale sports data in the cloud.


