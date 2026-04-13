🌟 About This Project

I am deeply curious about learning new technologies and continuously expanding my skill set. This project is part of my journey to understand the real-world workflow of a Data Engineer.

Using IPL dataset (from 2017 onwards), I explored how data is:

Stored in cloud storage (Amazon S3)
Ingested and processed using Databricks (Python)
Queried and transformed to generate insights

This project is inspired by a YouTube data engineering tutorial, and I implemented it hands-on to strengthen my practical understanding.

🧠 What I Learned
</markdown>
- Working with cloud storage (S3)
- Data ingestion in Databricks notebooks
- Using Python (Pandas / PySpark) for data processing
- Writing queries and transforming raw data into insights
- Understanding the end-to-end data pipeline



<pre>
          ┌────────────────────────────┐
        │   Amazon S3 Bucket         │
        │   (IPL CSV Data - 2017+)   │
        └────────────┬───────────────┘
                     │
                     │  Read via S3 path (s3://...)
                     ▼
        ┌────────────────────────────┐
        │ Databricks Python Notebook │
        │ (Spark / Pandas)           │
        └────────────┬───────────────┘
                     │
                     │ Data Ingestion
                     ▼
        ┌────────────────────────────┐
        │ Data Processing Layer      │
        │ - Cleaning                 │
        │ - Filtering               │
        │ - Aggregations            │
        └────────────┬───────────────┘
                     │
                     ▼
        ┌────────────────────────────┐
        │ Analysis & Querying        │
        │ (SQL / PySpark)            │
        └────────────┬───────────────┘
                     │
                     ▼
        ┌────────────────────────────┐
        │ Output / Insights          │
        │ - Charts                   │
        │ - Tables                   │
        │ - Reports                  │
        └────────────────────────────┘
  
</pre>
