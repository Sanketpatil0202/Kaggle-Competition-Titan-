# 🚢 Titanic - Machine Learning from Disaster

Welcome aboard! This repository contains my work on the **Titanic: Machine Learning from Disaster** competition hosted on [Kaggle](https://www.kaggle.com/competitions/titanic). It's one of the most iconic beginner-friendly challenges and a great starting point for anyone diving into machine learning and data science.

---

## 💡 Competition Overview

The goal of this competition is to **predict whether a passenger survived the Titanic shipwreck** using data such as age, gender, ticket class, and more. Despite the tragedy, this dataset provides a compelling opportunity to explore binary classification using real-world data.

### 🎯 Objective

> **Predict survival on the Titanic**: Build a machine learning model that answers the question, *"What sorts of people were more likely to survive?"*

---

## 🗂️ Dataset

The competition dataset consists of two main files:

- `train.csv` — Contains data of 891 passengers including survival status.
- `test.csv` — Contains data of 418 passengers without survival status (to be predicted).
- `gender_submission.csv` — An example of a valid submission file.

Each entry includes information like:

- PassengerId
- Name
- Sex
- Age
- Pclass (ticket class)
- SibSp (siblings/spouses aboard)
- Parch (parents/children aboard)
- Fare
- Embarked (port of embarkation)

---

## 🧠 Approach

1. **Data Cleaning & Exploration**
   - Handle missing values
   - Perform exploratory data analysis (EDA)

2. **Feature Engineering**
   - Convert categorical variables
   - Create new meaningful features

3. **Modeling**
   - Train models like Logistic Regression, Random Forest, XGBoost, etc.
   - Use cross-validation and grid search for model tuning

4. **Prediction**
   - Generate predictions on the `test.csv` dataset
   - Prepare submission file

---

## 📈 Evaluation Metric

The model is evaluated on **accuracy** — the percentage of correctly predicted survival outcomes.

**Submission File Format**:
A CSV file with exactly 418 rows (one for each test passenger) and 2 columns:
```csv
PassengerId,Survived
892,0
893,1
894,0
...
