# Machine-Learning-Prediction---Employee-Attrition

## Overview
This project analyzes employee attrition data to identify the factors associated with employees leaving the company and to build machine learning models that predict employees who are at risk of leaving in the future. The analysis was completed using Python and several supervised machine learning classification algorithms.
## Project Objectives
* Analyze the factors influencing employee attrition.
* Identify the characteristics of employees who are more likely to leave.
* Build predictive models to identify employees at risk of leaving.
* Compare multiple machine learning algorithms and select the best-performing model.

## Dataset
The dataset consists of two employee records:
* **Existing Employees**
* **Employees Who Have Left**

Each employee record includes the following features:
* Satisfaction Level
* Last Evaluation
* Number of Projects
* Average Monthly Hours
* Time Spent at the Company
* Work Accident
* Promotion in the Last 5 Years
* Department
* Salary

To train the classification models, the two datasets were combined into a single dataset. An **Employee Status** target column was created, where:
* **1** = Current Employee
* **0** = Employee Left
The remaining variables were used as predictor features.

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Learning Outcomes
This project demonstrates:
* Exploratory Data Analysis (EDA)
* Data preprocessing
* One-Hot Encoding
* Feature Scaling
* Supervised Machine Learning
* Model evaluation using confusion matrices and accuracy scores
* Employee attrition prediction
