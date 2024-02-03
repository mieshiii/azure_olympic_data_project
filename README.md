# End-to-End Azure Data Engineering Project

## Basic Architecture

The basic architecture of the project is illustrated below:

**Requirements:**
- Azure account (preferably with Free credits to reduce costs)
- Basic knowledge of Python
- Introduction to Cloud Computing
- Introduction to Distributed Computing
- Introduction to Spark (and the Hadoop ecosystem)

Process flow:

1. Raw data is captured from different sources. For this project, the data can be downloaded or scraped directly from Kaggle (Tokyo Olympic Data set).
2. All provisioned services must be housed within an Azure VNet, for security purposes.
3. Raw data is ingested via an HTTP pipeline within Azure Data Factory which is then stored into a Azure Data Lake Gen2.
4. Create connectivity between Vnet and internal Azure Services via Azure App Registrations (Azure Entra).
5. Initial Data processing is done through Azure Databricks and stored on the Data Lake Gen2. 