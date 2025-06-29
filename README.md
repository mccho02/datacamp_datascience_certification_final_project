# Recipe Site Traffic Prediction

This repository contains a complete data science project for the DataCamp Practical DSP Exam – Recipe Site Traffic (2212). The objective of the project is to help Tasty Bytes, a recipe recommendation company, determine which recipes are likely to generate high traffic when featured on the homepage.

## Problem Statement

The Product Manager wants to improve user engagement by displaying recipes on the homepage that consistently attract higher traffic. The goal is to:

- Predict whether a recipe will result in high site traffic when featured.
- Correctly identify popular recipes at least 80% of the time.
- Minimize the chance of promoting unpopular recipes.

## Project Workflow

1. Data Validation & Cleaning
- Ensured all numeric fields were valid (e.g., no negative or missing values).
- Verified the consistency of categorical fields.
- Handled missing values and checked for duplicates.

2. Exploratory Data Analysis (EDA)
- Explored distribution of calories, carbohydrates, sugar, protein, etc.
- Visualized trends across recipe categories.
- Compared variables against the target: high_traffic.

3. Model Building
- Framed this as a binary classification task.
- Trained:
  - A baseline model using Logistic Regression.
  - A comparison model using Random Forest.

4. Model Evaluation
- Evaluated both models using:
  - Accuracy
  - Precision / Recall
  - Confusion Matrix
- Selected the best-performing model based on balanced accuracy and business needs.

5. Business Metric
- Defined a monitoring metric: True Positive Rate (TPR) for high-traffic prediction.
- Current TPR estimated from test set results.

6. Final Recommendations
- Use the model to inform recipe selection.
- Focus on recipes with high predicted probability.
- Continuously update model as new data comes in.


## Key Takeaways

- Recipe category and nutritional content influence traffic.
- Predictive modeling can outperform human intuition in selecting recipes.
- A well-tuned model improves homepage performance and potential subscriptions.

## Author and Certification

This project was completed as part of the DataCamp Data Scientist Professional Certification.  
Author: Marco Soh
Date: June 2025
