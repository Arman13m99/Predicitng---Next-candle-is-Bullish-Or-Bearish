# Random Forest Classifier for Long-Short Classification

## Overview
This Python script utilizes a Random Forest classifier to predict whether cryptocurrency prices will increase (long) or decrease (short) based on historical data and technical indicators. The script preprocesses the input data, trains the classifier using grid search with cross-validation, evaluates the model's performance, and visualizes the learning curve.

## Features
- **Data Loading and Preprocessing**: The script loads historical cryptocurrency data from a CSV file, preprocesses it by removing irrelevant columns and setting the date-time column as the index.
- **Model Training and Evaluation**: It splits the data into training and testing sets, standardizes features, defines hyperparameters for the Random Forest classifier, performs grid search with cross-validation to find the best model, evaluates the model's performance using confusion matrix and classification report, and calculates test accuracy.
- **Learning Curve Visualization**: The script plots the learning curve to visualize the model's performance on training and validation data across different training set sizes.

## Usage
1. **Data Preparation**: Prepare a CSV file containing historical cryptocurrency price and indicator data for classification.
2. **Data Loading and Preprocessing**: Modify the script to load your dataset and preprocess it according to your requirements.
3. **Model Configuration**: Adjust hyperparameters and settings for the Random Forest classifier as needed.
4. **Model Training**: Run the script to train the Random Forest classifier on your preprocessed dataset.
5. **Model Evaluation**: Evaluate the trained model's performance using printed evaluation metrics such as confusion matrix, classification report, and test accuracy.
6. **Learning Curve Visualization**: Analyze the learning curve plot to understand the model's performance with different training set sizes.

## Dependencies
- Python 3.9.18
- pandas: Data manipulation library for handling datasets.
- numpy: Numerical computing library for array manipulation.
- scikit-learn: Machine learning library for data preprocessing, model training, and evaluation.
- matplotlib: Plotting library for data visualization.
- seaborn: Statistical data visualization library for enhancing plots.

## Note
- This script is designed for classification tasks involving cryptocurrency price movements and can be adapted for other similar classification problems.
- Ensure that your dataset contains relevant features and a target variable for classification.
- Experiment with different hyperparameters and model settings to optimize the classifier's performance.

## Contact
For any inquiries or support, please contact [arman13m99@gmail.com].

