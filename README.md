<!-- Banner -->
<h1 align="center">🚢 Titanic Survival Prediction</h1>
<p align="center">
  Predicting passenger survival using Machine Learning <br />
  <i>End-to-End ML project | EDA • Modeling • UI Deployment</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9-blue.svg" />
  <img src="https://img.shields.io/badge/ML-Scikit--learn-orange.svg" />
  <img src="https://img.shields.io/badge/UI-Streamlit-brightgreen" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

## 📌 Overview

This project predicts whether a passenger survived the Titanic shipwreck using demographic and socioeconomic data. It demonstrates a full ML workflow: data cleaning, feature engineering, model training, and Streamlit-based deployment.

---

## 🧠 Tech Stack

| Category | Tools |
|---------|-------|
| Language | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Seaborn, Matplotlib |
| Modeling | Scikit-learn (LogReg, SVM, RF, KNN) |
| Interface | Streamlit |
| Deployment | GitHub |

---

## 📊 Exploratory Data Analysis (EDA)

Key findings through visualizations:
- 🎟️ **Pclass & Survival** – Higher-class passengers had better chances.
- 👩‍🦰 **Gender** – Females survived more.
- 👶 **Age Distribution** – Children were prioritized.
- 💰 **Fare Paid** – More expensive tickets aligned with higher survival.

---

## 🏗️ Feature Engineering

- **Imputation**: Filled missing Age/Fare with median or mode.
- **Derived Features**: Created `FamilySize`, extracted `Title` from names.
- **One-Hot Encoding**: For `Sex`, `Embarked`, and `Pclass`.
- **Scaling**: StandardScaler used to normalize features.

---

## 🤖 Model Building

Multiple models were tested:
- Logistic Regression ✅
- Random Forest ✅
- Support Vector Machine
- K-Nearest Neighbors
- Decision Tree

🎯 **Best Accuracy**: ~81% (Random Forest)

```python
Accuracy: 81%
Precision: 0.80
Recall: 0.79
F1-score: 0.795
