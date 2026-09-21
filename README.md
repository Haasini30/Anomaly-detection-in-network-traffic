# Anomaly Detection in Network Traffic

This project implements a machine learning pipeline for **anomaly detection in network traffic**, with a focus on identifying **intrusions**—critical anomalies that compromise network integrity.

Using the **CSE-CIC-IDS2018 dataset**, which reflects real-world enterprise network conditions, the system detects various abnormal patterns including DDoS, brute force, and botnet attacks. The solution integrates robust data preprocessing, imbalance handling, and feature selection to prepare high-quality inputs for training.

## 🚀 Features

- **Preprocessing**: Label encoding, feature scaling, and data balancing using SMOTE and RandomOverSampler.
- **ML Models**: Decision Tree, Random Forest, Extra Trees, XGBoost, LightGBM, CatBoost, k-NN, SVM, Naive Bayes, MLP, and AdaBoost.
- **Evaluation**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC AUC, and cross-validation.
- **Explainability**: LIME and SHAP for model interpretation and transparency.

> 📌 This project is designed for **academic, research, and educational purposes only**.

## 🧾 Dataset

- Source: [CSE-CIC-IDS2018](https://www.unb.ca/cic/datasets/ids-2018.html)
- Realistic, labeled data for intrusion detection system benchmarking.

## 🛠️ Setup

1. Clone the repo or upload files to your GitHub profile.
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 📂 Files

- `anomalydetection.ipynb` – Full notebook containing code and visualizations
- `requirements.txt` – Dependencies list
- `LICENSE` – Educational use license
- `README.md` – This file

## 🧠 Notes

- Notebook was originally run in a Kaggle environment; update paths if running locally.
- Use Jupyter or VSCode to explore the notebook and visual outputs.

## 📝 License

This project is released under an [Educational Use License](./LICENSE). Commercial use is prohibited.
