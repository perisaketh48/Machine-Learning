# 🤖 Machine Learning Projects

Welcome to my Machine Learning repository 🚀
This repo contains a collection of hands-on ML projects where I explore data, build models, and evaluate performance using real-world datasets.

---

## 📌 What You'll Find Here

* End-to-end Machine Learning workflows
* Data preprocessing & feature engineering
* Model building & evaluation
* Real-world problem solving

---

## 🧠 Skills Demonstrated

* Data Cleaning & Preprocessing
* Feature Encoding (One-Hot, Binary)
* Model Selection & Comparison
* Cross Validation (Stratified K-Fold)
* Evaluation Metrics (Precision, Recall, F1 Score)
* Handling Imbalanced Data (SMOTE, class_weight)
* Hyperparameter Tuning (GridSearchCV)
* Pipeline Building (Scikit-learn & Imbalanced-learn)
* Avoiding Data Leakage

---

## 📂 Projects Included

### 🎯 Campus Placement Prediction

* Predicts whether a student will be placed or not
* Models used: Logistic Regression, SVM, Random Forest
* Best Model: **SVM (F1 Score ≈ 0.91)**
* Techniques:

  * One-hot encoding
  * Feature scaling
  * Stratified Cross Validation

---

### 📉 Telco Customer Churn Prediction

* Predicts whether a customer will churn or not
* Business use-case: Helps companies reduce customer loss

#### 🔍 Key Features:

* Handled missing values (`TotalCharges`)
* Converted categorical data using **ColumnTransformer + OneHotEncoder**
* Used **train-test split with stratification**
* Focused on **Recall** (important for churn detection)

#### ⚙️ Models & Techniques:

* Random Forest Classifier
* Hyperparameter tuning using **GridSearchCV**
* Compared 3 approaches:

  1. No class balancing
  2. `class_weight='balanced'`
  3. **SMOTE (Oversampling)**

#### 🚀 Advanced Concepts:

* Used **Imbalanced-learn Pipeline** to avoid data leakage
* Applied SMOTE only on training folds
* Evaluated using:

  * Confusion Matrix
  * Classification Report

---

*(More projects will be added here...)*

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas, NumPy
* Scikit-learn
* Imbalanced-learn

---

## 🚀 Approach

Each project follows a structured pipeline:

1. Data Understanding
2. Data Cleaning
3. Feature Engineering
4. Model Training
5. Evaluation
6. Testing with custom inputs

---

## 📈 Goal

To build practical ML solutions while focusing on:

* Correct methodology
* Avoiding common pitfalls
* Writing clean and reusable code

---

## 🔥 Future Improvements

* Advanced hyperparameter tuning
* Model explainability (SHAP, Feature Importance)
* Deployment (Web Apps / APIs)

---

## 👨‍💻 Author

**Saketh**
Machine Learning Enthusiast

---

⭐ If you find this repo useful, feel free to star it!
