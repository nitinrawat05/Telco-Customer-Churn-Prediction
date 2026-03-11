# Telco Churn – End-to-End ML Project

## Purpose
Build and deploy a full machine-learning solution for predicting customer churn in a telecom environment—from data preparation and modeling to an API and web interface for real-time predictions.

---

# Problem Solved & Benefits

### Faster decision making
Predicts which customers are likely to churn so retention teams can intervene before customers leave.

### Operationalized machine learning
The trained model is accessible through a REST API and a simple web interface, allowing users to generate predictions without using notebooks.

### Repeatable delivery
Containerization and CI/CD pipelines ensure that the application can be rebuilt, tested, and deployed consistently across environments.

### Traceable experiments
MLflow is used to track experiments, log metrics, and store model artifacts for reproducibility and auditing.

---

# What I Built

## Data & Modeling
Performed feature engineering and trained an **XGBoost classification model** to predict telecom customer churn. Experiments and metrics were logged using MLflow.

## Model Tracking
All training runs, evaluation metrics, and serialized models were logged under a structured MLflow experiment for reproducibility.

## Inference Service
Developed a **FastAPI application** exposing:
