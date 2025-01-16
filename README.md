# House_Price_Prediction
The goal of this project is to predict the housing prices of a town.In the process, we identify the most important features affecting the price of the house. We employed techniques of data preprocessing and built regression models, including a custom Linear Regression model, Random Forest, and XGBoost, to predict prices for unseen data.
The final model is generalized and achieves high accuracy in predicting housing prices.
# Requirements:
- joblib==1.4.2
- matplotlib==3.10.0
- matplotlib-inline==0.1.7
- numpy==2.2.1
- pandas==2.2.3
- scikit-learn==1.6.1
- scipy==1.14.1
- seaborn==0.13.2
# Steps for Project:
## 1. Data Preprocessing:
The script loads the Boston housing dataset, checks for missing values, handles them if necessary, and separates the target variable from the features. It then splits the data into training and testing sets using an 80/20 ratio and displays the shapes of the resulting sets.
## 2. Model Implementation:
This script loads the cleaned Boston housing dataset, splits the data into training and testing sets, and evaluates the performance of three models: Linear Regression, Random Forest, and XGBoost. For each model, the script fits the model to the training data and makes predictions on the test data
## 3. Performance Comparison:
The models are compared using the RMSE (Root Mean Squared Error) and R² (R-squared) metrics by calculating these values for each model's predictions on the test data. The RMSE and R² scores are then printed to evaluate and compare the performance of Linear Regression, Random Forest, and XGBoost.
## 4. Feauture Importance:
Feature importance for tree-based models like Random Forest and XGBoost is visualized by extracting the feature importances and plotting them using a bar chart. This allows for an understanding of which features contribute most to the model's predictions.
## Key Features:
1. **Custom Model Implementations**:
   - Linear Regression
   - Random Forest
   - XGBoost
2. **Performance Metrics**:
   - RMSE
   - R²
3. **Feature Importance Visualization**:
   - Highlight key predictors of house prices.



