# Internship_Case_Study_Day15

The Random Forest model was implemented for the fraud detection system. Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

This model is particularly effective for detecting complex patterns in transaction data and is widely used in financial fraud detection systems.

Objectives
The objectives of this step were:
- Train a Random Forest classifier on the prepared dataset
- Generate predictions on the test dataset
- Evaluate the model using classification metrics
- Compare its performance with the baseline Logistic Regression model

Model Training Process
The following steps were performed:
1. Load the dataset
2. Separate features and target variable
3. Split the dataset into training and testing sets
4. Train the Random Forest model
5. Generate predictions
6. Evaluate model performance

About Random Forest
Random Forest works by building multiple decision trees during training. Each tree learns different patterns from the dataset, and the final prediction is determined by majority voting among all trees.

Key characteristics:
- Ensemble learning method
- Handles nonlinear patterns
- Robust to overfitting
- Provides feature importance ranking

Evaluation Metrics
The model performance was evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

In fraud detection systems, **Recall** is particularly important because detecting fraudulent transactions is critical.
