Linear Regression Project: House Price Prediction

Project Overview

This project aims to predict house prices per unit area using linear regression techniques. The dataset includes various features such as house age, proximity to MRT stations, number of convenience stores, and geographical coordinates. The objective is to build and evaluate a model that accurately predicts house prices.

Key Tasks

Data Preprocessing:
Loading the data and initial checks.
Renaming columns for better readability.
Extracting date components (Year, Month, Day) from the transaction date.
Handling missing values and outliers using the IQR method.

Exploratory Data Analysis (EDA):

Understanding the distribution of features using histograms and boxplots.
Analyzing the relationship between features and the target variable (house price).
Examining the correlation matrix to identify significant relationships.

Model Training and Evaluation:
Splitting the data into training and testing sets (80:20).
Training the initial linear regression model and evaluating its performance using MAE, MSE, and R-squared metrics.
Improving the model by removing non-linear features.

Cross-Validation and Regularization:
Performing Leave-One-Out Cross-Validation (LOOCV) and Five-Fold Cross-Validation to assess model robustness.
Applying Lasso (L1) and Ridge (L2) regularization techniques to enhance model performance.

Final Model Comparison:

Comparing the performance of all models and selecting the best-performing one.
Providing recommendations for future improvements and applications.
Results

Model Performance: The improved model (Model 2) demonstrated the best performance with the lowest prediction errors and highest R-squared value.
Cross-Validation and Regularization: Regularization techniques slightly improved the model's robustness, though Model 2 remained the best overall.
Recommendations: It is recommended to use Model 2 for predicting house prices. Further improvements could include experimenting with alternative models like SVM or Random Forest and collecting more data to prevent overfitting.
Conclusion

The project successfully identified an effective linear regression model for predicting house prices, providing valuable insights into the factors influencing price variations. The findings and methodologies can be applied to similar predictive modeling tasks in the future.
