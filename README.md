# Customer-Churn-Prediction
Predicting customer churn using machine learning models.

# Customer Churn Prediction with Machine Learning

## Overview

This repository contains a machine learning project aimed at predicting customer churn for a telecom company. The project explores different machine learning models, including **Logistic Regression**, **Random Forest**, and **Gradient Boosting**, with a focus on optimizing the model's performance for predicting churners.

After comparing the models, **Gradient Boosting** was selected as the best-performing model, achieving an accuracy of **80.97%**. The model is tuned to provide a balanced performance across precision, recall, and F1-score for both churners and non-churners.

## Features of the Project

- **Data Cleaning and Feature Engineering**: We start by preprocessing the dataset, including handling missing values and encoding categorical features.
- **Model Comparison**: We evaluate multiple models to find the best-performing one.
- **Hyperparameter Tuning**: The **Gradient Boosting** model is tuned using **GridSearchCV** to improve its performance.
- **Real-Time Prediction Integration (Exploration)**: We explore how the model could be integrated into a real-time system to predict churn as new customer data becomes available.

## Key Technologies Used

- **Python**: For data analysis and model building.
- **Scikit-learn**: For machine learning models and hyperparameter tuning.
- **Pandas and NumPy**: For data manipulation and analysis.
- **Matplotlib and Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive development.

## Instructions for Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MutluToy/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction

