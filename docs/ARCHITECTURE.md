# System Architecture Document — RetailPulse DataOps Pipeline

**Project Name:** RetailPulse DataOps Pipeline  
**Author:** Nachiket Gadilohar  

---

## 1. Architecture Flow

```mermaid
graph LR
    Source["Raw CSV / PostgreSQL"] --> Airflow["Apache Airflow DAG"]
    Airflow --> Soda["Soda Core Data Quality"]
    Soda --> BigQuery["Google BigQuery Data Warehouse"]
    BigQuery --> dbt["dbt Transformation Models"]
    dbt --> BI["Power BI / Dashboard"]
```
