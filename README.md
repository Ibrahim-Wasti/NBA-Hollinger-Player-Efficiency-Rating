# NBA-Hollinger-Player-Efficiency-Rating

XGBoost Regressor to predict Hollinger's Player Efficiency Rating
Used BeautifulSoup4, requests, and regex libraries to scrape the ESPN Hollinger website to create a dataset of players with 12 features, Player Efficiency Rating (PER) being the target variable.
Saved the data as a list of dictionaries to a json file for easy loading in and conversion to a dataframe when conducting data exploration, analysis, and modelling.
Used Pandas, Seaborn, MPL, SK-Learn, and XGBoost for the above stated exploration, analysis, and modelling.
  - Feature selection for the SK-Learn model done using Pearson Correlation as this was Linear Regression probelm.
  - Used seaborn and IQR to get rid of outliers in the dataset, this increased the accuracy of the final model.
  - Modelled using SK-Learn for a base accuracy score (measured by RMSE) to see if XGB would give better results.
  - XGB Regressor performed with a higher accuracy (lower RMSE) than the SK-Learn model.
