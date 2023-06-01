# uber_etl_pipeline
Uber Data Engineering Project

Objective

The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python,
Compute Instance, Mage Data Pipeline Tool, BigQuery, and PowerBI.

1. Extracted data from NYC Trip Record Data website and loaded it into Google Cloud Storage for further processing.
2. Transformed and modeled the data using fact and dimensional data modeling concepts using Python on Jupyter Notebook.
3. Using ETL, I orchestrated the data pipeline on Mage and loaded the transformed data into Google BigQuery.
4. Developed a dashboard on PowerBI.

Architecture

![image](https://github.com/salmah52/uber_etl_pipeline/assets/44398948/ae2afe4b-3484-40f5-aff2-7a7f16d07592)

Files in the following stages:

Step 0: Cleaning and transformation 
Step 1: Storage
Step 2: ETL, Orchestration - Mage extract, transform, export
Step 3: Analytics - SQL script
Step 4: Dashboard

Technology Used
The following technologies are used to build this project:

1. Language: Python, SQL
2. Extraction and transformation: Jupyter Notebook, Google BigQuery
3. Storage: Google Cloud Storage
4. Orchestration: Mage
5. Dashboard: PowerBI


Datasets Used

TLC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations,
trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Here is the dataset used in the video - https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv


Data Modelling

![image](https://github.com/salmah52/uber_etl_pipeline/assets/44398948/7eefea8a-67ba-43d9-833e-64ad9b388649)






