# 🏠 House Prices – Advanced Regression (XGBoost)

This project is a solution to the **Kaggle House Prices: Advanced Regression Techniques** competition.  
The goal is to predict house sale prices using advanced regression models with strong feature engineering.

---

## 📌 Overview

- End-to-end machine learning pipeline
- Data cleaning & preprocessing
- Feature engineering & encoding
- Model training using **XGBoost**
- Kaggle submission generation

---
```
## 📁 Project Structure


house-prices-advanced-regression/
│
├── notebook/
│ └── house_prices_xgboost.ipynb
│
├── data/
│ ├── train.csv ❌ not uploaded
│ └── test.csv ❌ not uploaded
│
├── submission/
│ └── submission.csv
│
├── images/
│ └── kaggle_score.png
│
└── README.md
```
---

## 📦 Dataset

Dataset used from Kaggle:

🔗 https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

> ⚠️ **Note:**  
> `train.csv` and `test.csv` are not included in this repository  
> due to Kaggle rules and GitHub best practices.

---

## 🧠 Model Details

- **Algorithm:** XGBoost Regressor  
- **Target Variable:** `SalePrice`
- **Loss Metric:** RMSE (log-transformed target)
- **Techniques Used:**
  - Missing value handling
  - Categorical encoding
  - Feature selection
  - Log transformation of target
  - Hyperparameter tuning

---

## 🚀 How to Run (Kaggle)

1. Open the notebook in Kaggle
2. Add the competition dataset as input
3. Run all cells
4. Generate `submission.csv`
5. Submit to Kaggle leaderboard

---

## 📊 Kaggle Score

![Kaggle Score](images/kaggle_score.png)

---

## ✅ Key Learnings

- Importance of feature engineering in tabular data
- Handling skewed targets using log transformation
- Boosting models outperform basic linear models
- Proper project structuring for GitHub & Kaggle

---

## 👤 Author

**Anurag Chauhan**  
Machine Learning | Data Science | Kaggle Projects

---

⭐ If you like this project, feel free to star the repository!
