# Logistic Regression on Social Network Ads

## Overview
This repository contains an implementation of Logistic Regression for classifying whether a user purchases a product based on their age and estimated salary. The dataset used is `Social_Network_Ads.csv`.

## Dataset
The dataset consists of 400 entries with the following columns:
- **Age**: Age of the individual.
- **EstimatedSalary**: Estimated salary of the individual.
- **Purchased**: Target variable (0 = No, 1 = Yes) indicating whether the individual made a purchase.

## Implementation
The implementation is provided in the Jupyter Notebook `logistic regression.ipynb`. The key steps include:
1. **Data Preprocessing**
   - Importing necessary libraries.
   - Loading the dataset.
   - Splitting the data into training and testing sets.
   - Feature scaling.
2. **Model Training**
   - Applying Logistic Regression.
   - Training the model on the training set.
3. **Model Evaluation**
   - Making predictions on the test set.
   - Evaluating performance using confusion matrix and accuracy score.
4. **Visualization**
   - Plotting the decision boundary.
   - Visualizing the classification results.

## Results
- The model successfully classifies users based on their purchase decisions.
- The decision boundary is visualized to show classification regions.

