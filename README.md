# NYC Housing Price Predictor
This project focuses on building a predictive model for housing prices in New York City. By analyzing various features like property size, total rooms, area, and more, the model estimates housing prices to support better decision-making in the real estate market.

# Table of Contents
1. Project Overview
2. Dataset
3. Data Preprocessing
4. Modeling
5. Evaluation Metrics
6. Technologies Used

# Project Overview
This project builds a predictive model that estimates housing prices in NYC using various property-related features. The model was tested with different regression techniques, including Linear Regression, Decision Tree Regressor, Random Forest Regressor, and more, to identify the best-performing model based on the R² score.

# Dataset
The dataset can be found here : nyc-property-sales/nyc-rolling-sales.csv

The dataset contains various attributes of houses in NYC, such as:
1. Land_Square_Feet
2. Gross_Square_Feet
3. Residential_Units
4. Commercial_Units
5. Tax_Class_At_Present
6. Tax_Class_At_Sale
and more.


# Data Preprocessing
Several preprocessing steps were applied to prepare the data:

Handling Missing Values: Empty values were managed to ensure data consistency.
Encoding Categorical Data: Label Encoding and One-Hot Encoding were applied to categorical features for compatibility with machine learning models.
Feature Scaling: Data was scaled to prevent exploding gradients and improve model performance.
The dataset was then split into training, validation, and test sets for unbiased model evaluation.

# Modeling
A variety of regression models were trained to predict housing prices:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. LinearSVR
5. SVR

The models were integrated into a pipeline that automated the entire process, from preprocessing through to model training. The learning rate of 0.001 was determined to be the most effective for stable and accurate predictions.

# Evaluation Metrics
The performance of each model was evaluated using:

R² Score: This metric was chosen to assess how well each model explains the variance in housing prices.

# Technologies Used
Programming Languages: Python <br/>
<br/>
Libraries: <br/>
Data Manipulation: NumPy, Pandas <br/>
Modeling and Evaluation: Scikit-Learn (sklearn) <br/>
Visualization: Matplotlib <br/>
