### This is to desribe what's the worst solution and what's the journey to improve it.

1st approach: Imputed the NaN values with zero and used LinearRegression

2nd approach: Imputed the NaN values with mean and used LinearRegression

3rd aproach: Imputed the NaN values with median values and used LinearRegression

4th aproach: Imputed the NaN values with median values and used XGBRegressor

5th aproach: Imputed the NaN values with mean values and used XGBRegressor with StandardScaling

6th aproach: Imputed the NaN values with mean values and used XGBRegressor with StandardScaling and dropping the uncorrelated features

7th aproach: Imputed the NaN values with mean values and used XGBRegressor with StandardScaling, dropping the uncorrelated features and tuned hyperparams
