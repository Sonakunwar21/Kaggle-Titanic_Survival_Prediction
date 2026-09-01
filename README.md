# 🚢 Titanic — Machine Learning from Disaster Project

> **From Passenger Data → Survival Insights → Machine Learning Predictions**

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)
[![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?logo=scikit-learn)](https://scikit-learn.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Competition-20BEFF?logo=kaggle)](https://www.kaggle.com/)

---

## 📌 Project Overview

This project solves Kaggle's **Titanic: Machine Learning from Disaster** classification problem.

The goal is to predict passenger survival using demographic, ticket, fare, and family-related features.

The project follows a complete Data Science workflow:

**Data Understanding → EDA → Feature Engineering → Preprocessing → Model Training → Cross-Validation → Model Comparison → Prediction → Kaggle Submission**

---

## 🎯 Problem Statement

The objective is to predict whether a Titanic passenger survived based on available passenger information such as:

- Passenger Class
- Sex
- Age
- Fare
- Family Information
- Embarkation Port

The target variable is **`Survived`**, where:

- `0` → Did not survive
- `1` → Survived

---

## 🔍 Project Workflow

```text

Raw Dataset
     ↓
Data Understanding
     ↓
Missing-Value Analysis
     ↓
Data Cleaning
     ↓
Feature Engineering
   ├── Title Extraction
   ├── Family Size
   ├── Is Alone
   └── Age/Fare Features
     ↓
EDA & Visualization
     ↓
Encoding & Transformation
     ↓
Train / Validation Strategy
     ↓
Baseline Model
     ↓
Model Comparison
     ↓
Random Forest Tuning
     ↓
Error Analysis
     ↓
Final Model
     ↓
Test Prediction
     ↓
Kaggle Submission
```
---


## 📊 Exploratory Data Analysis

The EDA focused on understanding passenger characteristics, missing values, distributions, and their relationship with survival.

### Key Analyses

- Numerical feature distributions
- Categorical feature distributions
- Missing-value analysis
- Survival rate by Sex
- Survival rate by Passenger Class
- Age vs Survival
- Fare vs Survival
- Sex × Passenger Class × Survival
- Family Size × Sex × Survival
- Correlation analysis

### 🔑 Key Insights

- **Sex** showed a strong relationship with survival.
- **Passenger Class** strongly influenced survival.
- Female passengers generally had higher survival rates.
- Higher fares were generally associated with higher survival.
- Very large families showed lower survival patterns.
- `Cabin` contained a substantial amount of missing data.
- `Fare` showed a right-skewed distribution.
---

## 🧠 Models & Evaluation

The following classification approaches were explored:

- Logistic Regression
- Random Forest
- Gradient Boosting / XGBoost

### Evaluation Strategy

- Stratified K-Fold Cross-Validation
- Accuracy comparison
- Model performance comparison
- Error analysis
- Hyperparameter tuning

The models were evaluated using validation performance before generating predictions for the unseen test dataset.
---
## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | Jupyter Notebook |
| Competition | Kaggle |
---
## 💡 Key Learnings

- EDA helps identify meaningful patterns before modeling.
- Feature engineering can improve predictive performance.
- Cross-validation provides a more reliable estimate of model performance.
- Preprocessing must be handled carefully to avoid data leakage.
- Local validation performance can differ from Kaggle performance.
- Iterative experimentation is important for improving ML models.
---

## 📈 Outcome & Conclusion

- Built an end-to-end Titanic classification project.
- Performed structured EDA to identify important survival patterns.
- Applied feature engineering and data preprocessing.
- Used cross-validation to evaluate model performance.
- Compared multiple classification approaches.
- Generated predictions for the Kaggle test dataset.
- Successfully created and submitted `submission.csv`.
- Achieved a **77.51% accuracy** on the first Kaggle submission.
---
## 🚀 Future Improvements

- Improve feature engineering using deeper EDA insights.
- Perform more systematic hyperparameter tuning.
- Explore advanced boosting and ensemble techniques.
- Perform deeper error analysis.
- Improve model generalization.
- Compare future submissions against the **77.51% baseline**.

---

```text

Titanic-Machine-Learning-from-Disaster/
│
├── 📂 data/
│   ├── train.csv
│   └── test.csv
│
├── 📂 notebooks/
│   ├── Titanic_EDA.ipynb
│   └── Titanic_ML.ipynb
│
├── 📂 submission/
│   └── submission.csv
│
├── README.md
│
└── licence
---
```
## 👩‍💻 Author

**Sona Kunwar**
