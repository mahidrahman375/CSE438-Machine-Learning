# 🫀 Heart Disease Prediction using K-Nearest Neighbours (KNN)

## 🎯 Project Overview

This project implements a **Heart Disease Prediction system** using the **K-Nearest Neighbours (KNN) classification algorithm**.

The goal is to build a complete machine learning pipeline that can predict whether a patient has heart disease based on clinical and lifestyle features.

The project follows a full data science workflow including:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature encoding and scaling
* Model training using KNN
* Performance evaluation and error analysis

---

## 🧠 Problem Statement

Cardiovascular diseases are one of the leading causes of death worldwide. Early prediction using machine learning can assist in timely diagnosis and treatment.

This project aims to:

* Predict heart disease status (Yes/No)
* Analyze model performance under class imbalance conditions
* Evaluate the effectiveness of KNN for medical classification tasks

---

## 📊 Dataset Description

* **Source:** Kaggle (Oktay Rdeki Heart Disease Dataset)
* **Samples:** 10,000 patient records
* **Features:** 21 clinical + lifestyle attributes
* **Target:** Heart Disease Status (Binary: Yes / No)
* **Class Distribution:**

  * No Heart Disease: ~80%
  * Heart Disease: ~20%

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Missing value imputation (Median for numerical, Mode for categorical)
* One-hot encoding for categorical variables
* Feature scaling using StandardScaler
* Train-test split (80/20, stratified)

### 2. Model Used

* K-Nearest Neighbours (KNN)
* k = 5
* Euclidean distance metric

### 3. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 📈 Results

* **Test Accuracy:** 79.00%

### Key Observation:

* High performance on majority class (No Heart Disease)
* Very low recall on minority class (Heart Disease)
* Strong impact of class imbalance on model performance

---

## ⚠️ Key Challenges

* Severe class imbalance (80:20 ratio)
* Poor minority class recall
* High dimensionality after encoding
* Missing data in multiple features (especially Alcohol Consumption)

---

## 📉 Confusion Matrix Summary

* True Positives: 8
* False Negatives: 392
* True Negatives: 1572
* False Positives: 28

---

## 💡 Key Learnings

* Accuracy is not enough for imbalanced datasets
* KNN is sensitive to feature scaling and data distribution
* Medical datasets require careful handling of recall and false negatives
* Proper preprocessing is critical for model performance

---

## 🚀 Future Improvements

* Apply SMOTE or oversampling techniques
* Try Logistic Regression, Random Forest, XGBoost
* Hyperparameter tuning for optimal k
* Use AUC-ROC for better evaluation
* Feature selection to reduce dimensionality

---

## 🧰 Tools & Libraries

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 📌 Conclusion

This project demonstrates an end-to-end machine learning pipeline for heart disease prediction using KNN. While the model achieves reasonable accuracy, it highlights the importance of handling class imbalance and choosing appropriate evaluation metrics for real-world medical applications.

---

## 📎 Author

**Yeamin Rahman Mahid**
CSE, East West University

