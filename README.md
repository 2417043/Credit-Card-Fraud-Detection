# 💳 Credit Card Fraud Detection Using Isolation Forest and SMOTE

## 📌 Project Overview

Credit card fraud is one of the major challenges in the financial sector. Fraudulent transactions are extremely rare compared to normal transactions, making fraud detection a challenging machine learning problem.

This project uses the Credit Card Fraud Detection dataset to identify fraudulent transactions. The dataset is highly imbalanced, so SMOTE (Synthetic Minority Oversampling Technique) is used to balance the classes before applying the Isolation Forest algorithm for anomaly detection.

---

## 🎯 Objective

* Detect fraudulent credit card transactions.
* Handle highly imbalanced datasets using SMOTE.
* Train an Isolation Forest model for anomaly detection.
* Evaluate model performance using classification metrics.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
* Google Colab

---

## 📊 Dataset Information

The dataset contains credit card transactions made by European cardholders.

### Target Variable

* **Class = 0** → Normal Transaction
* **Class = 1** → Fraudulent Transaction

The dataset is highly imbalanced:

* Normal Transactions: 284,315
* Fraudulent Transactions: 492

---

## 🤖 Machine Learning Techniques

### 1. SMOTE (Synthetic Minority Oversampling Technique)

SMOTE generates synthetic samples of the minority class (fraud cases) to balance the dataset and improve model learning.

### 2. Isolation Forest

Isolation Forest is an anomaly detection algorithm that isolates rare observations and identifies potential fraudulent transactions.

---

## 🔄 Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Class Distribution Analysis
5. Train-Test Split
6. Feature Scaling
7. Handling Imbalanced Data using SMOTE
8. Training Isolation Forest Model
9. Model Evaluation
10. Result Analysis

---

## 📈 Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

---

## 📋 Results

### Model Performance

* Accuracy: 99.82%

### Observations

* The dataset was highly imbalanced.
* SMOTE successfully balanced the training data.
* Isolation Forest achieved high overall accuracy.
* Fraud detection remains challenging due to the rarity of fraudulent transactions.
* Accuracy alone is not sufficient for evaluating fraud detection systems.

---

## 🚀 Future Improvements

* Hyperparameter Tuning
* Random Forest Classifier
* XGBoost Classifier
* Logistic Regression
* Deep Learning Models
* Real-Time Fraud Detection Systems

---

## 👩‍💻 Author

**Sanika Jamale**

B.Tech Artificial Intelligence & Machine Learning (AIML)

Rajarambapu Institute of Technology (RIT)

GitHub: https://github.com/2417043

LinkedIn: https://www.linkedin.com/in/sanika-jamale-510909327/
