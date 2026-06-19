# -AWS_S3-ADF-AzureSQL-project

Pipeline to connect Amazon S3 to ADF

Project Overview
This project demonstrates an end-to-end data pipeline that ingests JSON files from AWS S3, stages them in Azure Data Lake Storage Gen2, and loads the data into Azure SQL Database using Azure Data Factory.
The project focuses on cross-cloud data movement, ADF orchestration, event-based triggering, and secure credential handling through Azure Key Vault.

Technologies Used
Azure Data Factory
AWS S3
Azure Data Lake Storage Gen2
Azure SQL Database
Azure Key Vault
JSON
GitHub


Repository Structure
adf/
├── datasets/
├── factory/
├── linkedServices/
├── pipelines/
└── triggers/


Security Note
Sensitive values such as access keys, SQL credentials, storage account names, resource IDs, and Key Vault details have been redacted for public GitHub visibility.
