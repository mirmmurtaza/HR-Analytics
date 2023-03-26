# HR Analytics: Predicting Employee Behavior with Machine Learning

## Introduction
This project uses machine learning techniques to predict employee behavior and identify potential areas of concern in the Human Resources Analytics dataset, which contains information on employee satisfaction, years spent at the company, and whether or not an employee left the company. The goal of the project is to develop predictive models that can help HR professionals understand the factors that may retain the employees. The project uses exploratory data analysis (EDA), hyperparameter tuning, and model evaluation to achieve this goal.

## Dataset Description
The Human Resources Analytics dataset contains 10 columns and 14999 rows. Each row represents an employee and each column represents an attribute of the employee. The columns include satisfaction level, last evaluation, number of projects, average monthly hours, time spent at the company, whether or not the employee had a work accident, whether or not the employee left the company, whether or not the employee was promoted in the last five years, the department the employee worked in, and the salary of the employee. The dataset contains no missing values or duplicates.

## Exploratory Data Analysis
The EDA section of the project includes a variety of visualizations to help the reader gain a better understanding of the data. These visualizations include histograms, boxplots, barplots, countplots, and correlation heatmaps.

## Preprocessing and Feature Engineering
The preprocessing and feature engineering section of the project includes converting the categorical variables to numerical values and splitting the dataset into training and testing sets.

## Model Training and Evaluation
The model training and evaluation section of the project includes the training and evaluation of Random Forest and XGBoost classifiers. The Random Forest classifier is trained and optimized using hyperparameter tuning with RandomizedSearchCV. The XGBoost classifier is also trained and optimized using hyperparameter tuning with RandomizedSearchCV. The performance of each model is evaluated using F1 score and confusion matrix. The F1 score for the XGBoost classifier is 97%, while the F1 score for the Random Forest classifier is 99%.

## Results and Discussion
The Random Forest classifier performs slightly better than the XGBoost classifier, with an F1 score of 99% compared to 97%. The most important features for predicting employee behavior are satisfaction level, number of projects, and time spent at the company. These results suggest that HR professionals should focus on improving employee satisfaction and providing opportunities for professional development to retain high-potential employees.
