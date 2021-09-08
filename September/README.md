### This is to desribe what's the worst solution and what's the journey to improve it.

1st approach: Imputed the NaN values with zero and used LinearRegression

2nd approach: Imputed the NaN values with mean and used LinearRegression

3rd aproach: Imputed the NaN values with median values and used LinearRegression

4th aproach: Imputed the NaN values with median values and used XGBRegressor

5th aproach: Imputed the NaN values with mean values and used XGBRegressor with StandardScaling

6th aproach: Imputed the NaN values with mean values and used XGBRegressor with StandardScaling and dropping the uncorrelated features

7th aproach: Imputed the NaN values with mean values and used XGBRegressor with StandardScaling, dropping the uncorrelated features and tuned hyperparams

8th approach: Up until now I was all wrong, I have been using regression which is pretty stupid thing to do but now I want to save myself from all the misery so I will try classifiers, which I should have used before but its better late than never. So, here is the score if I will use ,

I used logistic regression and XGClassifier with median imputation and it actually didnt imporve the score. Dammit!
There must be something wrong. 

9th Approach: Classifier with mean imputation and fixing the iteration to 3k. Hope to see better results, let's see what happens! The score is so far the best of that I have seen so far but there is something wrong. It did not improve that much. Gonna try some other imputation method. :(

10th Approach: Classifier when used constant imputation resulted in better results. and also when features were added it gave pretty good results for logistic regression as well which I didnt think it would give. 



