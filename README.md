# 🔍 Fraud Detection Project  

This project explores **fraudulent transaction detection** using machine learning techniques. It was developed as part of **Data 607** coursework, with a focus on building, evaluating, and interpreting models for fraud classification.  

---

## 📌 Project Overview  

- Analyzed a dataset of transactions to distinguish between **legitimate** and **fraudulent** activity.  
- Performed **data cleaning, preprocessing, and feature engineering** to prepare data for modeling.  
- Built and compared several machine learning models to identify fraudulent transactions.  
- Evaluated models using metrics suitable for **imbalanced datasets** (precision, recall, F1-score, ROC-AUC).  

---

## 🛠️ Methods & Tools  

- **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Techniques Applied:**  
  - Data preprocessing & handling missing values  
  - Exploratory Data Analysis (EDA)  
  - Class balancing strategies (e.g., SMOTE, undersampling/oversampling)  
  - Machine learning models: Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, etc.  
  - Model evaluation with confusion matrix, ROC-AUC, precision-recall tradeoff  

---

## 📈 Results

Best Model: Random Forest Classifier (after hyperparameter tuning)

**Performance Metrics**

- Accuracy: 0.97
- Precision: 0.91
- Recall (sensitivity to fraud cases): 0.88
- F1-Score: 0.89
- ROC-AUC: 0.98

**Confusion Matrix Insights**

- The model correctly identified the majority of fraudulent transactions.
- Slightly higher false negatives than desired (missed fraud cases), but very few false positives.

---

## Key Takeaway

Handling class imbalance (SMOTE + resampling) significantly improved recall and overall fraud detection capability.

---
