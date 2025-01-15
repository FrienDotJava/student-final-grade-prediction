# Predicting Student Final Grades Using Linear Regression

This project demonstrates how to predict students' final grades using Linear regression, Ridge Regression, and Lasso Regression. The dataset contains academic and demographic data about students, and the model aims to provide insights into factors influencing academic performance.

## Overview
Student performance prediction can help educators identify at-risk students and implement interventions to improve academic outcomes. This project uses linear regression to:
- Analyze relationships between features (e.g., study time, attendance) and final grades.
- Predict student grades based on input data.

## Dataset
The dataset used in this project is sourced from [UCI Machine Learning Repository - Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance). It includes attributes like:
- Demographic data (age, gender, etc.)
- Academic performance (grades, study time, failures, etc.)
- Social factors (family support, extracurricular activities, etc.)

## Features
Key features used in the prediction model include:
- `studytime`: Weekly study time.
- `failures`: Number of past class failures.
- `absences`: Number of school absences.
- `G1`, `G2`: Grades from the first and second terms.

## Model
The project employs three different models:
- Linear Regression
- Ridge Regression
- Lasso Regression

### Workflow
1. Data preprocessing: Cleaning and encoding categorical variables.
2. Exploratory Data Analysis (EDA): Visualizing relationships between features.
3. Model training: Fitting the models.
4. Evaluation: Measuring performance using metrics like MAE, MSE, and R² score.

## Results
The models achieved the following results:
1. Linear Regression
  - **R² Score**: 0.73
  - **Mean Absolute Error (MAE)**: 1.62
  - **Mean Squared Error (MAE)**: 5.59
1. Ridge Regression
  - **R² Score**: 0.72
  - **Mean Absolute Error (MAE)**: 1.65
  - **Mean Squared Error (MAE)**: 5.65
1. Lasso Regression
  - **R² Score**: 0.76
  - **Mean Absolute Error (MAE)**: 1.42
  - **Mean Squared Error (MAE)**: 4.69

These results indicate the models perform well for predicting student final grades based on the given features.
