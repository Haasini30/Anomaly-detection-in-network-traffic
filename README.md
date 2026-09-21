# Anomaly Detection in Network Traffic (CSE-CIC-IDS2018)

This project implements a Machine Learning-based Intrusion Detection System (IDS) using the **CSE-CIC-IDS2018** dataset. It applies various ML algorithms, data preprocessing techniques, and model explainability tools to classify network traffic and detect malicious activity.

---

## 📊 Dataset

- **Source**: [CSE-CIC-IDS2018](https://www.unb.ca/cic/datasets/ids-2018.html)
- The dataset simulates real-world traffic with labeled attacks such as DDoS, Brute-force, Botnets, and more.

---

## 🧰 Features

- **Data Preprocessing**:
  - Handling missing values
  - Categorical encoding
  - Feature scaling (Standard, MinMax, Robust)
  - Balancing using SMOTE, RandomOverSampler, RandomUnderSampler

- **Modeling**:
  - Tree-based models: DecisionTree, RandomForest, ExtraTrees
  - Ensemble models: XGBoost, LightGBM, CatBoost, AdaBoost
  - Others: k-NN, Naive Bayes, SVM, MLP

- **Evaluation**:
  - Accuracy, Precision, Recall, F1-Score, ROC AUC
  - Confusion Matrix, Cross-validation

- **Explainability**:
  - LIME (Local Interpretable Model-Agnostic Explanations)
  - SHAP (SHapley Additive exPlanations)

---

## 🛠️ Requirements

See [`requirements.txt`](./requirements.txt) for dependencies.

Install with:

```bash
pip install -r requirements.txt
