# Credit-Card-Fraud-Detection
End-to-End Project for Credit Card Company

Introduction:

This project is focused on detecting fraudulent transactions in credit card usage using Python and machine learning algorithms. It utilizes the dataset 'credit_card_fraud.csv' to analyze transaction data, identify patterns in fraudulent activities, and build predictive models.

Installation

To run this project, follow these steps:

1- Clone the repository.

2- Install required Python packages:

pip install numpy pandas matplotlib seaborn scikit-learn imblearn

3- Download the dataset 'credit_card_fraud.csv' included in the repository.

Dataset

The dataset, 'credit_card_fraud.csv', contains transaction details and user information necessary for identifying fraudulent activities.
Preprocessing includes handling missing values, encoding categorical variables, balancing training the dataset, and feature correlation analysis.

Dataset Source: https://app.datacamp.com/workspace/w/760c72c0-cd75-438e-9b85-110f0ce8b39f/edit
dataset size: 339607



Feature Analysis

Conduct exploratory data analysis to understand feature distributions.
Utilize seaborn and matplotlib for visualizations, including the distribution of transaction amounts and feature correlations.

Model Training and Evaluation

Split the dataset into training and testing sets.
Use SMOTE to balance the dataset for training.
Train models like Logistic Regression, Random Forest, and Gradient Boosting.
Evaluate models based on accuracy, precision, recall, and F1-score.

Usage

The project can be applied to predict fraudulent activities in credit card transactions.
Users can input transaction data into the model to classify them as fraud or non-fraud.
