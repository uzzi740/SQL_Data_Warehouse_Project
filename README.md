# **SQL_Data_Warehouse_Project**

Welcome to the Data Warehouse and Analytics Project repository! 🚀

This repository showcases a complete data warehousing and analytics solution, covering everything from building a robust data warehouse to extracting meaningful insights. Designed as a portfolio project, it demonstrates industry best practices in data engineering and analytics.

🏛️ **Data Architecture**:

I have selected the Medallion Architecture for this Data Warehouse architecture project which consists of Bronze, Silver and Gold layers.
![Alt Text](https://github.com/uzzi740/SQL_Data_Warehouse_Project/blob/main/docs/Datawarehouseproject.jpg?raw=true)

1. **Bronze Layer**: This layer captures raw, unprocessed data directly from source systems in its original format. The data is ingested from CSV files into a SQL Server database, preserving its integrity for future transformations.
2. **Silver Layer**: Here, data undergoes cleansing, standardization, and normalization to improve consistency and quality. This step ensures that anomalies, duplicates, and errors are removed, making the data reliable for analysis.
3. **Gold Layer**: The final layer contains business-ready data, transformed into a structured format for reporting and decision-making. Using a star schema, it optimizes performance for analytics tools, enabling efficient querying and insights.
