# HR-Analytics-EmployeePerfomace
An end-to-end HR analytics project analyzing employee attrition using the IBM dataset. Includes data cleaning, EDA, and predictive modeling with XGBoost and logistic regression to identify key factors influencing turnover. Achieved 91% accuracy and 0.97 ROC-AUC.
 Project Title: IBM HR Analytics – Employee Attrition & Performance
 Overview
This project analyzes employee attrition using IBM’s HR Analytics dataset.

Combines descriptive and predictive analytics to uncover key factors driving turnover.

Uses Python for EDA, preprocessing, and machine learning modeling.

 Key Objectives
Identify departments and roles with high attrition.

Analyze demographic and workplace factors contributing to employee turnover.

Build a predictive model to classify employees likely to leave.

 Data Preparation
Dropped constant and ID columns (e.g., EmployeeNumber, Over18).

Encoded categorical variables using label and one-hot encoding.

Handled outliers in MonthlyIncome using IQR method.

Performed train-test split for modeling.

 Exploratory Analysis
Evaluated attrition by department, gender, age, and job satisfaction.

Found higher attrition among younger employees, Sales reps, and those with low satisfaction.

 Predictive Modeling
Built models using Logistic Regression and XGBoost.

Achieved 91% accuracy and 0.97 ROC-AUC with XGBoost.

Identified key predictors: Overtime, Business Travel, Marital Status, Years at Company.

 Visualizations
Included bar charts, KDE plots, and ROC curves for interpretability.

 Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

 Dataset
IBM HR Analytics Attrition Dataset – Kaggle

