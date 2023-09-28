# ML_HR_Attrition
## Employee Attrition Prediction with Machine Learning
# Overview
This repository contains a dataset and machine learning models for predicting employee attrition. Employee attrition refers to the phenomenon of employees leaving an organization voluntarily or involuntarily. Predicting attrition is crucial for HR and management to take proactive measures to retain valuable employees. In this project, we have used various machine learning models to predict attrition based on employee-related features.

# Dataset
The dataset used in this project contains information about employees, including their age, daily rate, department, education, and more. The primary target variable is "Attrition," which indicates whether an employee has left the company (Yes) or not (No). The dataset is structured as follows:

Age: The age of the employee.
BusinessTravel: The frequency of business travel (e.g., Travel_Rarely, Travel_Frequently).
DailyRate: The daily rate of the employee.
Department: The department in which the employee works (e.g., Sales, Research & Development).
DistanceFromHome: The distance of the employee's home from the workplace.
Education: The level of education of the employee.
EducationField: The field of education of the employee.
EmployeeCount: A constant value (1) indicating the number of employees in the dataset.
EmployeeNumber: A unique identifier for each employee.
Among other features

# Machine Learning Models
We have trained and evaluated three different machine learning models to predict employee attrition using the dataset. Here are the models and their accuracy scores:

Random Forest Model : Accuracy: 0.8641
Decision Tree Model: Accuracy: 0.8016
Logistic Regression Model: Accuracy: 0.8886
These models were trained on the dataset to learn the patterns and relationships between employee attributes and attrition. The models can be used to make predictions on new data to identify employees who might be at risk of leaving the company.

# Conclusion
Predicting employee attrition is essential for organizations to retain their workforce and maintain productivity. In this project, we have demonstrated the use of machine learning models to predict attrition based on employee-related features
