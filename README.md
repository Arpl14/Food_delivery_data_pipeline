# Food Delivery Data Pipeline on GCP

Pipeline:
<img width="954" alt="Screenshot 2025-04-14 at 6 16 16 PM" src="https://github.com/user-attachments/assets/372e4491-de41-4af2-b6a2-7e9c7e0b0435" />

Dashboard:
<img width="826" alt="Screenshot 2025-04-27 at 5 58 48 PM" src="https://github.com/user-attachments/assets/973d2146-ab32-422c-8a7d-472c1bfd5bd1" />

This repository documents an end-to-end data pipeline for the food delivery industry. The solution tackles challenges associated with processing large, unstructured datasets, transforming them into actionable insights that can guide strategic decision-making.


## Overview

- **Objective:** Enable data-driven decision-making by processing and analyzing food delivery data efficiently.
- **Core Technologies:**
  - **Google Cloud Storage:** Stores raw CSV files.
  - **Apache Airflow:** Orchestrates the ETL workflow.
  - **Apache Beam:** Performs data cleaning, transformation, and aggregation.
  - **Google BigQuery:** Serves as a scalable data warehouse.
  - **Tableau:** Visualizes processed data via interactive dashboards.

## Workflow

1. **Data Ingestion:** CSV files are uploaded to a GCS bucket.
2. **Orchestration:** Airflow monitors the bucket and triggers the pipeline.
3. **Data Processing:** Apache Beam cleans, normalizes, aggregates, and validates the data.
4. **Data Warehousing:** Processed data is loaded into BigQuery.
5. **Visualization:** Tableau connects to BigQuery to generate business insights.

## Usage & Applications

- **Usage:**
  - **Developers:** Set up your GCP environment with the required credentials and use the documented Airflow DAG and Beam scripts as guidelines to deploy a similar pipeline.
  - **Business Analysts:** Leverage the processed data in BigQuery and Tableau to create reports that support operational improvements and strategic decisions.

- **Applications:**
  - Optimize delivery operations and routing.
  - Analyze customer trends and preferences.
  - Inform franchising and expansion decisions with detailed performance metrics.

## Conclusion

This project showcases a robust, cloud-based pipeline that transforms raw food delivery data into valuable insights. By integrating modern data processing tools on GCP, it supports strategic decision-making and operational efficiency in a dynamic industry.

---
