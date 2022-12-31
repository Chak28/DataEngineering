## Description
---
* This repo contains projects done which applies principles in data engineering. 


## Projects
---
1. <ins> Web Scrapying using Scrapy, MongoDB ETL </ins> :heavy_check_mark:
* In storing semi-structured data, one form to store it in, is in the form of documents. MongoDB makes this possible, with a specific collection containing related documents. Each document contains fields of data which can be queried. 
* In this project, data is scraped from a books listing website using Scrapy. The fields of each book, such as price of a book, ratings, whether it is available is stored in a document in the books collection in MongoDB.

2. <ins> Pipelining with Airflow </ins> :heavy_check_mark:
* This project schedules data pipelines, to perform ETL from json files in S3 to Redshift using Airflow. 
* Why use Airflow? Airflow allows workflows to be defined as code, they become more maintainable, versionable, testable, and collaborative
