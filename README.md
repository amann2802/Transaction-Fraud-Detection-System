# Transaction-Fraud-Detection-System
This project focuses on building a machine learning-based fraud detection system to identify fraudulent financial transactions using behavioral, transactional, and risk-based features.
The dataset contained highly imbalanced classes, where fraudulent transactions represented a very small percentage of total transactions. To address this challenge, advanced preprocessing and imbalance handling techniques such as SMOTE were applied to improve model performance on minority class detection.The project involved end-to-end data science workflow including:
1.Data cleaning and preprocessing.

2.Handling missing values

4.Feature engineering (transaction velocity, failure ratio, geo-risk, amount deviation, time-based features)
5.Class imbalance treatment using SMOTE
6.Exploratory Data Analysis (EDA) to identify fraud patterns
7.Model training using Random Forest and XGBoost
8.Performance evaluation using Precision, Recall, F1-score, and ROC-AUC

Special focus was given to optimizing Recall to minimize false negatives, as missing fraudulent transactions carries high financial risk.
