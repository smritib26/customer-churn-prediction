# customer-churn-prediction
# Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn is a critical challenge for businesses, as retaining existing customers is often more cost-effective than acquiring new ones. This project aims to predict customer churn using machine learning techniques and identify the key factors that influence customer retention.

The model was developed using the IBM Telco Customer Churn dataset and achieved an accuracy of **80%** in predicting customer churn.

---

## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer information including:

- Demographic details
- Account information
- Subscription services
- Billing details
- Customer churn status

**Target Variable:** Churn (Yes/No)

---

## Project Objectives

- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Identify patterns associated with customer churn
- Build a machine learning model for churn prediction
- Evaluate model performance
- Generate business insights to improve customer retention

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Project Workflow

### 1. Data Collection
Loaded the IBM Telco Customer Churn dataset.

### 2. Data Cleaning
- Removed unnecessary columns
- Handled missing values
- Converted data types where necessary

### 3. Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Examined customer demographics
- Studied service and contract patterns

### 4. Data Preprocessing
- Encoded categorical variables
- Prepared features for model training

### 5. Model Development
Implemented a Random Forest Classifier to predict customer churn.

### 6. Model Evaluation
Evaluated model performance using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Results

| Metric | Value |
|----------|----------|
| Model | Random Forest Classifier |
| Accuracy | 80% |

### Key Factors Influencing Churn

- Customer tenure
- Monthly charges
- Contract type
- Payment method
- Internet service type

---

## Business Insights

- Customers with month-to-month contracts are more likely to churn.
- Long-term customers show higher retention rates.
- Higher monthly charges are associated with increased churn risk.
- Contract duration plays an important role in customer loyalty.

---

## Future Improvements

- Hyperparameter tuning
- Feature selection techniques
- Comparison with other machine learning algorithms
- Deployment using Streamlit
- Real-time churn prediction dashboard

---
## Repository Structure

```
customer-churn-prediction/
│
├── customer_churn_prediction.ipynb
├── README.md
└── images/
```
## Feature Importance

![Feature Importance](images/feature_importance.png)


---

## Author
Smriti Bhattacharjee

B.Tech Student | Data Science Enthusiast | Aspiring AI Professional


