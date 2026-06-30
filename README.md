#  Loan Approval Prediction using Ensemble Learning

An end-to-end Machine Learning project that predicts whether a loan application will be approved using multiple Ensemble Learning algorithms. The project compares several classification models, performs hyperparameter tuning, evaluates model performance using multiple metrics, and explains predictions through feature importance analysis.

---

##  Project Overview

Financial institutions process thousands of loan applications every day. Accurately predicting loan approval helps reduce financial risk while ensuring fair lending decisions.

In this project, multiple Ensemble Learning techniques are implemented and compared to identify the best-performing model for loan approval prediction.

---

##  Objectives

- Perform Exploratory Data Analysis (EDA)
- Handle missing values
- Engineer meaningful features
- Build a robust preprocessing pipeline
- Compare multiple classification models
- Tune the best-performing model
- Interpret feature importance
- Evaluate using multiple performance metrics

---

##  Dataset

**Source:** Kaggle Loan Prediction Dataset

**Target Variable**

- **Loan_Status**
  - **1 → Loan Approved**
  - **0 → Loan Rejected**

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

---

##  Workflow

### 1️⃣ Data Understanding

- Dataset overview
- Missing value analysis
- Duplicate detection
- Feature inspection

---

### 2️⃣ Exploratory Data Analysis

- Target distribution
- Numerical feature distributions
- Outlier detection
- Categorical feature analysis
- Correlation analysis

---

### 3️⃣ Data Cleaning

- Missing value imputation
- Data type corrections
- Duplicate removal

---

### 4️⃣ Feature Engineering

Created several new features:

- Total Income
- Loan-Income Ratio
- Family Size
- Income Per Person
- Log Transformed Income
- Log Transformed Loan Amount

---

### 5️⃣ Data Preprocessing

Implemented a Scikit-learn Pipeline using:

- ColumnTransformer
- OneHotEncoder
- Train/Test Split

---

### 6️⃣ Model Training

The following models were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Extra Trees Classifier
- AdaBoost Classifier
- Gradient Boosting Classifier
- HistGradient Boosting Classifier

---

### 7️⃣ Hyperparameter Tuning

RandomizedSearchCV was used to optimize the AdaBoost Classifier.

---

### 8️⃣ Model Explainability

- Feature Importance
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve

---

##  Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|----------|-----------|--------|----------|---------|
| AdaBoost | **90.24%** | **88.42%** | **98.82%** | **93.33%** | **84.94%** |
| Logistic Regression | 86.18% | 84.00% | 98.82% | 90.81% | 78.36% |
| Gradient Boosting | 86.18% | 86.17% | 95.29% | 90.50% | 80.54% |
| Extra Trees | 85.37% | 83.17% | 98.82% | 90.32% | 77.04% |
| Random Forest | 85.37% | 83.84% | 97.65% | 90.21% | 77.77% |
| HistGradient Boosting | 82.11% | 86.21% | 88.24% | 87.21% | 78.33% |
| Decision Tree | 78.05% | 88.16% | 78.82% | 83.23% | 77.57% |

---

##  Best Performing Model

🥇 **AdaBoost Classifier**

- Accuracy: **90.24%**
- Precision: **88.42%**
- Recall: **98.82%**
- F1 Score: **93.33%**
- ROC-AUC: **84.94%**

---

##  Repository Structure

```
Loan-Approval-Prediction/
│
├── notebook/
│   └── loan_approval_prediction.ipynb
│
├── images/
│   ├── target_distribution.png
│   ├── model_comparison.png
│   ├── feature_importance.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── precision_recall_curve.png
│
├── models/
│   └── loan_approval_model.pkl
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Future Improvements

- XGBoost
- LightGBM
- CatBoost
- SHAP Explainability
- Streamlit Web Application
- Model Deployment using Docker

---

##  Author

**Yuwin** or **Godofthunder2407**

GitHub: https://github.com/Yuwin2008

Discord Username: godofthunder_2407

---

 If you found this project useful, consider giving it a star!
