# Hi, I'm Atharva

**MS Data Science @ UC San Diego** · **ex-Data Engineer @ State Street** (2 yrs) · San Diego, CA

I architect ML systems and real-time data pipelines that transform raw data into measurable business impact.  
Focused on **production-grade ML**, **streaming systems**, and **vector databases**.

---

## ⚡ Quick Highlights

- 🔬 **Research Focus:** Vector Databases, Graph ML, Production ML Systems
- 📊 **Specialty:** Building end-to-end ML pipelines with <100ms latency @ scale
- 🏢 **Industry:** 2+ years optimizing ML workflows at Fortune 500
- 🏆 **Track Record:** Multiple production systems handling 1K+ events/sec
- 🌱 **IP:** Copyright registered IoT biosensor system (Govt. of India)

---

## 💻 Tech Stack

**Languages & Core**  
![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

**ML / Deep Learning**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=TensorFlow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-CC342D?style=flat&logo=xgboost&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

**MLOps & Serving**  
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)

**Data Engineering & Databases**  
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-1A1A1A?style=flat&logo=timescaledb&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-018BFF?style=flat&logo=neo4j&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-000000?style=flat&logo=qdrant&logoColor=white)

**Cloud & DevOps**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

---

## 🎯 Featured Projects

### [SignalStack](https://github.com/atharvahirulkar/SignalStack) - Real-Time ML Systems for Equity Markets
Production-grade end-to-end pipeline with sub-100ms latency  
`Polygon.io WebSocket` → `Kafka` → `PySpark Streaming` → `TimescaleDB` → `FastAPI` → `Grafana`  
⚡ **>1,000 ticks/sec** · 📊 Full Docker Compose stack · 3 concurrent models (LSTM, LightGBM, Isolation Forest) · PSI drift monitoring with MLflow

### [FraudLens](https://github.com/atharvahirulkar/fraudlens) - Production Fraud Detection with Explainable AI
End-to-end ML system: training, serving, batch scoring, and RAG-powered explanations  
`IEEE-CIS` → `XGBoost + LightGBM` (20+ MLflow runs) → `FastAPI` → `AWS ECS Fargate + ALB` · `Airflow` DAG → `S3 + Athena`  
🎯 **AUC-PR >0.88** · ⚡ **p99 <80ms** · 🔍 RAG explanation layer (Qdrant + SHAP + GPT-4o-mini) · GitHub Actions CI/CD

### [Cadbury](https://github.com/atharvahirulkar/cadbury) - Local-First AI Agent with Constraint Architecture
Privacy-first terminal assistant powered by local LLMs — refining
`Ollama (Qwen 2.5 7B)` → `Policy Engine` → `Allowlisted RAG Search` → `Audit Log` → `Interactive CLI`
🔒 **Deny-by-default tool policy** · 📁 Allowlist-only file access · 🔍 Semantic search with source citations · 🖥️ Fully local inference · v0.2 active

### [JobPilot](https://github.com/atharvahirulkar/JobPilot) - Autonomous Job Application Agent
LLM-powered job application pipeline — testing
`JD Ingestion` → `GPT-4o-mini Alignment Scoring` → `LaTeX Resume Tailoring` → `Cover Letter Generation` → `PostgreSQL Persistence`
🎯 **0–100 resume↔JD fit scoring** · ✂️ Brace-match LaTeX injection · 📝 3-paragraph cover letter generation · 🗄️ Dedup pipeline

### [CosmeTik](https://github.com/atharvahirulkar/cosmetik) - Hybrid Vector + Graph ML Recommender
Multi-database intelligence: relational + graph + vector embeddings  
`PostgreSQL (3NF)` + `Neo4j (PageRank + Louvain)` + `Qdrant (384-dim embeddings)` → `Streamlit UI`  
📦 **~8.5K products** · ⭐ **1M+ reviews** · 🔗 **30 ingredient communities detected** · Skin-type-aware discovery with zero manual curation

### [PulseML](https://github.com/atharvahirulkar/pulseml) - IoT Wearable Biosensor System
Full-stack IoT → signal processing → anomaly detection  
`Custom ECG/PPG wristband (MAX86150 + Arduino Bluno BLE)` → `HeartPy signal processing` → `LSTM + 1D-CNN classifier`  
🏆 **Copyright Reg. No. L-114951/2022** (Govt. of India) · **AUC 0.93** · 30% reduction in false-positive cardiac alerts · BPM forecasting 2.5 min ahead

### [Multilingual Speech Transcription](https://github.com/atharvahirulkar/multilingual-speech-transcription) - Video-to-Text Pipeline
End-to-end video processing with multi-stage NLP  
`Google Speech Recognition` + `BART-Large-CNN summarization` + `Google Translate` → `Flask web app`  
🌍 **100+ languages** · 📝 **~95% WER (English)** · Accessible transcription at scale

---

## 🏆 Achievements

| Focus Area | Highlight |
|---|---|
| **System Performance** | <100ms latency streaming at 1,000+ events/sec |
| **Model Quality** | AUC-PR >0.88 on imbalanced fraud detection · AUC 0.93 on arrhythmia detection |
| **Intellectual Property** | Copyright-registered IoT biosensor system (Govt. of India) |
| **Scale** | 5M+ records/day Snowflake ETL · ~8.5K products · 1M+ reviews |
| **Full Stack** | ML training → MLflow registry → Production APIs → Real-time dashboards |

---

## 🌐 Connect & Explore

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atharva-hirulkar/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/atharvahirulkar)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=github&logoColor=white)](https://atharvahirulkar.github.io/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:atharvahirulkar.010@gmail.com)

**Open to:** ML Engineering · Data Engineering · ML Systems roles - 2026+
