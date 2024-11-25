# Data Engineering Capstone Project

Final assignment for the course "Data Modeling, Transformation, and Serving" by DeepLearning.AI & AWS on Coursera.

## Project Overview

![capstone_technical_overview](assets/Capstone-diagram2.png)

This project implements an end-to-end data engineering pipeline on AWS Cloud, orchestrated using Apache Airflow. Data is extracted from an API endpoint and an RDS database, then stored in S3 in the Landing Zone. The raw data is transformed using Apache Iceberg within the Transformation Zone and cataloged with AWS Glue. Redshift Spectrum is used for querying data, and quality checks are applied to ensure accuracy. The transformed data is loaded into Amazon Redshift for analytics. Finally, dbt is used for modeling, and Apache Superset provides interactive dashboards for visualization.

## Author(s)

* Joe Reis
* Morgan Willis
* Navnit Shukla
