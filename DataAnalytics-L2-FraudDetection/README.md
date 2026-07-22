# Credit Card Fraud Detection using Machine Learning

## Oasis Infobyte Data Analytics Internship

### Level 2 - Task 3: Fraud Detection

## Project Overview

This project develops a machine learning pipeline to detect fraudulent credit card transactions from a highly imbalanced dataset. The project focuses on handling class imbalance using SMOTE, training multiple classification models, and evaluating their performance using appropriate metrics for fraud detection.

---

## Objective

- Analyze fraudulent and genuine transaction patterns.
- Handle severe class imbalance using SMOTE.
- Build machine learning models for fraud detection.
- Compare multiple models using evaluation metrics.
- Recommend the most suitable model for deployment.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## Dataset

Dataset Used:
**Credit Card Fraud Detection Dataset**

- Total Transactions: 284,807
- Fraudulent Transactions: 492
- Genuine Transactions: 284,315

The dataset is highly imbalanced, making fraud detection a challenging classification problem.

---

## Project Workflow

1. Data Loading
2. Data Inspection
3. Exploratory Data Analysis (EDA)
4. Class Imbalance Analysis
5. Feature Scaling
6. SMOTE Oversampling
7. Train-Test Split using Stratification
8. Logistic Regression Model
9. Random Forest Model
10. Model Evaluation
11. ROC Curve Analysis
12. Feature Importance Analysis
13. Model Comparison
14. Business Recommendations

---

## Exploratory Data Analysis

The project includes:

- Class Distribution
- Transaction Amount Distribution
- Fraud vs Non-Fraud Box Plot
- Time-of-Day Analysis
- Transaction Time Distribution
- Correlation Heatmap

---

## Machine Learning Models

- Logistic Regression
- Random Forest Classifier

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Project Outputs

The project generates:

- Model_Comparison.csv
- Feature Importance Chart
- ROC Curve
- Confusion Matrices
- EDA Visualizations
- Customer Transaction Insights

All visualizations are stored inside the **images/** folder.

---

## Key Findings

- The dataset is extremely imbalanced.
- SMOTE significantly improves model learning.
- Random Forest outperformed Logistic Regression.
- Recall is more important than Accuracy for fraud detection.
- Feature importance helps identify the most influential variables contributing to fraud prediction.

---

## Business Recommendations

- Deploy the Random Forest model for fraud detection.
- Continuously retrain the model with new transaction data.
- Prioritize Recall to minimize undetected fraud.
- Combine machine learning with rule-based fraud detection systems.
- Implement real-time fraud monitoring for immediate alerts.

---

## Project Structure

```
DataAnalytics-L2-FraudDetection/
│
├── Fraud_Detection.ipynb
├── creditcard.csv
├── Model_Comparison.csv
├── images/
│
└── README.md
```

---

## Author

**Rachaita Sarkar**

BBA (Finance) Student

Techno Main Salt Lake

Oasis Infobyte Data Analytics Internship
