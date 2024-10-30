# Customer Churn Data Engineering Project

  This project demonstrates how to build and automate a Python ETL (Extract, Transform, Load) pipeline using AWS Glue to load data from an S3 bucket into an Amazon Redshift data warehouse. The final output is visualized in Power BI, providing insights into customer churn.

## Architecture

----- photo ------

## Project Overview

  In this project, we developed an automated data pipeline using AWS services to analyze customer churn. The pipeline follows these steps:

- Data Ingestion: Data is downloaded from the internet and stored in an Amazon S3 bucket.
- Data Cataloging: AWS Glue Crawler is used to infer the schema and create a data catalog from the raw data stored in S3.
- Data Querying: Amazon Athena is employed to run SQL queries on the data stored in S3, allowing quick insights from the data catalog.
- Data Loading: AWS Glue ETL jobs load the cataloged data into an Amazon Redshift data warehouse.
- Data Visualization: Power BI is connected to the Redshift cluster for visualization and reporting.
- Automation: Apache Airflow is used to orchestrate and automate the entire ETL process.

## Technologies Used

$ Amazon S3: Data storage.
$ AWS Glue: For data cataloging and ETL processing.
$ Amazon Redshift: Data warehousing for querying and analysis.
$ Amazon Athena: Ad-hoc querying and analytics on data stored in S3.
$ Apache Airflow: Workflow automation and orchestration.
$ Power BI: Data visualization.
$ Python: Custom ETL scripts.

## Prerequisites

1) AWS account with permissions to use S3, Glue, Redshift, and Athena.
2) Power BI desktop
3) Apache Airflow via AWS EC2.

## Conclusion
  This project showcases the full cycle of building and automating a cloud-based ETL pipeline for customer churn analysis using AWS Glue, Amazon Redshift, and Power BI.