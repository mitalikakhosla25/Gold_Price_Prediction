# Gold_Price_Prediction
Built an end-to-end Gold Price Prediction ML project using XGBoost, Random Forest, Decision Tree, and Linear Regression with 98.72% R² accuracy and live prediction dashboard.

This project was carried out in Phases: 
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Feature Selection
5. Model Training


The following regression models were trained:

1. Linear Regression

Used as baseline model for comparison.

2. Decision Tree Regressor

Used for capturing non-linear patterns.

3. Random Forest Regressor

Used for stronger accuracy and reduced overfitting.

4. XGBoost Regressor

Used as final advanced boosting model for best performance.

Hyperparameter Tuning

Manual Hyperparameter Tuning was performed for:

Decision Tree
Random Forest
XGBoost

Parameters tuned:

n_estimators
max_depth
min_samples_split
min_samples_leaf
learning_rate

This significantly improved model performance.

Model Evaluation Metrics

Since this is a Regression Problem, the following metrics were used:

MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score

Best Model
XGBoost Regressor 
Final Performance:
R² Score = 98.72%
RMSE = 2.63
MAE = 1.37

XGBoost achieved the highest R² score and lowest prediction error, making it the most accurate and reliable model for Gold Price Prediction.






