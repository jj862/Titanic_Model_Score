# Titanic_Model_Score
Ranking Models for titanic csv


This notebook will work through seven stages to serve as a comprehensive guide for the data.
* 1.) Define the question or problem
* 2.) Obtain the training and testing data
* 3.) Clean/Scrub and wrangle the data
* 4.) Identify patterns in the data, analyze findings, and explore the data
* 5.) Model the data, make predictions and solutions for the problem
* 6.) Visualize and report the problem-solving step and present the final solution
* 7.) Submit the results

#### Workflow goals

* Classifying. We may want to classify or categorize our samples. We may also want to understand the implications or correlation of different classes with our solution goal.
* Correlating. One can approach the problem based on available features within the training dataset. Which features within the dataset contribute significantly to our solution goal? Statistically speaking, is there a correlation between a feature and a solution goal? As the feature values change does the solution state change as well, and visa-versa? This can be tested for both numerical and categorical features in the given dataset. We may also want to determine the correlation among features other than survival for subsequent goals and workflow stages. Correlating certain features may help in creating, completing, or correcting features.
* Converting. For the modeling stage, one needs to prepare the data. Depending on the choice of model one may require all features to be converted to numerical equivalent values. For instance, converting text categorical values to numeric values.
* Completing. Data preparation may also require us to estimate any missing values within a feature. Model algorithms may work best when there are no missing values.
* Correcting. We may also analyze the given training dataset for errors or possibly inaccurate values within features and try to correct these values or exclude the samples containing the errors. One way to do this is to detect outliers among our samples or features. We may also completely discard a feature if it is not contributing to the analysis or may significantly skew the results.
* Creating. Can we create new features based on an existing feature or a set of features, such that the new feature follows the correlation, conversion, and completeness goals?
* Charting. How to select the right visualization plots and charts depending on the nature of the data and the solution goals?


Model	Scores:
-   Random Forest	86.76
- 	Decision Tree	86.76
- 	KNN	84.85
- 	Logistic Regression	80.36
-   Linear SVC	79.12
-   Perceptron	78.34
- 	Support Vector Machines	78.23
- 	Stochastic Gradient Decent	74.19
- 	Naive Bayes	72.28
