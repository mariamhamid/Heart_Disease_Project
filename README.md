# ❤️ Heart Disease Classification Project

## 📌 Project Overview
This project focuses on predicting the presence of heart disease using supervised machine learning classification models.  
The main goal is to understand the full machine learning workflow — from data preparation to model evaluation and hyperparameter tuning — rather than advanced feature engineering.

---

## 🎯 Project Goals
- Prepare data for modeling
- Train and compare different classification algorithms
- Evaluate models using multiple performance metrics
- Apply hyperparameter tuning techniques
- Export the final trained model for later use

---

## 🧠 Machine Learning Workflow
1. Data loading and basic preprocessing  
2. Train / Test data splitting  
3. Model training using multiple classifiers  
4. Model evaluation using different metrics  
5. Hyperparameter tuning:
   - Grid Search
   - Randomized Search
6. Exporting the trained model

> ⚠️ No feature engineering was applied in this project.  
> The focus is on model comparison and evaluation.

---

## 🤖 Models Used
- LogisticRegression  
- RandomForestClassifier  
- KNeighborsClassifier
- SVC
- LinearSVC

Each model was evaluated and compared to identify strengths and weaknesses.

---

## 📊 Dataset
- Dataset: **Heart Disease Dataset**
- Target Variable:
  - `1` → Presence of heart disease
  - `0` → No heart disease

> The dataset file is not included in this repository.  

---

## 📈 Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve
- Cross_validation

Using multiple metrics helps provide a more reliable assessment than accuracy alone.

---

## ⚙️ Hyperparameter Tuning
Two optimization techniques were applied:
- **GridSearchCV** for exhaustive parameter search
- **RandomizedSearchCV** for efficient parameter exploration

These methods helped improve model performance and stability.

---

## 📦 Model Export
The best-performing model was exported using `joblib` for reuse in future predictions or deployment.

---
## Future Work

Apply feature engineering techniques

Address class imbalance

Experiment with ensemble and boosting methods

Deploy the model using a web or API interface

