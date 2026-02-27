# 🚀 Bank Marketing Campaign Analysis & Subscription Prediction

> End-to-End Data Analysis & Machine Learning Project  
> Predicting Term Deposit Subscription using Advanced ML Models

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-5C5C5C?style=for-the-badge)

---

## 📌 Business Problem

A Portuguese banking institution conducted direct marketing campaigns to promote term deposits.  
The objective is to **predict whether a client will subscribe** to a term deposit product.

Accurate predictions allow the bank to:
- 🎯 Target high-probability customers
- 💰 Reduce marketing costs
- 📈 Increase campaign conversion rate

---

## 📊 Dataset Overview

- 👥 11,162 customer records
- 📞 Marketing campaign call data
- 🏦 Financial & demographic features
- 🎯 Target variable: `Subscribed (Yes/No)`

---

## 🔎 Project Workflow

### 1️⃣ Exploratory Data Analysis (EDA)
- Univariate & Bivariate Analysis
- Correlation Analysis
- Distribution & Skewness detection
- Outlier detection

### 2️⃣ Data Preprocessing
- Missing value handling
- Encoding categorical variables
- Feature scaling
- Feature engineering

### 3️⃣ Modeling
Models trained & compared:
- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost (Best Performer)

### 4️⃣ Hyperparameter Tuning
- GridSearchCV
- Cross-validation
- ROC-AUC optimization

---

## 🏆 Model Performance

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | ~XX% | ~XX |
| Random Forest | ~XX% | ~XX |
| XGBoost (Tuned) | **Best Performance** | **Highest ROC-AUC** |

> XGBoost achieved the best overall performance after tuning.

---

## 💡 Key Insights

- 📞 **Call duration** is the strongest predictor.
- 💰 Clients with higher account balance are more likely to subscribe.
- 🏠 Clients without housing loans show higher conversion probability.
- 🌸 Spring season campaigns show better response rates.

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📁 Project Structure

```
bank-marketing-campaign-analysis/
│
├── data/
├── notebooks/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
```

## 📈 Business Impact

This model can help financial institutions:

- Reduce unnecessary customer calls
- Focus on high-conversion segments
- Improve marketing ROI
- Make data-driven campaign decisions

---

## 👤 Author

Ahmed Fouad
Data Scientist  
LinkedIn: (https://www.linkedin.com/in/hashemili/)  
Kaggle: (https://www.kaggle.com/hashemili)

---
