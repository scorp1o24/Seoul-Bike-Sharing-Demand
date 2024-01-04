Project Name: SeoulBikeAI Predictor

Description:
This project focuses on predicting bike counts in Seoul, South Korea, utilizing machine learning techniques. The dataset comprises various environmental features, including temperature, humidity, wind, and more. The goal is to develop predictive models to enhance bike-sharing system management.

Dataset:
The dataset is sourced from the UCI Machine Learning Repository and South Korea Public Holidays.

Features:

bike_count
temp
humidity
wind
visibility
dew_pt_temp
radiation
rain
snow
functional (target variable)
Key Steps:

Data Cleaning: Columns like "Date," "Holiday," and "Seasons" were dropped for simplicity.
Data Exploration: Initial data exploration involved visualizing relationships between bike count and individual features.
Linear Regression Models:
Temperature-based Model: Utilized linear regression to predict bike counts based on temperature.
Multiple Regression: Extended the model to include multiple environmental features for more accurate predictions.
Neural Network Models:
Single-parameter Model: Implemented a neural network for predicting bike counts based on temperature.
Multi-parameter Model: Developed a neural network incorporating multiple environmental parameters.
Evaluation: Calculated Mean Squared Error (MSE) for both linear regression and neural network predictions on the test set.

Results:

The linear regression model achieved a score of approximately 34% on the test set.
The neural network model, while exhibiting higher MSE, provides a more complex understanding of the relationships between multiple parameters and bike counts.
