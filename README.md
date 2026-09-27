# AIML Assignment 3 – Performance Evaluation of Regression Model

## Title
Performance Evaluation of Regression Models

## Objective

1. Develop regression models for a real-world application and evaluate their performance using appropriate metrics.
2. Implement and analyze the performance of Gradient Descent optimization for Linear Regression.

## Dataset

The California Housing dataset from Scikit-learn is used for this assignment.

The dataset contains 20,640 records and 9 columns, including:

- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude
- MedHouseVal

The target variable is `MedHouseVal`, which represents the median house value.

The dataset is loaded directly using:

```python
from sklearn.datasets import fetch_california_housing
