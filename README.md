# Credit Card Fraud Detection 💳 using Machine Learning

## Project Overview
This project focuses on detecting **fraudulent credit card transactions** using **Logistic Regression**.  
The dataset is highly imbalanced, making fraud detection a challenging classification problem.

---

## Why This Project?
Credit card fraud detection is a real-world problem where **data imbalance, false negatives, and model reliability** are critical challenges.  
This project demonstrates my ability to handle imbalanced datasets, apply machine learning techniques effectively, and build a practical classification model that mirrors real financial risk scenarios. It also reflects my interest in applying AI and data science to **FinTech and machine learning-focused applications**.

---

## Objective
To build a machine learning model that accurately classifies transactions as:
- **0 → Legitimate**
- **1 → Fraudulent**

---

##  Dataset Information 📊
- Transactions are anonymized using **PCA transformation**
- Features: `V1` to `V28`, `Amount`, `Time`
- Target variable: `Class`
- Highly imbalanced dataset (~0.2% fraud cases)

---

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## Approach
1. Data loading and exploration
2. Handling class imbalance using **under-sampling**
3. Feature and label separation
4. Train-test split with stratification
5. Model training using Logistic Regression
6. Performance evaluation

---

## Model Used
**Logistic Regression**
- Suitable for binary classification
- Efficient and interpretable
- Performs well on PCA-transformed data

---

## Results
- Achieved high accuracy on both training and test datasets
- Balanced dataset improved fraud detection capability

> Note: Accuracy alone is not sufficient for fraud detection.  
Future improvements include Precision, Recall, F1-score, and ROC-AUC evaluation.

---

## 🔮Future Improvements
- Use **SMOTE** for better imbalance handling
- Try advanced models like **Random Forest, XGBoost**
- Add evaluation metrics such as **Precision-Recall Curve**
- Deploy as a web app using **Flask / Streamlit**

---

## Authors
**Aniket Kumar**, **Param Vansh Singh** & **Krishnaveni**

Aniket Kumar - Undergraduate | Computer Science  
Interested in AI, Data Science & FinTech
