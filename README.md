
# 💳 Credit Card Default Prediction

This project uses machine learning models to predict whether a customer will default on their credit card payment next month.

## 📂 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)
- **Size**: 30,000 samples, 24 features
- **Target**: `default.payment.next.month` (1 = default, 0 = no default)

---

## ⚙️ Models Used

- ✅ Logistic Regression
- ✅ Random Forest Classifier
- ✅ XGBoost Classifier

---

## 🧪 Evaluation Metrics

- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- ROC AUC Score

---

## 🧠 SHAP Explainability

Used SHAP (SHapley Additive Explanations) to interpret the predictions of the XGBoost model.

- `summary_plot`: Shows global feature importance
- `waterfall`: Explains individual predictions

---

## 🧰 Libraries Required

```bash
pandas
numpy
scikit-learn
xgboost
shap
matplotlib
```

You can install dependencies with:

```bash
pip install -r requirements.txt
```

---

## 📊 Results Overview

- XGBoost performed best with highest ROC AUC
- SHAP showed that payment history and bill amounts are the most influential features

---

## 📁 Files

- `Credit_Card_Default_Prediction_With_SHAP.ipynb`: Main notebook with full implementation
- `README.md`: Project overview and documentation

---

## 🚀 How to Run

1. Upload the notebook to [Google Colab](https://colab.research.google.com) or run locally in Jupyter
2. Install required packages if not available
3. Run all cells

---

## ✍️ Author

Made by a Data Science enthusiast exploring predictive modeling and interpretability.
