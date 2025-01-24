# AbaloneAgeML
This project focuses on analyzing and predicting the age of abalones using physical measurements from the Abalone Dataset. The primary objective is to process and explore the dataset, then apply various machine learning models for regression and classification tasks. The key target variable, Rings, is used to estimate the age of abalones with the formula:
Age = Rings + 1.5 years

Dataset Information
Abalone Dataset

Source:
Marine Resources Division, Tasmania
Donor: Sam Waugh, University of Tasmania
Attributes:
Sex: Nominal (Categories: M = Male, F = Female, I = Infant)
Length, Diameter, Height: Continuous (Measurements in mm)
Whole weight, Shucked weight, Viscera weight, Shell weight: Continuous (Weights in grams)
Objective:
Predict the age of abalones based on physical measurements.
Classify abalones into categories based on the Rings attribute.

The following machine learning models were implemented to perform regression and classification:

Linear Regression
Random Forest Regressor
K-Nearest Neighbors (KNN)
Multi-Layer Perceptron (MLP)
Each model was evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score to assess performance.
