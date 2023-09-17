# Uber-ETL-pipeline-Data-Analysis-GCP

This project showcases the handling and transformation of raw Uber data hosted in Google Cloud Storage. The data was modeled into a structured fact table complemented by dimension tables. Utilizing a Mage data pipeline tool operating on a compute instance, extraction, transformation, and loading were seamlessly executed using Python. Once transformed, the data was loaded into a designated dataset, enabling efficient utilization of Google BigQuery for comprehensive analysis and insights through table joins and deep dives into the data. Leveraging the capabilities of BigQuery, valuable analytical outcomes were obtained. To enhance data interpretation and accessibility, the processed data was effectively visualized using Looker Studio, presenting an intuitive representation for informed decision-making.

## Architecture 
<img src="architecture.jpg">

## Technology Used
- Programming Language - Python

Google Cloud Platform
1. Google Storage
2. Compute Instance 
3. BigQuery

Looker Studio

Modern Data Pipeine Tool - https://www.mage.ai/

## Data Model
<img src="data_model.jpeg">
