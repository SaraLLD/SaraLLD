# Bonjour, je suis Sara 👋

**Data Scientist & MLOps**

Je travaille sur des projets de machine et Deep Learning appliqués au domaine médical, mais plus largement sur de vrais solutions metiers (finance, e-commerce...)
avec une attention particulière à la robustesse des pipelines et à la mise en production.
Ci-dessous 3 de mes projets phares.
---

## 🔬 Projet 1 — Classification de cellules sanguines

🔒 *Repo privé*

> Classification automatique de 8 types de cellules sanguines à partir d'images microscopiques,
> en aide au diagnostic clinique.

**Dataset** : Mendeley PBC — 17 092 images · 8 classes  
**Modèle déployé** : DenseNet-121 · Cross-validation 5 folds · ~99% accuracy

| Couche | Technologies |
|---|---|
| Deep Learning | PyTorch · timm · DenseNet-121 · GradCAM++ |
| API & Serving | FastAPI · Streamlit |
| MLOps | MLflow · Apache Airflow · Docker |
| Monitoring | Evidently · IVDR 2017/746 · alertes email |
| Stockage | Supabase · PostgreSQL |
| ML classique | scikit-learn · XGBoost · LightGBM · SHAP |

---

## 🤖 Projet 2 — Bot Telegram open banking

🔒 *Repo privé*

> Assistant Telegram pour marchands d'un client de la fintech: consultation de transactions en langage naturel,
> FAQ d'intégration via RAG, et analyse de données JSON directement dans le chat.

**Infrastructure** : OVH VPS Ubuntu 24.04 
**RAG** : 319 chunks indexés · Faithfulness RAGAS 

| Couche | Technologies |
|---|---|
| Bot | python-telegram-bot 21.6 · Webhook HTTPS |
| LLM | Mistral AI |
| RAG | ChromaDB · |
| Admin UI | Streamlit · RAGAS 0.1.21 |
| Infra | Nginx · systemd · OVH VPS |

---

## 🏥 Projet 3 — RegBot Santé

🔒 *Repo privé*

> Assistant IA gratuit qui répond aux questions réglementaires santé (essais cliniques, AMM,
> vigilance, RGPD) en s'appuyant exclusivement sur les FAQ et textes officiels de l'EMA, l'ANSM,
> la DGOS, la CNIL, le CTIS et le Code de la santé publique, avec citation systématique des sources.

**Démo** : https://regbot-sante.streamlit.app
**RAG** : retriever hybride BM25 + FAISS · ~5 000 chunks indexés · 6 sources réglementaires

| Couche | Technologies |
|---|---|
| LLM | Groq (`llama-3.3-70b`) · bascule automatique multi-modèles sur quota |
| RAG | LangChain · FAISS · BM25 (rank_bm25) · sentence-transformers |
| Interface | Streamlit · zone admin (monitoring, feedback, RAGAs) |
| Qualité | RAGAs (fidélité, pertinence, précision du contexte) |
| Déploiement | Streamlit Community Cloud |

---

## 🛠️ Compétences

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Mistral AI](https://img.shields.io/badge/Mistral_AI-FF7000?style=flat&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat&logoColor=white)
