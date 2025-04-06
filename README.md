# ❤️ Heart Disease Diagnostic Classifier

This repository contains a machine learning-based predictive model designed to accurately classify the presence of heart disease using clinical data. The models implemented include Random Forest (RF), XGBoost, LightGBM, and an ensemble of classifiers. Each model has been evaluated based on key performance metrics: accuracy, precision, and recall.

## 🚀 Objective

To build an efficient and reliable classifier that can assist in early diagnosis of heart disease, enabling timely medical intervention.

---

## 📊 Model Performance

| Model         | Accuracy | Precision | Recall |
|---------------|----------|-----------|--------|
| Random Forest | 0.97     | 0.97      | 0.97   |
| XGBoost       | ~0.99    | ~0.99     | ~0.99  |
| LightGBM      | ~0.99    | ~0.99     | ~0.99  |
| Ensemble      | ~0.99    | ~0.99     | ~0.99  |

> All models demonstrated high performance, with XGBoost, LightGBM, and the Ensemble model attaining approximately 99% across all major metrics.

---

##  Best Performing Model

###  **Selected Model: XGBoost Classifier**

The **XGBoost** model is selected as the best-performing classifier due to its:
- Superior generalization capabilities
- Fast training time
- Robustness to overfitting
- Interpretability via built-in feature importance

While the ensemble approach offers similar metrics, XGBoost achieves this performance independently with less complexity, making it ideal for deployment and real-time diagnostics.

---

## 🧠 Libraries Used

- Python
- Scikit-learn
- XGBoost
- LightGBM
- Pandas, NumPy
- Matplotlib, Seaborn

---


