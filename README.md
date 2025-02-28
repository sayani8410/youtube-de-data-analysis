# Data Engineering YouTube Analysis Project
The YouTube Data Analysis project aims to securely manage, streamline and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

# Dataset used
The Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

# Services used 
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. Amazon QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

# Description
The Project designed a data pipeline that processed 100GB+ YouTube video records, implementing AWS Lambda to convert raw JSON data into optimised parquet format, reducing storage costs by 60% and improving query performance. The AWS Glue ETL jobs are developed to clean, transform and load the data into S3. Generated automated workflows with AWS Lambda, ensuring real time processing of new data and eliminating 90% of manual intervention. Utilized Amazon Athena for querying and analyzing processed data, improving insights into video categories and trending metrics. Amazon QuickSight created interactive dashboards. This enabled real-time trend analysis on video categories, engagement metrics, and regional performance.
