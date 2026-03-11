# 🌲 Random Forest – Classifier & Regressor Practice

> Hands-on practice of Random Forest (Classification + Regression) as part of my AI/ML learning journey.

---

## 📁 Project Structure

```
random-forest-practice/
│
├── random_forest_classifier.ipynb   # Titanic survival prediction
└── random_forest_regressor.ipynb    # Diabetes disease progression prediction
```

---

## 🔍 Notebook 1 – Random Forest Classifier

**Dataset:** Titanic (via Seaborn)  
**Goal:** Predict passenger survival (binary classification)

### What I did:
- Selected features: `pclass`, `sex`, `age`, `fare`, `embarked`
- Handled missing values using **median imputation** (age) and **mode imputation** (embarked)
- Encoded categorical variables with `LabelEncoder`
- First trained a **Decision Tree** (max_depth=4) → observed classic overfitting
- Then trained a **Random Forest** (501 estimators, OOB score enabled) → improved generalization

### Key Concept Learned:
> A single Decision Tree overfits. Random Forest builds 500+ trees and averages their predictions — reducing variance and improving test accuracy.

---

## 🔍 Notebook 2 – Random Forest Regressor

**Dataset:** Sklearn Diabetes dataset (442 samples, 10 features)  
**Goal:** Predict disease progression score (continuous target)

### What I did:
- Loaded data directly from `sklearn.datasets`
- Trained a **Decision Tree Regressor** (max_depth=7, min_samples_leaf=20)
- Evaluated using **MSE** and **R² score** on both train and test sets
- Then trained a **Random Forest Regressor** (501 estimators, OOB score) → better R² and lower MSE

### Key Concept Learned:
> OOB (Out-of-Bag) Score acts like a built-in cross-validation for Random Forests — no need for a separate validation set.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-lightblue)

---

## 📈 My ML Learning Journey

This is part of my ongoing ML practice series. Check out my other projects:

| Project | Algorithm | Dataset |
|---------|-----------|---------|
| [Credit Risk App](https://github.com/paramramit305-a11y/credit-risk-streamlit-app) | Logistic Regression | Loan Data |
| [KNN Heart Disease](https://github.com/paramramit305-a11y/knn-heart-disease-classification) | KNN | Heart Disease |
| [Heart Disease LR](https://github.com/paramramit305-a11y/logistic-regression-heart-disease) | Logistic Regression | Heart Disease |
| [Insurance Charges](https://github.com/paramramit305-a11y/linear-regression-insurance) | Linear Regression | Insurance |
| 🌲 **Random Forest** (this repo) | Random Forest | Titanic + Diabetes |

---

## 🙋‍♂️ About Me

**Aspiring AI Engineer** | Focused on building real-world ML projects

- 🔗 [GitHub](https://github.com/paramramit305-a11y)
- 💼 [LinkedIn](https://www.linkedin.com/in/banavali-aman-97941a377)
