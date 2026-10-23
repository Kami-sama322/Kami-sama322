<!--
  GitHub Profile README
  Repo: https://github.com/Kami-sama322/Kami-sama322
  Copy this file as README.md into that special repo (same name as username).
-->

<div align="center">

### [🇷🇺 Русский](README.ru.md) | en English

# Alexander Tsay

**Lead / Senior Data Engineer**

Serbia · remote / hybrid

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alextsay92/)
[![Habr](https://img.shields.io/badge/Habr-77A8CC?style=for-the-badge&logo=habr&logoColor=white)](https://habr.com/ru/users/Kami-sama322/articles/)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/AlexTsay92)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:AlexTsay92@yandex.ru)

</div>

---

## About

Senior Data Engineer with around five years building data warehouses, pipelines, and backend services.

At MTS Digital I develop dbt models, maintain an Airflow DAG factory, and build data and LLM-powered services. I review code, plan work for junior engineers, and mentor on the company program.

I use Cursor daily with project-specific rules, reusable agent skills, hooks, and MCP integrations. I review generated changes and check them with tests.

Open to Lead/Senior Data Engineer roles, remote.

---

## Stack

### Data & pipelines

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Flink](https://img.shields.io/badge/Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)

### Storage

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)

### AI / LLM

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat-square)
![LiteLLM](https://img.shields.io/badge/LiteLLM-0B57D0?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-4051B5?style=flat-square)

### Platform

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Superset](https://img.shields.io/badge/Apache%20Superset-20A7C9?style=flat-square&logo=apache&logoColor=white)

---

## Highlights

| What | Outcome |
| --- | --- |
| **dbt media catalog** | Full rebuild of roughly 2 hours down to a 15-minute incremental run. 40 models, 8 sources. Normalized layer plus wide marts for a leisure bot. |
| **Airflow factory** | 150 DAGs. A similar new report went from a day as its own DAG to an hour. Each run posts to the company messenger. dbt tests for unique and not_null keys, plus a 24-hour freshness check. |
| **Clickstream** | 50 million events a day, peaks near 3,000 per second. Kafka into ClickHouse through the Kafka engine and materialized views. Marts for DAU, MAU, retention, funnels, and screen usage. |
| **Support-bot retrieval** | NER pulls IDs, product names, and error text. An agent chooses the search. Hybrid embeddings and BM25 in Qdrant. The model answers from the ranked chunks. |
| **Qwen on vLLM** | Served in our own environment. Langfuse records token counts from the API. A rate card estimates cost. Prometheus and Grafana show KV-cache use and queue depth. Batching under PagedAttention was set from those graphs. |
| **Text2SQL** | LangGraph agent for 15 people who do not write SQL. Repeat questions to analysts dropped from several times a day to several times a week. On 30 questions, 80% of first answers were acceptable. |
| **SkillHub and LiteLLM** | Versioned prompts and skills for internal agents. Request traces in Langfuse. |
| **Reporting APIs** | Rewrote reporting services on async FastAPI. No direct push to dev or master. Credentials in Vault. |
| **GigaAM-v3** | Transcriber in OpenWebUI through an OpenAI-compatible LiteLLM endpoint. |
| **Pravoved analytics** | One glossary with sales, marketing, and finance. After Tableau left, main reports on Yandex DataLens in a week, then the warehouse on ClickHouse. Quarterly AppRaise score 4.9/5. |

---

## Open source

| Repository | About |
| --- | --- |
| [flink_streaming_python_mongodb_postgresql](https://github.com/Kami-sama322/flink_streaming_python_mongodb_postgresql) | Streaming MongoDB → PostgreSQL with PyFlink on Kubernetes |
| [superset-plugin-filter-calendar](https://github.com/Kami-sama322/superset-plugin-filter-calendar) | Native Filter: calendar like a Power BI Date Slicer |
| [superset-plugin-filter-checkbox](https://github.com/Kami-sama322/superset-plugin-filter-checkbox) | Native Filter: checkbox list for multi/single select |
| [superset-plugin-chart-logo-buttons](https://github.com/Kami-sama322/superset-plugin-chart-logo-buttons) | Chart: logo buttons with dashboard cross-filters |
| [superset-plugin-chart-country-scatterplot-map](https://github.com/Kami-sama322/superset-plugin-chart-country-scatterplot-map) | Chart: Country Map choropleth + scatter bubbles |
| [superset-plugin-chart-funnel](https://github.com/Kami-sama322/superset-plugin-chart-funnel) | Chart: Funnel chart like a PowerBI with wide customizations |
| [superset-plugin-filter-period-ranges](https://github.com/Kami-sama322/superset-plugin-filter-period-ranges) | Native Filter: 1–5 equal-length date ranges with OR filtering |
| [superset-plugin-chart-period-comparison](https://github.com/Kami-sama322/superset-plugin-chart-period-comparison) | Chart: one metric across 1–5 periods with on-chart date pickers |

---

## Publications

- [Custom Native Filter plugin for Apache Superset](https://habr.com/ru/companies/ru_mts/articles/1067600/)
- [Apache Flink streaming from MongoDB to PostgreSQL in Python](https://habr.com/ru/companies/ru_mts/articles/898636/)

---

## Experience

```text
2024 — now   MTS Digital (MTS Web Services)     Leading engineer-analyst
2021 — 2023  Pravoved.RU                        BI Analyst
```

~5+ years in data · Python · SQL · ETL/ELT · DWH · LLM agents

---

## Languages

- Russian — native
- English — B2

---

## Focus

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=20A7C9&center=true&vCenter=true&width=640&lines=Data+pipelines+%26+product+DWH;LLM+agents+in+production;Apache+Superset+plugins;Airflow+%C2%B7+Flink+%C2%B7+ClickHouse)](https://git.io/typing-svg)

<br />

<img src="https://skillicons.dev/icons?i=python,postgres,docker,kubernetes,fastapi,redis,kafka,linux,git,prometheus,grafana&perline=11" alt="Core tools" />

<br /><br />

</div>
