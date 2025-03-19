# Big-Data-Analytics
The research presented in this project is about supply chain operations optimization using big data technologies, based on the 'DataCo SMART SUPPLY CHAIN FOR BIG DATA ANALYSIS' dataset. 
Step1: Environment Setup:
Created an AWS S3 bucket for data storage.
Set up Databricks Community Edition and connected to AWS S3.
Installed MySQL Community Server for storing processed insights.
Installed necessary libraries: pyspark, sqlalchemy, pymysql, matplotlib, seaborn.

##Note: REMEMBER THE ACCESS KEY AND SECRET ACCESS KEY CREDENTIALS OF THE AWS S3 BUCKET
##Note: REMEMBEER THE USERNAME AND PASSWORD MADE DURING THE INSTALLATION OF THE MYSQL SERVER AND WORKBENCH

Step2: Databricks Setup:
Import the my-data-analytics-project.ipynb file into databricks
Run the code

Step3: Mysql Setup
Execute Query1.sql before performing the JDBC Connection of Databricks to MYSQL
Execute Query2.sql after executing Query1.sql
Execute Query3.sql after running the codes for storing the data from Databricks to MYSQL in .ipynb file.

Step4: Export CSV Files
After executing Query3.sql export the data as CSV Files
(top_10_frequent_customers.csv, top_10_product_categories.csv, delivery_performance_analysis.csv)
using export wizard function of MYSQL Workbench

Step5: Data Visualization using Tableau
Open the tableau packaged workbook file(TABLEAU.twbx) in Tableau.
