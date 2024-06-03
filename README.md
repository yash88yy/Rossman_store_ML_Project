# Rossman_store_ML_Project

Rossmann Sales Prediction Project

This project aims to predict the daily sales of Rossmann stores in Germany using various machine learning techniques. The project involves data preprocessing, feature engineering, model training, and evaluation.

Data Preprocessing:

Missing Values:
Replaced missing values in CompetitionDistance with the median value.
Replaced missing values in CompetitionOpenSinceMonth, CompetitionOpenSinceYear, Promo2SinceWeek, Promo2SinceYear, and PromoInterval with 0.
Outliers:
Winsorized outliers in the Sales variable to preserve the shape of the distribution.
Feature Engineering:

Categorical Encoding:
Performed one-hot encoding on the PromoInterval column.
Label encoded the StateHoliday column.
Feature Selection:
Used correlation analysis and feature importance scores to select relevant features for the model.
Model Training and Evaluation:

Linear Regression:
Trained a linear regression model and achieved an R-squared score of approximately 0.87.
Decision Tree:
Trained a decision tree model and obtained an R-squared score of around 0.81.
Random Forest:
Trained a random forest model and achieved an R-squared score of approximately 0.92.
XGBoost:
Trained an XGBoost model and obtained the highest R-squared score of close to 0.99.
Usage
To use this code, you will need to install the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
Results
The following table shows the R-squared scores for each model:

Model	R-squared Score
Linear Regression	0.87
Decision Tree	0.81
Random Forest	0.92
XGBoost	0.99
AdaBoost	0.92
Conclusion:

The XGBoost model demonstrated the best performance in predicting sales, with the lowest MSE and RMSE values. This suggests that more complex ensemble methods like XGBoost are well-suited for capturing the intricacies of sales data and generating highly accurate predictions.

GitHub Repository:

The project code and detailed explanations can be found in the GitHub repository: https://github.com/ankit-chuahan/rossman_sales_analysis__/blob/main/Rossman_sales_ml_project.ipynb

Contributions:

This project was completed by Ankit Chauhan as part of a machine learning capstone project.

Sure, here is a README file for your GitHub repository:
