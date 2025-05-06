## Description
---
* This repo contains projects done which applies principles in data engineering. 

## Projects
Postgres ETL✔️
This project involves data modeling for a hypothetical music startup, Sparkify, using a STAR schema to load data in a way that simplifies querying and helps answer questions from the product owner.

Cassandra ETL ✔️
In the domain of big data, Cassandra facilitates the ingestion of huge volumes of data in a NoSQL system. The project incorporates a query-oriented approach in data ingestion into data tables in Cassandra to solve business questions for a music app.

Web Scraping using Scrapy, MongoDB ETL✔️
Storing semi-structured data in the form of a document is one of the ways to manage it. MongoDB facilitates this, with specific collections storing related documents. Each document contains queryable data fields.
In this project, data is scraped from a book listing site using Scrapy. Details like book price, ratings, and availability are saved in documents within the books collection in MongoDB.

Data Warehousing using AWS Redshift✔️
This project produces a data warehouse in AWS Redshift. A data warehouse offers a stable and consistent base for users to query and respond to various business questions based on requirements.

Data Lake using Spark & AWS S3 ✔️
This project develops a data lake within AWS S3 using Spark.
Why build a data lake? A data lake provides a reliable repository for large amounts of data—unstructured, semi-structured, and structured. In this project, JSON files are ingested, denormalized into fact and dimension tables, and stored in AWS S3 as Parquet files.

Data Pipelining using Airflow ✔️
This project schedules data pipelines to perform ETL from JSON files in S3 to Redshift using Airflow.
Why use Airflow?
Airflow lets you define workflows as code, making them more maintainable, versionable, testable, and collaborative.

Capstone Project ✔️
This project marks the culmination of Udacity's Data Engineering Nanodegree. While Udacity offers a default dataset, I chose to pursue an independent project of my own.
