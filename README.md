# Food Delivery Data Pipeline on GCP

This repository contains an end-to-end data pipeline for the food delivery industry. It addresses challenges associated with managing large volumes of unstructured data and transforms it into actionable insights for strategic decision-making.

## Overview

- **Objective:** Enable data-driven decision-making by efficiently processing and analyzing food delivery data.
- **Core Technologies:**  
  - **Google Cloud Storage:** Stores raw CSV files.  
  - **Apache Airflow:** Orchestrates ETL workflows.  
  - **Apache Beam:** Cleans, transforms, and aggregates data.  
  - **Google BigQuery:** Serves as the scalable data warehouse.  
  - **Tableau:** Visualizes and generates interactive dashboards.

## Workflow

1. **Data Ingestion:** Upload raw CSV files to a GCS bucket.
2. **Orchestration:** Airflow detects incoming files and triggers the pipeline.
3. **Data Processing:** Apache Beam cleans and normalizes the data, performs aggregations, and validates records.
4. **Data Warehousing:** Processed data is loaded into BigQuery.
5. **Visualization:** Tableau connects to BigQuery to create dashboards for business insights.

## Usage & Applications

- **Usage:**  
  - **Business Analysts:** Use the processed data in BigQuery and Tableau to generate reports that inform operational improvements and strategic decisions.
  
- **Applications:**  
  - Optimize food delivery operations and routing.
  - Analyze customer trends and preferences.
  - Inform franchising and expansion decisions with detailed performance metrics.

## Conclusion

This project demonstrates a practical, cloud-based solution to transform raw food delivery data into valuable insights. By leveraging GCP and modern data processing tools, it enhances data quality and supports strategic decisions across operational, customer, and franchising dimensions. The pipeline is designed to be scalable and robust, making it a useful template for similar data-driven initiatives in dynamic industries.

---

