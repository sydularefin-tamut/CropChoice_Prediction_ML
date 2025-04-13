# 🌾 Crop Choice Decision Prediction Using ML & Multinomial Logit

📊 Predicting crop choices like rice, maize, jute, and lentil using agro-environmental features via Multinomial Logistic Regression and powerful Machine Learning models.

---

## 📚 Project Summary

This project integrates:
- A **Multinomial Logit model** to statistically evaluate agro-environmental impacts
- **ML models** (Random Forest, Gradient Boosting, LightGBM) for predictive crop selection
- Feature importance analysis to understand environmental and nutrient drivers
- A dataset of 2200 samples from Kaggle including N, P, K, temp, humidity, pH, and rainfall

---

## 🔧 Key Features

- Dual-method analysis (Statistical + Machine Learning)
- Multiclass prediction (5 crop types)
- Marginal effect interpretation of soil/environmental variables
- Model metrics: precision, recall, F1-score, feature importance
- Exploratory boxplots for variable impact across crops

---

## 🧠 Models Used

- Multinomial Logistic Regression
- Random Forest (RF)
- Gradient Boosting (GB)
- LightGBM (LGBM)

---

## 📈 Results Snapshot

| Model     | Accuracy | Notable Findings                                      |
|-----------|----------|--------------------------------------------------------|
| RF        | ~99%     | High recall on cotton & maize, rice slightly lower    |
| GB        | 98.1%    | Great performance, minor drops on jute & rice         |
| LGBM      | 98.6%    | Highest efficiency, balanced prediction across crops  |

> **Rainfall and humidity** were top features across all ML models.

---

## 🔍 Feature Importance

| Feature     | RF    | GB    | LGBM |
|-------------|-------|-------|------|
| Rainfall    | 0.227 | 0.242 | 0.226 |
| Humidity    | 0.211 | 0.232 | 0.225 |
| Potassium   | 0.181 | 0.190 | 0.132 |
| Phosphorus  | 0.143 | 0.120 | 0.108 |
| Nitrogen    | 0.108 | 0.119 | 0.107 |
| Temperature | 0.075 | 0.055 | 0.105 |
| pH          | 0.052 | 0.038 | 0.093 |

---

## 📦 Requirements

```bash
pip install -r requirements.txt
•	pandas
•	numpy
•	scikit-learn
•	statsmodels
•	xgboost
•	lightgbm
•	seaborn
•	matplotlib

