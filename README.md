# Task 3 – Customer Churn Prediction

## Objective
The goal of this task is to predict whether a customer is likely to leave a bank based on their demographics and account activity. This task uses the Churn Modelling dataset and involves data preprocessing, feature encoding, model training, and feature importance analysis using classification techniques.

## Approach
- Loaded and inspected the dataset
- Dropped irrelevant columns such as `RowNumber`, `CustomerId`, and `Surname`
- Handled categorical variables:
  - Label Encoded `Gender`
  - One-Hot Encoded `Geography`
- Standardized numerical features to improve model performance
- Split the data into training and testing sets
- Trained two classification models:
  - Logistic Regression
  - Random Forest Classifier
- Evaluated both models using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
- Visualized feature importance from the Random Forest model

## Results and Insights
- Random Forest achieved an accuracy of **86%**
- Logistic Regression achieved an accuracy of **81%**
- Important features influencing churn included:
  - Age
  - Balance
  - Credit Score
  - Geography (especially Germany)
- Random Forest performed better overall, with more balanced precision and recall

---
This task reinforced practical skills in handling real-world customer data, preprocessing for classification models, and interpreting feature importance to draw business insights.
