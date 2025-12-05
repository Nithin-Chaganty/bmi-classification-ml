# bmi-classification-ml

This project builds a machine learning model that predicts a person’s BMI category (underweight, normal weight, overweight, or obese) using gender, height, and weight. I wanted to use to bridge the gap between my knowledge in data science and my interest in nutrition.

Overview

The goal of this project is to classify individuals into BMI categories based on basic biometric features. I compared multiple machine learning models and selected the one that performed the best on classification accuracy.

Dataset

Kaggle dataset:
https://www.kaggle.com/datasets/rukenmissonnier/age-weight-height-bmi-analysis

Features used

Gender

Height

Weight

Target

BMI Category

Methods

Cleaned and encoded the data

Standardized height and weight

Split into training and testing sets

Applied 5 fold cross validation

Tested logistic regression, random forest, and SVM

Selected the best performing model based on accuracy and F1 score

Results

SVM was the most accurate model. Most errors occurred for people near BMI category boundaries. Adding more features, such as age or lifestyle factors, could improve future versions of the project.

Files

notebook.ipynb Notebook with full analysis and code

data/ Dataset or download link

README.md Project overview

Future Work

Add age, activity level, and nutrition inputs

Try advanced models like gradient boosting or neural networks

Build a simple web app that predicts BMI category
