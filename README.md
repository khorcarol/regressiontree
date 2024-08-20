# Random Forest Regressor

Random Forest Regression Model used to analyse non linear data collected from pumps.

Steps:
1. Preprocess data by converting units and filtering missing values and outliers by quantile.
2. Perform exploratory data analysis.
3. Split data into test and train, and train model with hyperparameters from grid search.
4. Test on test data to get model performance (acc > 0.8)
5. Get feature importance by Gini importance.
6. Visualise with plots.
