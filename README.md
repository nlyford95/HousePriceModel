Language: Python

The goal of this project is to produce a model capable of predicting the home prices of houses. The dataset includes house sales from Ames, Iowa.

The data requires extensive cleaning, this process is shown in the cleaning codes. Much of the cleaning is condensing categorical data into fewer categories, removing data that is too skewed, and standardizing continuous data.

I implemented three models, a basic linear regression model meant to serve as a baseline, the XGBoost regressor model, and a nueral network.

The XGB model performed the best on the test data - leading to an RMSE of 0.14353
