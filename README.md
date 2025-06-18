# 💳 Credit Risk Analysis using GAN, LightGBM & Optuna

[![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)](https://github.com/shreyamitra)
[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

This project leverages **deep learning** and **ensemble methods** to assess **credit risk** in loan applications. We’ve used **GANs to augment tabular data**, **ADASYN for balancing**, and **LightGBM with Optuna** for optimal classification.

---

## 🚀 Features

- 🔍 Preprocessing: Label Encoding, Scaling
- 🤖 GAN for synthetic feature generation
- ⚖️ ADASYN to combat class imbalance
- 🌲 LightGBM Classifier
- 🔧 Hyperparameter tuning with Optuna
- 📈 Evaluation: Accuracy, AUC-ROC, Confusion Matrix
- 📦 Model saving & real-time prediction
- 📊 Test dataset generation with batch prediction

---

## 🧠 Tech Stack

| Category          | Tools Used                                 |
|------------------|---------------------------------------------|
| Language          | Python                                      |
| Data Processing   | Pandas, NumPy                               |
| Modeling          | LightGBM, TensorFlow/Keras (GAN), Optuna   |
| Balancing         | imbalanced-learn (ADASYN)                  |
| Evaluation        | Scikit-learn, Matplotlib, Seaborn           |

---

## 📊 Sample Output

```bash
🔥 Loan Approved? YES
🔥 Approval Probability: 0.9432
```
## 🚀 How to Run This Project

📍 Option 1: Google Colab

- Open RiskAnalysis.ipynb in Google Colab
- Upload the model .pkl if needed
- Run the notebook top to bottom
---
## 🖥️ Option 2: Local System

# Clone the repo
```bash
git clone https://github.com/yourusername/Credit-Risk-Analysis.git
cd credit-risk-analysis
```
```bash
# Run the notebook in Jupyter or VSCode
jupyter notebook RiskAnalysis.ipynb
```

