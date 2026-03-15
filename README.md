# Neidy Tunzine - Data Engineering Projects

**Data Engineer** | Building data platforms that power analytics and AI

In this page I outline years of learning and testing with scalable data systems — from ETL pipelines and lakehouse architectures to ML-serving platforms. 10+ years across the full data lifecycle: field data collection → transformation pipelines → analytics dashboards → AI integration.

Currently a Data Architect at [Zenysis Technologies](https://www.zenysis.com), where I build data integration pipelines for health-sector analytics across multiple countries.

📍 Cape Town, South Africa · 🇲🇿 Originally from Mozambique · 🗣️ Portuguese & English

---

## 🔧 What I work with

**Data Engineering:** Python, SQL, Apache Spark (PySpark), Apache Kafka, DBT, Airflow, Trifacta/Alteryx  
**Cloud & Infrastructure:** AWS (S3, Redshift, Glue, Lambda, Kinesis, Athena), Terraform, Docker, Kubernetes  
**Data Storage:** Delta Lake, Apache Iceberg, PostgreSQL, DuckDB, Parquet, BigQuery  
**AI/ML Integration:** scikit-learn, XGBoost, Prophet, LangChain, pgvector, RAG pipelines, FastAPI  
**Governance & Quality:** Great Expectations, dbt-expectations, Soda, data modeling (Kimball, Data Vault)

---

## 📂 Portfolio projects

### Data engineering

| Project | Description | Tech stack | Status |
|---------|-------------|------------|--------|
| [**bcg-vaccine-forecasting**](https://github.com/neidynm/bcg-vaccine-forecasting) | End-to-end pipeline: ingests WHO/UNICEF immunization data, engineers features, forecasts BCG vaccine demand by country. Includes data quality checks and FastAPI serving. | Python, Airflow, DBT, Prophet, XGBoost, Docker, Terraform | 🟡 In progress |
| [**streaming-health-pipeline**](https://github.com/neidynm/streaming-health-pipeline) | Real-time streaming pipeline for health facility data. Kafka ingestion → Spark Structured Streaming → Iceberg tables on S3 → query via Trino. | Kafka, Spark, Iceberg, Trino, Terraform, Docker | 🔜 Planned (Phase 1) |
| [**transaction-anomaly-detection**](https://github.com/neidynm/transaction-anomaly-detection) | Real-time fraud detection platform: simulated transaction stream, rolling feature engineering, Feast feature store, XGBoost anomaly classifier, Streamlit dashboard. | Kafka, Spark Streaming, Feast, XGBoost, FastAPI, Docker | 🔜 Planned (Phase 2) |
| [**dbt-lakehouse-analytics**](https://github.com/neidynm/dbt-lakehouse-analytics) | Full lakehouse implementation: raw → staging → marts on S3/Parquet. Extended from my [96% performance improvement](https://medium.com/@neidy.tunzine/the-technical-case-for-dbt-how-we-achieved-96-performance-gains-61ae2dacb822) work with DBT + DuckDB. | DBT, DuckDB, S3, Parquet, Terraform, dbt-expectations | 🔜 Planned (Phase 1) |

### AI / ML

| Project | Description | Tech stack | Status |
|---------|-------------|------------|--------|
| [**AI_Agents_crash_course**](https://github.com/neidynm/AI_Agents_crash_course) | RAG-powered documentation chatbot: data ingestion from GitHub repos, chunking strategies, vector search, hybrid retrieval, LLM agent with evaluation framework. [Blog series →](https://medium.com/@neidy.tunzine/7-day-ai-agent-crash-course-building-a-github-repository-chatbot-f72a3a73abfb) | Python, LangChain, Elasticsearch, DeepSeek R1, RAG | ✅ Complete |
| [**Maternal health risk prediction**](https://medium.com/@neidy.tunzine/predicting-maternal-health-risk-651916ed7655) | End-to-end ML system for healthcare risk assessment: data analysis, feature engineering, model training and evaluation, deployment. | Python, scikit-learn, XGBoost, Docker, FastAPI | ✅ Complete |
| [**machine_learning_zoomcamp_homework**](https://github.com/neidynm/machine_learning_zoomcamp_homework) | Complete coursework from DataTalksClub ML Zoomcamp: regression, classification, decision trees, deep learning, Kubernetes deployment. | Python, TensorFlow, scikit-learn, Docker, K8s | ✅ Complete |

### Architecture & documentation (coming soon)

| Document | Description | Status |
|----------|-------------|--------|
| **Data platform blueprint** | Reference architecture for a mid-size health-tech company: ingestion, lakehouse, transformation, ML serving, governance, cost model. | 🔜 Planned (Phase 2) |
| **Architecture Decision Records** | ADR series: "Why Iceberg over Delta", "Batch vs. streaming for health data", "When to use a feature store vs. materialized views" | 🔜 Planned (Phase 3) |

---

## 📝 Writing

I write about data engineering, AI/ML, and lessons learned on [**Medium**](https://medium.com/@neidy.tunzine). Selected posts:

- [The Technical Case for DBT: How I Achieved 96% Performance Gains](https://medium.com/@neidy.tunzine/the-technical-case-for-dbt-how-we-achieved-96-performance-gains-61ae2dacb822) — Refactored a 1,000+ line SQL pipeline using DBT + DuckDB
- [Predicting Maternal Health Risk](https://medium.com/@neidy.tunzine/predicting-maternal-health-risk-651916ed7655) — Building an end-to-end ML system for healthcare
- [Building Smart AI Agents with Free LLMs](https://medium.com/@neidy.tunzine/day-4-creating-smart-ai-agents-with-free-llms-bringing-your-documentation-assistant-to-life-e8d8a69b79a7) — RAG documentation assistant with DeepSeek R1
- [AWS S3 Tables for Healthcare Data Analytics](https://medium.com/@neidy.tunzine/transforming-healthcare-data-collection-my-experience-with-amazon-s3-tables-workshop-7fdba660a303) — Real-time streaming pipeline workshop insights

---

## 🎓 Certifications

| Certification | Issuer | Year |
|---------------|--------|------|
| AWS Certified Cloud Practitioner | Amazon Web Services | 2025 |
| AWS Certified Data Engineer — Associate | Amazon Web Services | 🔜 In progress |
| Snowflake SnowPro Core | Snowflake | 🔜 Planned |
| Databricks Data Engineer Associate | Databricks | 🔜 Planned |
| Data Engineer Associate | DataCamp | 2025 |
| IBM Data Warehouse Engineer Professional | IBM / Coursera | 2024 |
| Google Data Analytics Professional | Google / Coursera | 2023 |

---

## 📫 Connect

- **LinkedIn:** [neidy-tunzine](https://www.linkedin.com/in/neidy-tunzine)
- **Medium:** [@neidy.tunzine](https://medium.com/@neidy.tunzine)
- **Email:** neidy.tunzine@gmail.com
