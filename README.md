# Pune-House-Rent-Prediction
Pune House Rent Prediction is a machine learning project based on a Kaggle dataset containing over 10,000 records of rental properties across Pune. The dataset includes features such as number of bedrooms, bathrooms, pet facilities, accommodation type, flooring type, furnishing status, and locality.

The data was first cleaned and preprocessed by handling missing values, encoding categorical variables (label encoding for ordinal and one-hot encoding for nominal), removing outliers using the IQR method, and checking for multicollinearity to drop redundant features. Since the 'area' column had over 1,100 unique values, target encoding was used to avoid high dimensionality.

The final model was trained using XGBoost Regressor, which outperformed other models tested. Evaluation metrics for the final model on the test data are:

RMSE: 2820.9338497448925
MSE: 7957667.784636539
MAE: 1934.5342981810763
R2 Score: 0.8367553447219529

The model captures over 83% of the variance in rental prices and performs well in predicting house rent in Pune.
