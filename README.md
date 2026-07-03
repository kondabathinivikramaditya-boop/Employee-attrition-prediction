# Employee Attrition Prediction using Logistic Regression

## Project Overview

Employee attrition is one of the biggest challenges faced by organizations. Losing experienced employees increases recruitment costs, training costs, and affects overall productivity.

In this project, a Machine Learning model is developed using **Logistic Regression** to predict whether an employee is likely to leave the company based on various employee-related features.

This project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model saving.

---

## Problem Statement

The objective of this project is to predict whether an employee will leave the company (**Attrition = Yes**) or stay (**Attrition = No**) using historical employee data.

This helps HR departments identify employees who are at a higher risk of leaving and take preventive actions.

---

## Dataset

**Dataset Name:** IBM HR Employee Attrition Dataset

**Source:** Kaggle

The dataset contains employee information such as:

- Age
- Gender
- Department
- Job Role
- Monthly Income
- Business Travel
- Overtime
- Job Satisfaction
- Environment Satisfaction
- Years at Company
- Work-Life Balance
- and many more...

**Target Variable**

- Attrition
    - Yes
    - No

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Git
- GitHub

---

## Machine Learning Workflow

### 1. Data Collection

- Loaded the IBM HR Employee Attrition dataset.

### 2. Exploratory Data Analysis (EDA)

Performed various visualizations including:

- Count Plot
- Box Plot
- Heatmap
- Correlation Analysis

### 3. Data Preprocessing

- Checked missing values
- Removed unnecessary columns
- Label Encoding
- One-Hot Encoding
- Feature Scaling

### 4. Train-Test Split

- Training Data : 80%
- Testing Data : 20%

### 5. Model Building

Algorithm Used:

- Logistic Regression

### 6. Model Evaluation

The model was evaluated using:

- Training Accuracy
- Testing Accuracy
- Confusion Matrix
- Accuracy Score
- Precision
- Recall
- F1 Score
- Classification Report

### 7. Model Saving

The trained model was saved using Joblib.

```python
joblib.dump(model, "employee_attrition_model.pkl")
```

---

## Project Results

### Training Accuracy

**89.11%**

### Testing Accuracy

**87.76%**

The model performs well on unseen data and shows good generalization.

---

## Feature Importance

The Logistic Regression coefficients were analyzed to understand which employee characteristics most influenced attrition.

### Top Positive Factors

- OverTime
- BusinessTravel (Travel Frequently)
- YearsAtCompany
- MaritalStatus (Single)
- Number of Companies Worked

### Top Negative Factors

- YearsInCurrentRole
- YearsWithCurrManager
- TotalWorkingYears
- JobSatisfaction
- EnvironmentSatisfaction

---

## Project Structure

```
Employee-Attrition-Prediction/
│
├── dataset/
│   └── HR-Employee-Attrition.csv
│
├── emp_attrition.ipynb
│
├── employee_attrition_model.pkl
│
├── requirements.txt
│
└── README.md
```

---

## Future Improvements

Future enhancements for this project include:

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- LightGBM
- Hyperparameter Tuning using GridSearchCV
- Streamlit Web Application
- Model Deployment

---

## Learning Outcomes

Through this project, I learned:

- Data Cleaning
- Data Visualization
- Feature Engineering
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Logistic Regression
- Model Evaluation
- Feature Importance
- Saving Machine Learning Models
- Git and GitHub

---

## Author

**Vikramaditya Kondabathini**

B.Tech – Computer Science Engineering (Data Science)

GitHub:
https://github.com/kondabathinivikramaditya-boop

---

## Acknowledgement

Dataset provided by IBM and available on Kaggle for educational and research purposes.
