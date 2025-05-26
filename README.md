Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

🏗️ Data Architecture

In this Data Warehouse project i have preferred to use Medallion structure which contains layers BRONZE, SILVER AND GOLD.

MEDALLION STRUCTURE

![image](https://github.com/user-attachments/assets/eb607def-106f-4b17-8d07-033e3bf95de6)

HIGH LEVEL ARCHITECTURE:

![image](https://github.com/user-attachments/assets/b03970b6-496d-41fa-8dad-0438f051083d)

Details of Each Layer and Its Functionality:
Bronze Layer:
** Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer:
** This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer:
** Houses business-ready data modeled into a star schema required for reporting and analytics.



