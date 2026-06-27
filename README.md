# Explainable Federated Learning Framework for Privacy-Preserving Breast Cancer Diagnosis

## Overview

This repository presents an **Explainable Federated Learning (FL)** framework for privacy-preserving breast cancer diagnosis using the **Breast Cancer Wisconsin (Diagnostic)** dataset.

Instead of sharing patient data with a central server, the proposed framework simulates multiple healthcare institutions where machine learning models are trained locally. The locally trained models are aggregated using the **Federated Averaging (FedAvg)** algorithm to construct a global model while preserving data privacy.

To improve transparency and clinical trust, **SHAP** and **LIME** are integrated to provide both global and local explanations of model predictions.

---

## Features

* Privacy-preserving Federated Learning framework
* Simulated multi-client healthcare environment
* Logistic Regression, Random Forest and XGBoost models
* Federated Soft Voting Ensemble
* SHAP global feature importance
* LIME local prediction explanations
* Comparative analysis between centralized and federated learning

---

## Dataset

**Dataset:** Breast Cancer Wisconsin (Diagnostic)

* Total Samples: **569**
* Features: **30**
* Classes:

  * Benign (357)
  * Malignant (212)

Source:
UCI Machine Learning Repository

---

## Methodology

The proposed framework follows these steps:

1. Data preprocessing and feature standardization
2. Train-test split (80:20)
3. Federated client partitioning
4. Local model training
5. Federated Averaging (FedAvg)
6. Global model evaluation
7. Federated Soft Voting Ensemble
8. Explainability using SHAP and LIME

---

## Models Used

* Logistic Regression
* Random Forest
* XGBoost
* Federated Soft Voting Ensemble

---

## Results

### Centralized Learning

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 96.49%   |
| Random Forest       | 97.37%   |
| XGBoost             | 97.37%   |

### Federated Learning

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 98.25%   |
| Random Forest       | 95.61%   |
| XGBoost             | 96.49%   |

### Federated Soft Voting Ensemble

* **Accuracy:** 97.37%
* **ROC-AUC:** 0.9980

---

## Explainability

The framework incorporates two explainability techniques:

### SHAP

* Global feature importance
* Model-level interpretation

### LIME

* Local prediction explanation
* Patient-specific feature contribution

---

## Technologies Used

* Python
* Google Colab
* Scikit-learn
* XGBoost
* Pandas
* NumPy
* Matplotlib
* SHAP
* LIME

---


## Authors

* **Riya Jain**
* **Mehak Aggarwal**

Department of Computer Science & Engineering (Artificial Intelligence)

Department of Information Technology (IT)

Indira Gandhi Delhi Technical University for Women (IGDTUW)

