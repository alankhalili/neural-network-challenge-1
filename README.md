# neural-network-challenge-1
neural-network-challenge-1

# Student Loans with Deep Learning

## Overview

This notebook contains an analysis and implementation of a recommendation system for student loans using deep learning techniques. Below is a brief overview of the sections and content included in the notebook.

## Data Description

The dataset used in this notebook includes various features related to student demographics, educational background, financial information, and loan preferences. The primary goal is to build a recommendation system that suggests suitable loan options for students based on their profiles.

## Key Features

- **payment_history**: Historical payment data of the student.
- **location_parameter**: Geographical location of the student.
- **stem_degree_score**: Indicator of whether the student is in a STEM field.
- **gpa_ranking**: Academic performance of the student.
- **alumni_success**: Success metrics of the alumni from the same institution.
- **study_major_code**: Code representing the student's major.
- **time_to_completion**: Expected time to complete the degree.
- **finance_workshop_score**: Score from a financial literacy workshop.
- **cohort_ranking**: Ranking within the student cohort.
- **total_loan_score**: Composite score of total loan needs.
- **financial_aid_score**: Score indicating the need and eligibility for financial aid.

## Model Development

The notebook covers the following key steps in developing the recommendation system:

1. **Data Preprocessing**: Cleaning and preparing the data for modeling.
2. **Feature Engineering**: Creating new features to improve model performance.
3. **Model Training**: Training a neural network model to predict suitable loan options.
4. **Hyperparameter Tuning**: Using Keras Tuner to find the best hyperparameters.
5. **Model Evaluation**: Assessing the model's performance using various metrics.

## Results

The results section includes the performance metrics of the trained model, such as accuracy and loss, and an analysis of feature importance using SHAP values to understand the model's decision-making process.

## Conclusion

This notebook demonstrates how to build a recommendation system for student loans using deep learning techniques. The system is designed to provide personalized loan recommendations based on detailed student profiles, ensuring that each student receives the best possible loan options tailored to their unique needs and circumstances.

## How to Run

Ensure you have the required packages installed:

- **import pandas as pd
- **import tensorflow as tf
- **import sklearn as skl
- **from tensorflow.keras.layers import Dense
- **from tensorflow.keras.models import Sequential
- **from sklearn.model_selection import train_test_split
- **from sklearn.preprocessing import StandardScaler
- **from sklearn.metrics import classification_report
- **from pathlib import Path
- **from tensorflow.keras.optimizers import Adam, RMSprop, SGD, Adagrad

##  License

This project is licensed under the MIT License - see the LICENSE.md file for details.

