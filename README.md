# Data-analytics-Project

We have used the dataset fuel_consumption.csv which was taken from the web.

1.Preprocessing the data:

We have imported the modules that are required for preprocessing the data, EDA and model evaluation.
Reading our dataset using the pandas module(read_csv())
Checked for the duplicates in the dataset and removed them.
Checked if there are any missing values in the dataset, if there we would replace it with the appropriate data.
Checked for the count of unique elements of the attributes.
We have plotted box plot for Engine size we can see the outliers aboce the Q3 region.
Discarding the tuples with the outliers wehave found for few of the attributes. 

2.Exploratory data analysis:

Histogram: We observe here that most models emits CO2 in the rate of 250 which is likely to be eco friendly than higher rates. We should try to reduce to even better than this achieve eco friendly nature by finding out the necessary correlations where CO2 emissions should be at a certain minimum rate. 
We have done most of the visualizations with the histogram plots, bar plots, scatter plots, count plots, regression plots, heat maps.
We have plotted the scatter plots and correlation between the attributes using the scatter plots.


3.Building models:

Multiple Linear Regression: In the decision tree regression we have firstly split the dataset into the train test dataset that helps in testing the predictions inside the dataset. Here we have a built in model called the Decision Tree imported from the module sklearn.tree.We have computed the values of the r2 score and MSE to hceck how good the model is for our dataset.

Decision Tree Regression: In the decision tree regression we have firstly split the dataset into the train test dataset that helps in testing the predictions inside the dataset. Here we have a built in model called the Decision Tree imported from the module sklearn.tree.We have computed the values of the r2 score and MSE to hceck how good the model is for our dataset.

Polynomial Regression: In the polynomial regression using the scikit learn we are going to do these two steps of adding polynomial features and applying linear regression to it in a pipeline. We have performed the polynomial expansion of the feature X-train represented in a higher order polynomial terms for the multivariate fit.We have computed the values of the r2 score and MSE to check how 
#good the model is for our dataset.

Random Forest Regression: In the Random forest regression using the scikit learn i.e sklearn.ensemble we are importing RandomForestRegressor.We are calling the RandomForestRegressor with the first argument being the number of forest in the random forest and assigned it to some variable.We have computed the values of the r2 score and MSE to check how good the model is for our dataset.



