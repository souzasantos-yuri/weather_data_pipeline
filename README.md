# 🌦️ Data Engineer Project — São Paulo Weather Pipeline

End-to-end ETL pipeline that collects real-time weather data from São Paulo via the OpenWeatherMap API, transforms it with Pandas, and stores it in PostgreSQL — orchestrated by Apache Airflow via Docker.

---

## 🎯 Objective

Build a complete data pipeline (Extract → Transform → Load) for continuous ingestion and storage of weather data from São Paulo, serving as a hands-on data engineering portfolio project.

---

## 🛠️ Technologies

| Technology | Use |
|---|---|
| Python 3.12+ | Main language |
| Pandas | Data transformation |
| SQLAlchemy + psycopg2 | PostgreSQL connection |
| PostgreSQL | Target database |
| Apache Airflow | Pipeline orchestration |
| Docker / Docker Compose | Containerized infrastructure |
| uv | Package manager |

---

## 🗂️ Structure

```
data-engineer-project-vb/
├── dags/               # Airflow DAGs
├── data/               # Raw/intermediate data
├── notebooks/          # Exploratory analysis
├── src/
│   ├── extract_data.py
│   ├── transform_data.py
│   └── load_data.py
├── main.py             # Pipeline entry point
├── docker-compose.yaml
└── pyproject.toml
```

---
