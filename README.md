# Customer Churn Prediction for Telecom

## 📌 Overview
Customer churn is a critical metric for telecom companies, as retaining customers is often more cost-effective than acquiring new ones. This project aims to predict which customers are likely to churn (stop using the service) based on their usage patterns, demographics, and customer service interactions. The goal is to identify at-risk customers and recommend strategies to retain them.

---

## 🎯 Problem Statement
- **Objective**: Predict whether a customer will churn (binary classification: Churn = 1, No Churn = 0).
- **Key Challenges**: Imbalanced dataset, identifying key drivers of churn.
- **Business Impact**: Reducing churn can significantly improve customer retention and revenue.

---

## 📂 Dataset
The dataset used in this project is the [Telco Customer Churn dataset from Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn). It contains information about:
- Customer demographics (e.g., gender, age).
- Services subscribed (e.g., phone, internet).
- Account information (e.g., tenure, contract type).
- Target variable: `Churn` (Yes/No).

---

## 🛠️ Tools and Technologies
- **Programming Language**: Python
- **Libraries**:
  - Pandas, NumPy: Data manipulation and analysis.
  - Scikit-learn: Machine learning models and evaluation.
  - Matplotlib, Seaborn: Data visualization.
  - XGBoost: Advanced machine learning model.
- **Environment**: Jupyter Notebook.

---

## 🚀 Project Steps
1. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Scale numerical features.
2. **Exploratory Data Analysis (EDA)**:
   - Analyze correlations between features and churn.
   - Visualize key trends (e.g., churn by tenure, monthly charges).
3. **Model Building**:
   - Train a Random Forest Classifier.
   - Evaluate the model using accuracy, precision, recall, and F1-score.
4. **Feature Importance**:
   - Identify the most important features driving churn.
5. **Recommendations**:
   - Provide actionable insights to reduce churn.

---

## 📊 Results
### Model Performance
- **Accuracy**: 87%
- **Confusion Matrix**:
- [[950 50]
  [120 180]]

- **Classification Report**:
-           precision    recall  f1-score   support
       0       0.89      0.95      0.92      1000
       1       0.78      0.60      0.68       300
accuracy                           0.87      1300

### Key Drivers of Churn
- **Top Features**:
1. Tenure
2. Monthly Charges
3. Contract Type

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/banner2399/Customer-Churn-Prediction.git

  
