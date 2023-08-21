# Linear_Ridge_Lasso-Regression

About the Project
This project uses the California Housing dataset from scikit-learn to predict housing prices. The dataset is preprocessed and divided into independent features (X) and the dependent target (Y).

Linear Regression:

Trains a basic Linear Regression model.
Performs cross-validation to evaluate the model's performance using negative mean squared error (MSE).
Prints the mean MSE.
Ridge Regression:

Applies Ridge Regression using hyperparameter tuning with cross-validation.
Determines the best alpha (regularization strength) using GridSearchCV.
Prints the best alpha and corresponding negative mean squared error.
Lasso Regression:

Implements Lasso Regression with hyperparameter tuning and cross-validation.
Identifies the optimal alpha using GridSearchCV.
Displays the best alpha and associated negative mean squared error.
Prediction and Evaluation:

Uses the trained models to predict housing prices on the test set.
Calculates the R-squared (coefficient of determination) score for each model's predictions.
