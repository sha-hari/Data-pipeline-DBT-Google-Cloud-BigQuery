# Data pipeline using Data Build Tool with GCP

## Description: 
Buiding a modern data engineering pipeline to transform and analyze Customer data using Data Build Tool (DBT) Google Cloud Platform

## Technology used:
- Cloud: GCP
- Storage: BigQuery
- ETL: DBT
- Scripts: Python
- Environment: PyCharm

 ## Data source: 
- Customers data from dbt
- Format: csv
  
## Process summary:
- Explored customer orders data with Data Build Tool, and seed a csv export of football stadium data
- Linked the DBT environment with BigQuery using yaml configurations for the project and schema to enable efficient SQL-based data transformations, and setup IAM roles in GCP
- Built a pipeline to manage table and view data structures, and implemented unit tests for data quality
- Setup auto generation of comprehensive project documentation served as a user interface

## Project execution:

### dbt Commands
- pip install dbt-bigquery
- dbt --version
- dbt init DBT-GCP-BigQuery
- dbt debug
- dbt run
- dbt run --full-refresh
- dbt seed
- dbt test
- dbt docs generate
- dbt docs serve --port 8083 (default on port 8080)


## Resources:
- https://docs.getdbt.com/docs/introduction   
    
