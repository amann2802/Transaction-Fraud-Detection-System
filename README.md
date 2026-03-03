# Transaction Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on building a Machine Learning-based fraud detection system to identify fraudulent financial transactions using behavioral, transactional, and risk-based features.

The dataset was highly imbalanced, where fraudulent transactions represented a very small percentage of total transactions. To address this challenge, advanced preprocessing and imbalance handling techniques such as SMOTE were applied to improve model performance on minority class detection.

---

## 🎯 Problem Statement

Financial fraud detection is a high-risk domain where missing a fraudulent transaction (False Negative) can result in significant financial losses.  

The objective of this project is to:

- Detect fraudulent transactions accurately  
- Minimize False Negatives  
- Optimize Recall and ROC-AUC instead of focusing only on accuracy  

---

## 🛠️ Project Workflow

### 1️⃣ Data Preprocessing
- Data cleaning
- Handling missing values
- Encoding categorical variables
- Feature scaling

### 2️⃣ Feature Engineering
Engineered behavioral and risk-based features including:

- Transaction velocity ratio
- Failed transaction ratio
- Geo-risk score
- Transaction amount deviation
- Time-based features (hour, day patterns)

### 3️⃣ Handling Class Imbalance
- Applied **SMOTE (Synthetic Minority Oversampling Technique)**
- Improved minority class learning
- Balanced dataset before model training

### 4️⃣ Exploratory Data Analysis (EDA)
- Fraud vs Non-Fraud distribution analysis
- Correlation analysis
- Risk-based feature impact visualization
- Behavioral anomaly detection patterns

### 5️⃣ Model Development
Trained and evaluated the following models:

- Random Forest Classifier
- XGBoost Classifier

### 6️⃣ Model Evaluation Metrics
Since fraud detection is imbalance-sensitive, the following metrics were prioritized:

- Precision
- Accuracy
- Recall
- F1-Score
- ROC-AUC Score

Special focus was given to **Recall** to minimize False Negatives.

---

## 🔍 Key Insights

The final model successfully captured behavioral anomalies such as:

- High transaction velocity
- Large deviation from normal user spending behavior
- Sudden geographic location changes
- Low KYC verification levels
- High IP and merchant risk scores

---

## 📊 Business Impact

- Reduced risk of financial loss by minimizing undetected fraud cases
- Improved fraud detection capability in imbalanced environments
- Demonstrated practical implementation of risk analytics techniques

---

## 🚀 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn

---



---

## 📌 Conclusion

This project demonstrates practical expertise in fraud analytics, feature engineering, imbalance handling, and performance-driven model optimization. It reflects a strong understanding of real-world financial risk modeling and anomaly detection systems.

