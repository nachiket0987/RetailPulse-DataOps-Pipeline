# Software Requirements Specification (SRS) — RetailPulse DataOps Pipeline

**Project Name:** RetailPulse DataOps Pipeline  
**Author:** Nachiket Gadilohar  

---

## 1. Requirements
- **FR-ETL-01**: Airflow DAG MUST run on schedule without task failures.
- **FR-DQ-01**: Soda Core assertions MUST block downstream dbt transformations if null thresholds exceed 0.01%.
