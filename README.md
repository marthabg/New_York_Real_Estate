# New_York_Real_Estate
Compares different regression models to predict property prices/analyze property attributes' relationship to price of properties in New York.

# Main Features
* Exploratory data analysis: thought process for deciding which features to include/exclude is documented throughout.
* Regression problem: makes use of sklearn's LinearRegression, Ridge, RandomForestRegressor, and xgboost's XGBRegressor.
* Matplotlib: shows histogram of distribution, which turned out to be skewed to the right leading to the decision to Log-transform the data
* Plotly.express: to display relationship between gross_square_feet and sale_price. Also allows for analysis of outliers.
* Metrics for evaluation: Mean Absolute Error and R^2
* Train/Test split based on date
