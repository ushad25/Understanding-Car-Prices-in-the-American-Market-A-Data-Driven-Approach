
# US Car Pricing Analysis and Prediction

## Project Overview

...

## Project Details

- **Project Entry Date:** 10-08-2024
- **Lead:** Usha
- **Mentor:** Jisma TK
 ## Project Overview
This project, led by Usha under the mentorship of Jisma TK from Entry Datascience and machine learning , aims to analyze and model car prices in the US market. The goal is to identify significant variables affecting car prices, understand how well these variables describe the price of a car, and develop predictive models to assist in pricing strategy and market entry for a Chinese automobile company.
 ## Objectives
1.Identify Significant Variables: Determine which factors most influence car pricing in the US market.
2.Model Implementation: Implement and compare various regression algorithms to predict car prices.
3.Model Evaluation: Assess the performance of each model using metrics like R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
4.Feature Importance Analysis: Analyze the importance of different features in predicting car prices.
5.Hyperparameter Tuning: Optimize model performance through hyperparameter tuning.
## Dataset
The dataset used for this project includes various car attributes and their prices in the US market. You can access and download the dataset from this link.https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view
## Key Components
Loading and Preprocessing:

Load the dataset.
Handle missing values and encode categorical variables.
Scale numerical features if necessary.
Model Implementation:

Implement the following regression algorithms:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor
Model Evaluation:

Compare model performance using R-squared, MSE, and MAE.
Identify the best-performing model and justify the results.
Feature Importance Analysis:

Analyze and rank the significance of each feature in predicting car prices.
Hyperparameter Tuning:

Perform hyperparameter tuning to enhance model performance.

## Model Evaluation Outputs
1. Baseline Model Metrics
R-squared (R²): 0.9536219
Explanation: This value indicates that approximately 95.36% of the variance in car prices can be explained by the baseline model. A higher R² value suggests a better fit of the model to the data.
Mean Squared Error (MSE): 3,661,273
Explanation: MSE measures the average squared difference between the predicted prices and the actual prices. A lower MSE indicates that the model's predictions are closer to the actual values.
Mean Absolute Error (MAE): 1,362.415
Explanation: MAE measures the average absolute difference between predicted and actual prices. It provides an intuitive sense of the average error in price predictions. A lower MAE indicates better prediction accuracy.
![image](https://github.com/user-attachments/assets/8b2b387a-d510-4f77-a7ed-a2e3fb3c298b)

 2.Tuned Model Metrics
R-squared (R²): 0.9544556576983939
Explanation: The R² value for the tuned model slightly improved to 95.45%, suggesting that the tuning process has further enhanced the model’s ability to explain the variance in car prices.
Mean Squared Error (MSE): 3,595,453.51
Explanation: The MSE decreased after tuning, indicating that the tuned model’s predictions are closer to the actual prices compared to the baseline model.
Mean Absolute Error (MAE): 1,332.91
Explanation: The MAE decreased after tuning, meaning that the tuned model provides more accurate price predictions on average compared to the baseline model.
## Feature Importance Analysis
Key Features and Their Importances:
enginesize: 0.588249
Explanation: This feature has the highest importance score, meaning that enginesize is the most significant predictor of car prices. Larger engine sizes generally lead to higher car prices.
curbweight: 0.230683
Explanation: This feature is the second most important, indicating that heavier cars (i.e., those with higher curb weight) tend to have higher prices.
highwaympg: 0.044075
Explanation: While less influential than enginesize and curbweight, highway miles per gallon still contributes to price predictions, likely reflecting fuel efficiency trends.
horsepower: 0.030306
Explanation: Horsepower has a relatively smaller impact on price compared to enginesize and curbweight, but it still plays a role in the overall pricing.
![image](https://github.com/user-attachments/assets/ac5445bb-6de4-416d-a543-32db8901491c)

In summary, the significant variables (enginesize, curbweight, highwaympg, and horsepower) effectively describe car prices, as evidenced by the high R² and low MSE and MAE values from the model evaluation. This comprehensive understanding of significant variables and their predictive power will help the company in pricing strategies and market positioning.
