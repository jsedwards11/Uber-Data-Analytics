# Creating an ETL Pipeline Using Google Cloud Platform, Mage BigQuery and Looker.

## Architecture Diagram

![ETL](https://i0.wp.com/www.theseattledataguy.com/wp-content/uploads/2023/05/architecture.jpg?w=960&ssl=1)


## Key Points and Overview

+ The goal of this project is to create an ETL pipeline extracting Uber data from a CSV, clearing and transforming the data using Python and Mage, loading this data to Google BiqQuery, and visualizing this data in a Looker dashboard. 


## Files

reddit_etl.py: This file contains the Python ETL script for extracting, transforming, and loading data from Reddit API to AWS S3 using s3fs.

reddit_dag.py: This file contains the DAG and task definitions for Airflow.
