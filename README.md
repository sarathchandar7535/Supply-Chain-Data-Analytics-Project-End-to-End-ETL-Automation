Project Overview

The goal of this project is to automate the ingestion of operational data, transform it into a structured analytical model, and make it ready for analysis with minimal manual intervention.

The pipeline starts from raw CSV files received via email and ends with a fully populated fact table in a cloud-hosted PostgreSQL database.

🏗️ Architecture & Workflow

1. Data Ingestion

Automated email trigger using n8n

CSV files extracted directly from Gmail attachments

2. Data Transformation

Data type validation and formatting

Date standardization (ISO format)

Basic cleansing to ensure analytics consistency

3. Data Storage

Cloud database built using Supabase (PostgreSQL)

Star-schema style design with fact and dimension tables

Optimized for querying and reporting

4. Data Analysis

Data exploration and validation using Quadratic

SQL-based analysis on structured fact tables

📊 Key Learnings

1. Building automated ETL pipelines using low-code tools

2. Handling real-world data issues (IDs, dates, schema design)

3. Designing analytics-ready fact tables

4. Working with cloud PostgreSQL databases
