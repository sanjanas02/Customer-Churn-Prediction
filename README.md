# Customer Churn Prediction

## Project Overview

Customer churn prediction is a Machine Learning project that identifies customers who are likely to stop using a company's services. Predicting churn helps businesses improve customer retention, reduce revenue loss, and make data-driven decisions.

This project uses the Telco Customer Churn Dataset and compares multiple machine learning algorithms to determine the most effective model for churn prediction.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographic information, account details, and service usage data.

### Features Include:
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Models

The following classification algorithms were implemented and compared:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. Gradient Boosting Classifier

---

## Project Workflow

### 1. Data Collection
- Loaded the Telco Customer Churn dataset.

### 2. Data Preprocessing
- Handled missing values.
- Converted categorical variables into numerical format.
- Scaled numerical features.

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer churn patterns.
- Visualized feature distributions.
- Studied relationships between variables.

### 4. Model Training
- Split data into training and testing sets.
- Trained multiple machine learning models.

### 5. Model Evaluation
- Evaluated performance using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC Score

### 6. Model Comparison
- Compared model performance to identify the best-performing algorithm.

---

## Results

| Model | Accuracy |
|---------|---------|
| Gradient Boosting | 80.07% |
| Logistic Regression | 79.93% |
| SVM | 79.22% |
| Random Forest | 78.01% |
| Decision Tree | 70.89% |

### Best Performing Model

**Gradient Boosting** achieved the highest accuracy of **80.07%** on the Telco Customer Churn Dataset.

---

## Evaluation Metrics

| Model | Precision | Recall | F1 Score | ROC-AUC |
|---------|---------|---------|---------|---------|
| Logistic Regression | 0.6490 | 0.5269 | 0.5816 | 0.8388 |
| Decision Tree | 0.4512 | 0.4597 | 0.4554 | 0.6299 |
| Random Forest | 0.6171 | 0.4462 | 0.5179 | 0.8135 |
| SVM | 0.6563 | 0.4516 | 0.5350 | 0.7867 |
| Gradient Boosting | 0.6586 | 0.5134 | 0.5770 | 0.8380 |

---

## Visualizations

### Model Comparison

![Comparison Table](images/Comparison%20Table.png)

### Customer Churn Distribution

![Customer Churn Distribution](images/Customer%20Churn%20Distribution.png)

### Feature Importance Analysis

![Feature Importance Analysis](images/Feature%20Importance%20Analysis.png)

---

## Business Applications

- Customer Retention Strategies
- Revenue Protection
- Customer Risk Assessment
- Marketing Campaign Optimization
- Customer Relationship Management

---

## Repository Structure

```text
Customer-Churn-Prediction/
│
├── dataset/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── images/
│   ├── Comparison Table.png
│   ├── Customer Churn Distribution.png
│   └── Feature Importance Analysis.png
│
├── notebook/
│   └── Customer_Churn_Prediction.ipynb
│
├── README.md
└── .gitignore
```

---

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- XGBoost Implementation
- Model Deployment using Streamlit or Flask
- Real-time Churn Prediction Dashboard

---

## Author

**Sanjana S**

Machine Learning & Data Science Enthusiast
