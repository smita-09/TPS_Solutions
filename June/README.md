### Here is the progress eport of what lead to changes in my score

The very first solution that I submitted had following things:
Since data had no null values so no worries about that.
Since the problem is classification, so need to use clasifiers, the very first thing that I tried is dropped the ids from both train and test data and later LabelEncoder to encode the classes and they were strings, Standarscaler is also used since I am using LogisticRegression.  1.8307023065814374

Then used stratification to split the data, and then later use logistic regression. 4.002083813135203

2nd Approach: Using random_classsifier without much hyperparametrization didn't really help. 1.8306874700003668

3rd Approach: Using random_classifier with little bit of hyperparametrization improved the score to a bit  1.7616033784491318

4th Approach: Used Lightbgm 1.755212422361672

5th Approach: Used Convolutional Neural Networks