#  Heart Disease Classification & Imbalanced Data Handling

##  Project Overview

This project focuses on predicting the presence of heart disease using machine learning techniques while addressing the challenge of **imbalanced data**.

The project combines:

* Exploratory Data Analysis (EDA)
* Feature engineering & preprocessing
* Multiple classification models
* Advanced resampling techniques
* Model comparison

---

##  Dataset Information

The dataset includes medical attributes such as:

* Age
* Blood Pressure (trestbps)
* Cholesterol (chol)
* Maximum Heart Rate (thalach)
* ST Depression (oldpeak)

###  Target Variable:

* `target`

  * **1 → Heart Disease Present**
  * **0 → No Heart Disease**

---

##  Exploratory Data Analysis

Performed:

* Distribution plots for numerical features
* Target class distribution
* Boxplots for outlier detection
* Correlation heatmap
* Scatter plots to analyze relationships

---

##  Data Preprocessing

* One-Hot Encoding for categorical features
* Train/Test split with **stratification**
* Feature scaling using **StandardScaler**

---

##  Imbalanced Data Problem

The dataset contains class imbalance, which can bias models toward the majority class.

###  Techniques Used to Handle Imbalance:

* Class Weight Adjustment
* SMOTE (Synthetic Minority Oversampling)
* SMOTE + Tomek Links
* SMOTE + ENN

---

##  Models Implemented

###  Logistic Regression:

* Before balancing
* With class weights
* With SMOTE
* With SMOTE Tomek
* With SMOTE ENN

###  Decision Tree:

* Before balancing
* With class weights
* With SMOTE
* With SMOTE Tomek
* With SMOTE ENN

---

##  Model Evaluation

Metrics used:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

##  Key Results

* Handling imbalance significantly improved **Recall**
* SMOTE-based methods improved minority class detection
* Class weights provided a simple but effective improvement
* Decision Tree performed well but may overfit
* Logistic Regression provided more stable results

---

##  Visualization

* Confusion matrices for each model
* Feature importance (Decision Tree)
* Distribution and correlation plots

---

##  Key Insights

* Data imbalance strongly affects model performance
* Oversampling techniques improve detection of heart disease cases
* Recall is a critical metric in medical problems
* Model choice + sampling technique both matter

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn

---

##  Future Work

* Try advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Cross-validation
* Deploy model as a web application

---

##  Highlights

* Real-world problem: **Imbalanced medical dataset**
* Comparison of multiple resampling techniques
* Strong focus on model evaluation metrics
* Practical understanding of classification challenges

---
