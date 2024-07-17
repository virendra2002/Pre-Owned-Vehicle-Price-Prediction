# Pre-Owned Vehicle Price Prediction

## Life cycle of Machine Learning Project

### Understanding the Problem Statement
    * We have a dataset about used cars sold on cardekho.com in India.
    * Our goal is to create a model that can predict the price of a car based on its features.
    * The predicted prices will help new sellers set their car prices according to market conditions.
    
### Collecting Data
    * Data used in this project is sourced from Kaggle website.

### Exploratory Data Analysis
    * Extracted Numerical and Categorical features, and performed Univariate and Multivariate Analysis.
    * Further extracted Continuous and Discrete features from Numerical features, and plotted their relation with the target variable.

### Data Cleaning
    * Handled Null values and Duplicates.

### Data Pre-Processing
    * Removed redundant columns
    * Capped Outliers using Boxplot formula for upper limit and lower limit

### Model Training
    * Encoded and Standardized Categorical and Numerical features.
    * Trained the model on 6 regression models, namely, Linear Regression, K-Neighbours Regressor, Decision Tree, Random Forest Regressor,
     XGBoost Regressor, CatBoosting Regressor.

### Choosing the optimal model
    * Final best model: CatBoosting Regressor with R^2 score of 0.9423.

