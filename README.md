# Cement Strength Prediction Using Linear Regression

This project uses a Linear Regression (LR) model to predict the compressive strength of concrete based on various input features.

## Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Features](#features)
- [Model Performance](#model-performance)
- [Feature Selection](#feature-selection)
- [Conclusion](#conclusion)

## Introduction
The goal of this project is to predict the compressive strength of concrete using a set of features that include various materials used in concrete production, such as cement, water, and additives. The model uses Linear Regression to find the relationship between these features and the target variable.

## Data Source
The dataset used in this project is from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength).

## Features
The following features are used for training the Linear Regression model:
- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Age
- Concrete Compressive Strength (Target)

## Feature Selection
Based on exploratory data analysis (EDA) and plot visualizations, it was found that the following features were not strongly related to the target variable and were dropped:
- Coarse Aggregate
- Fine Aggregate
- Blast Furnace Slag

These features were removed to improve model accuracy and reduce complexity.

## Model Performance
The Linear Regression model was evaluated using the following metrics:

- **Mean Squared Error (MSE):** 68.32
- **Root Mean Squared Error (RMSE):** 8.27
- **Mean Absolute Error (MAE):** 6.54
- **R² Score:** 0.62

These performance metrics indicate the model's effectiveness in predicting the compressive strength of concrete.

## Conclusion
The model provides a reliable prediction for concrete compressive strength based on a set of features. Although the model achieves a moderate R² score of 0.62, further improvements could be made by exploring other algorithms or engineering additional features. The current feature selection has helped streamline the model and removed irrelevant features for better predictive performance.

