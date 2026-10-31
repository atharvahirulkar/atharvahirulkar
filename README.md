# Hi, I'm Atharva

**Data & ML Platform Engineer** · MS Data Science @ UC San Diego (Dec 2026) · ex-State Street · San Diego, CA

Close to 3 years building production data platforms at State Street: Snowflake and Airflow pipelines at 5M+ records/day with 99.9%+ SLA, and Terraform, Ansible, and Azure DevOps automation for a 120+ team database migration. Now building ML systems and LLM agents on top of that foundation: model serving, MLOps, streaming, and governed data for AI.

🏆 3x hackathon winner in 2026: DataHacks, Bow Capital Defense Hackathon, and SOLIXEmpower (Data + AI Track).

---

## 💻 Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

**Data Engineering**
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-003366?style=flat)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-1A1A1A?style=flat&logo=timescale&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-018BFF?style=flat&logo=neo4j&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white)

**ML & MLOps**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=PyTorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-CC342D?style=flat)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**LLMs & Agents**
![Google ADK](https://img.shields.io/badge/Google%20ADK-4285F4?style=flat&logo=google&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)

**Cloud & DevOps**
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat&logo=oracle&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat&logo=azuredevops&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

---

## 🎯 Featured Projects

### [fraud-lens](https://github.com/atharvahirulkar/fraud-lens): Live Fraud Detection Service + Gemini Analyst Agent on GCP
A fraud model in production on GCP, with an analyst agent that answers plain-English questions over the scoring tables.
`XGBoost + MLflow registry` → `FastAPI on Cloud Run (scale to zero)` · `Airflow` → `GCS Parquet + BigQuery` · `Google ADK agent on Gemini 2.5 Flash`
🎯 **AUC-PR 0.833 · AUC-ROC 0.973** · 🤖 **98% agent answer accuracy over 60 runs**, graded against live BigQuery SQL · 🔒 GitHub Actions CI/CD via Workload Identity Federation, least-privilege service accounts

### [SignalStack](https://github.com/atharvahirulkar/SignalStack): Real-Time Streaming ML for Equity Markets
`Polygon.io WebSocket` → `Kafka` → `PySpark Structured Streaming` → `TimescaleDB` → `FastAPI` → `Grafana`
⚡ **>1,000 events/sec** · **p99 < 10ms** model serving · point-in-time correct features · LSTM, XGBoost, and Isolation Forest · MLflow registry with PSI drift alerting

### [MaritimeIQ](https://github.com/atharvahirulkar/MaritimeIQ): Agentic Data Activation for Shipping · 🏆 SOLIXEmpower 2026, Data + AI Track
Siloed, PII-heavy shipping feeds turned into governed, LLM-ready data (team project)
`6 source formats` → `PySpark + Delta Lake medallion (Bronze/Silver/Gold)` → `Entity resolution + human review` → `Guarded Text-to-SQL`
🎯 **Vessel entity resolution F1 1.00** · 🔒 **5/5 adversarial probes blocked** by a deterministic policy guard · PII masking and audit log · synthetic data with planted errors

### [Chokepoint](https://github.com/atharvahirulkar/chokepoint): Defense Supply-Graph Intelligence · 🏆 Bow Capital Defense Hackathon 2026 · [Live Demo](https://atharvahirulkar-chokepoint.hf.space)
Surfaces vendor concentration risk across the U.S. defense industrial base
`USAspending (9.1M rows)` → `NetworkX graph (49,842 vendors, 228K edges)` → `GradientBoosting + N-1 contingency labels` → `FastAPI + Streamlit`
🎯 **2x a centrality baseline** · 🔍 **6 of 10 real disruptions ranked in the top 1%** of vendors

### [Seismic Risk Atlas](https://github.com/Varad02/SeismicRiskAtlas): Census-Tract Earthquake Loss Estimator · 🏆 DataHacks 2026, Best in Data Engineering
Physics-based seismic risk modeling fused with housing and census data (team project)
`Databricks Spark` → `FEMA HAZUS fragility curves` → `GPU XGBoost` → `FastAPI + Leaflet.js`
🎯 **R² 0.99996** · ⚡ **0.70s GPU inference** · 2,498 LA County census tracts · geographic-split validation

### [CosmeTik](https://github.com/atharvahirulkar/cosmetik): Hybrid Graph + Vector Recommender
`PostgreSQL` + `Neo4j (PageRank + Louvain)` + `Qdrant (sentence-transformer embeddings)` → `Streamlit`
⭐ **1M+ reviews** · 🔗 **30 ingredient communities detected** · derived stores rebuilt from Postgres as the source of truth

### More projects
- [Irona](https://github.com/atharvahirulkar/irona): local-first AI agent on Ollama (Qwen 2.5 7B) with a deny-by-default tool policy, allowlisted file search, and full audit logging
- [JobPilot](https://github.com/atharvahirulkar/JobPilot): agentic job pipeline with GPT-4o-mini skill-gap extraction, LaTeX resume tailoring, and PostgreSQL dedup
- [FraudLens (v1)](https://github.com/atharvahirulkar/fraudlens): the original AWS build (ECS Fargate, ALB, S3, Athena), paused to control cost and rebuilt as fraud-lens on GCP
- [PulseML](https://github.com/atharvahirulkar/pulseml): wearable ECG/PPG monitoring, LSTM arrhythmia detection at AUC 0.93, Govt. of India Copyright L-114951/2022
- [Multilingual Speech Transcription](https://github.com/atharvahirulkar/multilingual-speech-transcription): video-to-text pipeline with summarization and translation

---

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atharva-hirulkar/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=About.me&logoColor=white)](https://ahirulkar.me)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ahirulkar@ucsd.edu)

**Open to:** full-time Data Engineering, ML Platform, MLOps, and AI Engineering roles from December 2026.
