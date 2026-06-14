# 💳 Credit Card Fraud Detection Using Machine Learning & Deep Learning

## Project Overview

Credit card fraud represents one of the most significant challenges in the financial industry.

The objective of this project is to build and evaluate multiple Machine Learning and Deep Learning models capable of detecting fraudulent credit card transactions while minimizing false negatives and false positives.

This project follows a complete end-to-end Data Science workflow including:

* Business Understanding
* Data Cleaning
* Exploratory Data Analysis
* Imbalanced Data Handling
* Feature Engineering
* Machine Learning Modeling
* Deep Learning Modeling
* Model Evaluation
* Business Recommendations

---

# Business Problem

Fraudulent transactions represent a very small fraction of all transactions, making fraud detection a highly imbalanced classification problem.

Financial institutions require systems capable of:

* Detecting fraudulent activity quickly
* Minimizing financial losses
* Reducing false positives
* Maintaining customer trust

---

# Dataset

Dataset: Credit Card Fraud Detection Dataset

Characteristics:

* 284,807 transactions
* 30 features
* Highly imbalanced classes
* PCA-transformed confidential features
* Binary classification target

Target:

* 0 = Legitimate Transaction
* 1 = Fraudulent Transaction

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
* XGBoost
* TensorFlow
* Keras
* Jupyter Notebook

---

# Exploratory Data Analysis

### Class Distribution

<p align="center">
  <img src="images/class_distribution.PNG" width="800">
</p>

Key Finding:

The dataset is extremely imbalanced, with fraudulent transactions representing less than 1% of all observations.

---

### Transaction Amount Analysis

<p align="center">
  <img src="images/amount_distribution.png" width="800">
</p>

Key Finding:

Fraudulent transactions tend to occur more frequently among lower transaction amounts.

---

### Correlation Analysis

<p align="center">
  <img src="images/heatmqo.PNG" width="800">
</p>

Key Finding:

Several PCA-transformed features demonstrate strong relationships with fraudulent activity.

---

# Handling Class Imbalance

To address severe class imbalance:

* SMOTE (Synthetic Minority Oversampling Technique) was applied
* Minority class samples were synthetically generated
* Model learning improved significantly

<p align="center">
  <img src="images/smote.PNG" width="800">
</p>

---

# Models Evaluated

### Logistic Regression

Advantages:

* Fast
* Interpretable
* Strong baseline model

---

### K-Nearest Neighbors

Advantages:

* Non-parametric
* Simple decision boundaries

---

### Support Vector Machine

Advantages:

* Effective on complex boundaries
* Strong classification performance

---

### Decision Tree

Advantages:

* Highly interpretable
* Easy visualization

---

### Random Forest

Advantages:

* Reduced overfitting
* Strong generalization

---

### XGBoost

Advantages:

* State-of-the-art boosting algorithm
* Excellent fraud detection performance

---

### Neural Network

Architecture:

* Dense Layers
* Dropout Regularization
* Binary Classification Output

<p align="center">
  <img src="images/loss vs.PNG" width="800">
</p>

---

# Model Evaluation

Metrics Used:

* Precision
* Recall
* F1 Score
* ROC Curve
* AUC Score
* Confusion Matrix

---

## ROC Curve Comparison

<p align="center">
  <img src="images/ruccurve.PNG" width="800">
</p>

---

## AUC Score Comparison

<p align="center">
  <img src="images/auc_comparaison.PNG" width="800">
</p>

---

## Final Model Comparison



---

# Key Findings

* Accuracy alone was misleading due to extreme class imbalance.
* Recall was the most important metric because missing fraud is costly.
* Ensemble models significantly outperformed simpler algorithms.
* Random Forest achieved the strongest balance between fraud detection and false positive control.
* XGBoost delivered highly competitive performance.
* Neural Networks demonstrated strong learning capability but required additional tuning.

---

# Business Recommendations

* Prioritize recall over raw accuracy.
* Deploy ensemble models for production environments.
* Continuously retrain models using fresh transaction data.
* Combine machine learning models with rule-based fraud systems.
* Implement real-time fraud monitoring pipelines.

---

# Skills Demonstrated

* Data Cleaning
* EDA
* Feature Scaling
* Imbalanced Data Handling
* SMOTE
* Classification Modeling
* Hyperparameter Tuning
* Model Evaluation
* Deep Learning
* Business Analytics
* Data Storytelling

---

# Future Improvements

* Autoencoders for anomaly detection
* Isolation Forest
* Ensemble Stacking
* Real-Time Fraud Detection Pipeline
* Explainable AI (SHAP)
* Fraud Risk Scoring System

---

# Author

Oualid GASMI

Data Analyst | Data Scientist | Machine Learning Enthusiast
