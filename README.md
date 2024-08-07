# Azure-Data-Ingestion-Project
Learning Data Ingestion Using Azure


This project provides a detailed implementation for ingesting data from a GitHub repository into Azure Data Lake Storage Gen2. It focuses on creating a robust and scalable data pipeline using various Azure services, making it an excellent example of cloud-based data management.

Project Overview:
The primary objective of this project is to automate the extraction of data from GitHub repositories and securely store it in Azure Data Lake Storage Gen2 for further processing and analysis. This setup is ideal for scenarios where regular data updates from source code repositories are required for analysis, reporting, or machine learning applications.

Key Components and Features:

1. Data Source - GitHub Repository 🗃️:
Data Extraction: Utilizes GitHub APIs to extract data, including source code, metadata, issues, pull requests, and other relevant information.
Data Processing: Initial data cleaning and transformation are handled to ensure consistency and usability in the target system.

2. Data Pipeline - Azure Data Factory / Azure Logic Apps ⚙️:
Orchestration: Manages the workflow of data extraction, transformation, and loading (ETL). It can be scheduled to run at regular intervals, ensuring that the data in Azure Data Lake Storage is always up-to-date.
Data Transformation: Uses Azure Data Factory’s mapping data flows or custom scripts to transform data into the desired format.

3. Data Storage - Azure Data Lake Storage Gen2 💾:
Scalable Storage: Provides a secure and scalable storage solution, supporting large-scale data analytics workloads.
Hierarchical Namespace: Organizes data efficiently, allowing for easy navigation and access to files.
Access Control: Implements Azure Active Directory and role-based access control (RBAC) to manage permissions and ensure data security.


Technologies Used:

Azure Data Lake Storage Gen2 💽: For scalable and secure data storage.

Azure Data Factory / Azure Logic Apps 🔧: For orchestrating and automating data workflows.

GitHub APIs 🌐: For extracting data from the GitHub repositories.

Azure Key Vault 🔑: For secure credential management.

Azure Monitor and Log Analytics 📈: For monitoring, logging, and alerting.

Architecture Diagram:

![image](https://github.com/user-attachments/assets/abed4fdd-d887-4cc8-b2bf-992bece4b890)


Visualization and SQL Queries
This data once loaded in Data Lake Storage Gen 2 needs to transformed using SQL and then needs to be visuzalized. 

For this here is the file with SQL Queries:
