# Gold_Price_Prediction
Built an end-to-end Gold Price Prediction ML project using XGBoost, Random Forest, Decision Tree, and Linear Regression with 98.72% R² accuracy and live prediction dashboard.

This project was carried out in Phases: 
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Feature Selection
5. Model Training


The following regression models were trained:

- Linear Regression

Used as baseline model for comparison.

- Decision Tree Regressor

Used for capturing non-linear patterns.

-  Random Forest Regressor

Used for stronger accuracy and reduced overfitting.

- XGBoost Regressor

Used as final advanced boosting model for best performance.

# Hyperparameter Tuning

Manual Hyperparameter Tuning was performed for:

Decision Tree
Random Forest
XGBoost

Parameters tuned:
1. n_estimators
2. max_depth
3. min_samples_split
4. min_samples_leaf
5. learning_rate

This significantly improved model performance.

Model Evaluation Metrics

Since this is a Regression Problem, the following metrics were used:

MAE (Mean Absolute Error), MSE (Mean Squared Error), RMSE (Root Mean Squared Error), R² Score

# Best Model
# Random Forest
Final Performance:
R² Score = 98.57%
RMSE = 2.83
MAE = 1.37

XGBoost achieved the highest R² score and lowest prediction error, making it the most accurate and reliable model for Gold Price Prediction.






