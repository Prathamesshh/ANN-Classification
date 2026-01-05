📊 Customer Churn Prediction Using Machine Learning

This repository contains an end-to-end machine learning classification project focused on predicting customer churn. The project demonstrates the complete machine learning lifecycle, including data preprocessing, exploratory data analysis, model training, experimentation, and evaluation.

🚀 Project Overview

Customer churn prediction helps businesses proactively identify customers who are likely to discontinue a service. By leveraging historical customer data and applying machine learning techniques, this project aims to accurately classify churn behavior and generate actionable insights to support customer retention strategies.

⚙️ Workflow
🔹 Data Preprocessing

Data loading and initial inspection

Handling missing values

Encoding categorical variables

Feature scaling and normalization

🔹 Exploratory Data Analysis (EDA)

Customer behavior analysis

Feature correlation analysis

Data visualization for insights

🔹 Model Training & Experimentation

Train-test data split

Training multiple classification models

Hyperparameter tuning and optimization

🔹 Summary

Loaded the trained ANN model and associated pickle files (scaler and encoders).
Converted new input data into a DataFrame.
Applied one-hot encoding to the Geography feature and label encoding to the Gender feature.
Concatenated the encoded features and dropped the original categorical columns.
Scaled the input features using the saved scaler.
Predicted the churn probability using the trained model.
Interpreted the prediction based on a threshold to determine if the customer is likely to churn.
