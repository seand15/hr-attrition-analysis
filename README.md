# Employee Attrition Analysis and Prediction

## Overview
This project analyzes employee attrition using a structured data science approach, including data cleaning, exploratory analysis, and predictive modeling.

## Objective
The goal of this project is to identify factors associated with employee attrition and build a model to predict employees at risk of leaving.

## Dataset
The dataset contains employee-level information including demographics, job characteristics, compensation, and work-related factors.

## Key Findings
- Employees who work overtime exhibit higher attrition rates
- Lower monthly income is associated with higher attrition
- Employees with shorter tenure are more likely to leave
- Multiple factors (income + overtime) interact to influence attrition

## Modeling
A logistic regression model was used to predict attrition:
- Accuracy: ~87.8%
- Recall for attrition: 44% (improved to 59% using class balancing)

## Key Insight
While the model achieves strong overall accuracy, it struggles to identify employees who leave, highlighting the impact of class imbalance and the importance of evaluation beyond accuracy.

## Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn

## Project Structure
hr-attrition-analysis/
│
├── notebooks/
│ └── 01_attrition_analysis.ipynb
├── images/
└── README.md
