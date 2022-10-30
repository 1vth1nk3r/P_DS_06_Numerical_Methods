# Predicting the market value of a used car
The project from the Numerical Methods sprint of the Practicum DS course.

## Description
Here we have a dataset on used car prices. Our goal is to build a model for predicting the market value of a car.

First, we should do some data preprocessing: clean the data, fill in the missing values (if any), and change data types. Next, we need to scale and encode the data. Afterward, we could proceed to model development.

## Conclusion
After preprocessing, we explored several models using the RMSE score and GridSearchCV to look for the best hyperparameters. CatBoost Regressor shows not only the best score but is training faster than Random Forest or LGBM models.