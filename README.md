# 🌦️ Data Engineer Project — São Paulo Weather Pipeline

Pipeline ETL que coleta dados meteorológicos de São Paulo em tempo real via API OpenWeatherMap, transforma com Pandas e armazena em PostgreSQL — orquestrado pelo Apache Airflow via Docker.

---

## 🎯 Objetivo

Construir um pipeline de dados completo (Extract → Transform → Load) para ingestão e armazenamento contínuo de dados climáticos da cidade de São Paulo, servindo como projeto prático de engenharia de dados.

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| Python 3.12+ | Linguagem principal |
| Pandas | Transformação dos dados |
| SQLAlchemy + psycopg2 | Conexão com PostgreSQL |
| PostgreSQL | Banco de dados de destino |
| Apache Airflow | Orquestração do pipeline |
| Docker / Docker Compose | Infraestrutura containerizada |
| uv | Gerenciador de pacotes |

---

## 🗂️ Estrutura

```
data-engineer-project-vb/
├── dags/               # DAGs do Airflow
├── data/               # Dados brutos/intermediários
├── notebooks/          # Análises exploratórias
├── src/
│   ├── extract_data.py
│   ├── transform_data.py
│   └── load_data.py
├── main.py             # Entrada do pipeline
├── docker-compose.yaml
└── pyproject.toml
```

---
