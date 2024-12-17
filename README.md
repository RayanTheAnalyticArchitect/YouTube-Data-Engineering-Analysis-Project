# YouTube-Data-Engineering-Analysis-Project
# **YouTube Trending Videos Analysis Project**

## **Overview**
This project focuses on analyzing and processing *YouTube trending video data*. Leveraging *AWS services*, the pipeline ingests, processes, and transforms raw YouTube data into structured insights for *visualization* and *reporting*.

---

## **Project Goals**
1. **Data Ingestion** — Collect raw *JSON* data from the *YouTube API*.
2. **ETL Pipeline** — Transform semi-structured *JSON* data into structured *Parquet* format.
3. **Data Lake** — Use *Amazon S3* for centralized raw and cleansed data storage.
4. **Scalability** — Ensure the solution scales to handle increasing data volumes.
5. **Cloud Integration** — Utilize *AWS services* for reliable and cost-effective data processing.
6. **Reporting** — Build insightful dashboards using *Amazon QuickSight*.

---

## **AWS Services Used**
1. **Amazon S3** — *Store raw and cleansed data*.
2. **AWS Lambda** — *Triggered on data upload* to process JSON files and convert them to Parquet.
3. **AWS Glue** — *Catalog cleansed data* and create metadata.
4. **Amazon Athena** — *Query cleansed data* using SQL for analytics.
5. **Amazon QuickSight** — *Visualize and report insights*.
6. **AWS IAM** — *Manage secure access* to AWS resources.

---

## **Dataset**
- **Source**: [YouTube Trending Videos Dataset on Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)
- **Description**:
   - Contains trending video statistics like *views, likes, dislikes, comments*, etc.
   - Includes region-specific *JSON* category metadata.

---

## **Architecture Workflow**
![Data Architecture](architecture.jpeg)


---



