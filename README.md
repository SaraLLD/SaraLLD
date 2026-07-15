# Bonjour, je suis Sara 👋

**Data Scientist & MLOps — Promotion MAR26 BDS, DataScientest**

Je travaille sur des projets de Deep Learning appliqués au domaine médical,
avec une attention particulière à la robustesse des pipelines et à la mise en production.

---

## 🔬 Projet phare — Classification de cellules sanguines

> Classification automatique de 8 types de cellules sanguines à partir d'images microscopiques,
> en aide au diagnostic clinique.

**Dataset** : Mendeley PBC — 17 092 images · 8 classes  
**Modèle déployé** : DenseNet-121 · Cross-validation 5 folds · ~97% accuracy

### Stack technique

| Couche | Technologies |
|---|---|
| Deep Learning | PyTorch · timm · DenseNet-121 · GradCAM++ |
| API & Serving | FastAPI · Streamlit |
| MLOps | MLflow · Apache Airflow · Docker |
| Monitoring | Evidently · IVDR 2017/746 · alertes email |
| Stockage | Supabase · PostgreSQL |
| ML classique | scikit-learn · XGBoost · LightGBM · SHAP |

### Pipeline MLOps

```
Données → Preprocessing (Cellpose) → Entraînement (Airflow DAG)
       → Évaluation (MLflow) → Déploiement (FastAPI + Streamlit)
       → Monitoring drift quotidien (Evidently + alertes IVDR)
```

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

---

## 📫 Contact

[![Email](https://img.shields.io/badge/sara@huch.tech-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sara@huch.tech)
