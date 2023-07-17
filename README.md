# WIDS 2020 Datathon

This repository contains code for the [Women in Data Science (WIDS) 2020 Datathon](https://www.kaggle.com/c/widsdatathon2020/) completed by the San Jose State University team consisting of [Sonia Meyer](https://github.com/soniawmeyer) and Emma Hendry. The code performs data preprocessing, feature selection, and training a logistic regression model on the dataset.

The code is organized into several sections:

1. Module Import and Data Reading: Imports necessary modules and reads the training and unlabeled data from CSV files.
2. Handling Missing Values: Drops columns with more than 75% missing values and removes irrelevant columns.
3. Removing Collinear Variables: Removes variables with high correlations.
4. Feature Selection: Selects the top 20 most correlated variables and their dictionary descriptions. Selects a subset of variables for training the model.
5. Data Imputation: Imputes missing values with the median value for the selected variables.
6. Training the Model: Trains a logistic regression model on the imputed data and evaluates its performance.
7. Cross-Validation: Performs cross-validation on the trained model to assess its average accuracy.
8. Receiver Operating Characteristic (ROC) Curve: Plots the ROC curve and calculates the Area Under the Curve (AUC) to evaluate the model's performance.
