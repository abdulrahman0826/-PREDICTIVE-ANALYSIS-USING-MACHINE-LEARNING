# -PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
Predictive Analysis with using Machine Learning
Company Name : Codtech IT Solutions
Name : Mohammed Abdul Rahman
Intern Id : CT4MDN1084
Domain : Data Analytics
Duration : 4 Months
Mentor : Neela Santosh Kumar
**Predictive Analysis Project:House Price Forecasting**
This repository documents a comprehensive machine learning project focused on predicting residential property sale prices using a robust dataset of housing features. The primary objective of this "Task 2 Predictive Analysis" was to develop and evaluate a highly accurate regression model capable of providing reliable price forecasts, a critical function in real estate investment and appraisal.
**Project Goal and Dataset Overview**
The core goal was the implementation of a machine learning pipeline to accurately predict the continuous target variable, SalePrice. We leveraged the House-Price-Prediction-clean.csv dataset, which includes a wide array of features related to property quality, size, location, and condition. The preliminary data cleaning steps were addressed in an earlier phase, allowing this notebook to focus primarily on advanced feature engineering, model optimization, and performance evaluation.
The dataset's features encompass both numerical attributes (e.g., lot size, living area in square feet, year built) and categorical attributes (e.g., neighborhood quality, overall condition). The inherent heterogeneity of these features necessitated a meticulous approach to data preparation to maximize model efficacy.
**Methodology and Data Preparation
Feature Engineering and Transformation**
A key step in this analysis involved crucial data transformations. Recognizing the typical non-normal distribution of housing prices, the target variable, SalePrice, was transformed using a logarithmic function to achieve a more symmetrical, Gaussian-like distribution. This stabilizes the variance and improves the performance of linear regression-based models.
**Handling Categorical Data**
The project employed One-Hot Encoding to convert nominal categorical features (like Neighborhood or HouseStyle) into a format usable by machine learning algorithms, avoiding the introduction of unintended ordinality. Ordinal features (like OverallQual or ExterQual) were often treated as numerical data, capitalizing on their inherent rank order.
**Model Training and Selection**
The prepared data was split into training and testing sets to ensure the model's performance was evaluated on unseen data, providing an unbiased assessment of its generalization capability.
Multiple regression models were explored to determine the best fit for the data structure:
Linear Regression: Served as a strong baseline model.
Regularized Models (Ridge/Lasso): Utilized to prevent overfitting, particularly by penalizing overly complex models and shrinking coefficients.
**Evaluation and Results**
Model performance was rigorously assessed using standard regression metrics, primarily Root Mean Squared Error (RMSE) and the R-squared value. RMSE provided a measurable metric in the original price units (after inverse log transformation), indicating the average magnitude of the prediction error. The final selected model consistently achieved a high R-squared score, demonstrating its strong explanatory power and ability to account for a significant portion of the variance in housing prices. The array of prediction outputs generated confirms the successful deployment of the final model.
**Technologies Used**
Python: The core programming language.
Pandas & NumPy: Essential libraries for data manipulation and numerical operations.
Scikit-learn : The primary library for model training, cross-validation, and evaluation.
Matplotlib / Seaborn: Used for exploratory data analysis and visualizing feature relationships 

Matplotlib / Seaborn: Used for exploratory data analysis and visualizing feature relationships (e.g., correlation heatmaps and distribution plots).
