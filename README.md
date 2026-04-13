# Employee Attrition Analysis and Prediction
The dataset contains 1,470 employee records with 35 features.

## Overview
This project analyzes employee attrition using a structured data science approach, including data cleaning, exploratory analysis, and predictive modeling.

## Project Type
End-to-end data science project (EDA + Machine Learning)

## Objective
The goal of this project is to identify factors associated with employee attrition and build a model to predict employees at risk of leaving.

## Dataset
The dataset contains employee-level information including demographics, job characteristics, compensation, and work-related factors.

## Workflow
1. Data cleaning and preprocessing  
2. Exploratory data analysis (EDA)  
3. Feature encoding and scaling  
4. Model training (Logistic Regression)  
5. Model evaluation (accuracy, precision, recall)  
6. Handling class imbalance
   
## Key Findings
- Employees who work overtime exhibit higher attrition rates
- Lower monthly income is associated with higher attrition
- Employees with shorter tenure are more likely to leave
- Multiple factors (income + overtime) interact to influence attrition

## Modeling
A logistic regression model was used to predict attrition:
- Accuracy: ~87.8%
- Recall for attrition: 44% (improved to 59% using class balancing)

## Modeling Approach
Logistic Regression was used as a baseline classification model due to its interpretability. Features were scaled using StandardScaler, and categorical variables were one-hot encoded. The dataset was split into training and testing sets (80/20).

## Key Insight
While the model achieves strong overall accuracy, it performs significantly worse in identifying employees who leave (Attrition = 1), with recall as low as 44%. This highlights the importance of evaluating models beyond accuracy, particularly in imbalanced classification problems.

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
