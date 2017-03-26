### ***Final Project - Exploratory Analysis Feedback***

***Nico Van de Bovenkamp***
***

**Overall** Well done on the feature engineering! You made some really handy lambda expressions to extract information out of all those features, which will pay of when you build your models! Also, you have some fantastic plots to go along with all the extracted information.

**Some thoughts**

* You will have to dummify many of your features, which is good. Having discretized data, empirically speaking, allows models to train a bit more consistently and efficiently.
* You mention you will make use of some time series models. You certainly could, but honestly I don't recommend it. Given this data set, you should really just build a model with all the information set up the way it is. Non-linear models will perform well, but again, of course, do tend to overfit... So watch out!
* Try out some linear models (your Regularized linear regressions, likely Ridge) and then move on to some non-linear models (most likely decision tree).
* Don't forget to do your cross validation, in addition to your gridsearch!
* When it comes to modeling, typically you will do your own train, test split. Given your dataset is from kaggle, you will have to submit your model predictions and then see where it ranks you and get your Test Error. (Note: If you don't want to go this route, you can do a train test split on your own train set, but you will be losing out on Training instances...)
* Take a look at this [Stacking Example](https://www.kaggle.com/arthurtok/titanic/introduction-to-ensembling-stacking-in-python). It's a solid technique/architecture for improving modeling in these types of scenarios where you are note implementing a model as much as just trying to cook up the lowest prediction error.

***Lets discuss this more on Tuesday when we are in class! Please let me know if you have any questions or want any help. This is a fantastic start.***
