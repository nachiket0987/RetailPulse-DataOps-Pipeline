# Product Requirement Document (PRD) — RetailPulse DataOps Pipeline

**Project Name:** RetailPulse DataOps Pipeline  
**Project Description:** Enterprise Retail Analytics Data Pipeline using Apache Airflow, BigQuery, dbt, & Soda Core.  
**Author:** Nachiket Gadilohar  

---

## 1. Executive Summary
RetailPulse is an automated DataOps pipeline for retail sales, inventory, and customer churn analytics. It orchestrates DAGs using Apache Airflow, transforms raw data models in Google BigQuery via dbt, and enforces data quality checks with Soda Core.

---

## 2. Core Features
1. **Airflow Orchestration**: Automated daily ETL DAG execution.
2. **dbt Data Transformation**: Staging, intermediate, and dimensional data modeling (Star Schema).
3. **Soda Core Data Quality Tests**: Automated assertions for non-null checks, schema drift, and fresh timestamps.
