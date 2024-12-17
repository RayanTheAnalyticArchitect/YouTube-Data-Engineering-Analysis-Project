# YouTube-Data-Engineering-Analysis-Project
**Overview**

This project focuses on analyzing and processing YouTube trending video data. Leveraging AWS services, the pipeline ingests, processes, and transforms raw YouTube data into structured insights for visualization and reporting.

**Project Goals**

Data Ingestion: Collect raw JSON data from YouTube API.

ETL Pipeline: Transform semi-structured JSON data into structured Parquet format.

Data Lake: Use Amazon S3 for centralized raw and cleansed data storage.

Scalability: Ensure the solution scales to handle increasing data volumes.

Cloud Integration: Utilize AWS services for reliable and cost-effective data processing.

Reporting: Build insightful dashboards using Amazon QuickSight.

**AWS Services Used**

Amazon S3: Store raw and cleansed data.

AWS Lambda: Triggered on data upload to process JSON files and convert them to Parquet.

AWS Glue: Catalog cleansed data and create metadata.

Amazon Athena: Query cleansed data using SQL for analytics.

Amazon QuickSight: Visualize and report insights.

AWS IAM: Manage secure access to AWS resources.


**Dataset**

Source: [YouTube Trending Videos Dataset on Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new/data)

Description: Contains trending video statistics such as views, likes, dislikes, and comments. Each region's data includes JSON categories with video-specific metadata.


**Architecture Workflow**

