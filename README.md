# Credit Card Fraud Detection  🔐💳

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A machine learning model to detect fraudulent credit card transactions using anonymized transaction data.  
Built for secure, real-time fraud detection using classification algorithms.

---

## ✨ Features
- Binary classification: Fraudulent vs Legitimate
- Imbalanced data handling
- Feature scaling and preprocessing
- Model performance evaluation with precision/recall/F1
- Optional Streamlit interface for live predictions

---

## 🧠 Tech Stack
| Tool | Purpose |
|------|---------|
| Python | Programming |
| Pandas, NumPy | Data analysis |
| Scikit-learn | Model training & evaluation |
| Matplotlib, Seaborn | Visualization |

---

## 📂 Dataset
- *Source*: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- *Size*: 284,807 transactions, 492 frauds
- *Note*: Highly imbalanced dataset

---

## 🏗 Workflow
1. Load and preprocess data (scaling, null checks)
2. Handle imbalance with undersampling / SMOTE
3. Train models: Logistic Regression, Random Forest, XGBoost
4. Evaluate using:
   - Confusion Matrix
   - ROC AUC
   - Precision/Recall

---

## 📊 Results
- Best performing model: *[Insert model name]*
- Accuracy: 99.6%
- Precision: 97.47%
- Recall: 78.57%
  
---

## 🛠 Installation

```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
jupyter notebook  # or streamlit run app.py
