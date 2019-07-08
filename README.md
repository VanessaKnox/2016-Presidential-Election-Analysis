# 2016 U.S. Voter Behavior and Election Analysis

<img width="673" alt="countrypic" src="https://user-images.githubusercontent.com/30671201/60775770-4c4e6980-a0db-11e9-97b9-dbc0750428ae.png">

An analysis on the 2016 presidential election to determine how high of an accuracy voter behavior predictions, such as classifying in a minority or upper class, can determine the outcome of an election. 

Voter behavior prediction (and thus election forecasting) can be a hard problem because there are numerous
random variables that need to be accounted for in terms of what a voter will decide or say. These variables tend to be immeasurable since they rely on a voter's background and mindset, leaving it not easy to develop predictions considering the constant change in state and national economy, or changes in societal conditions, etc.

Ultimately, there are many factors that need to be considered, but not all of them are easily predicted, leading to errors that can have drastic changes in the overall election forecasting.

### Built With
R Studio 

### Methodology
* Data Wrangling
* Principal Component Analysis
* Hierarchical Clustering
* Decision Tree Classification
* Logistic Regression
* Lasso Regression
* Gradient Boosting
* Bootstrap Aggregating
* Random Forest 

### Conclusions
According to the ROC curves, the logistic regression and lasso methods return the highest true positive rate,
as both curves hug the upper left corner the most. We also decided to calculate the AUC (Area Under
Curve) for each method to better determine which method provides the best predictions. The AUC for the
decision tree method is the lowest at 0.8297726 while the AUC values for logistic regression and the lasso
method are the highest and the exact same value at 0.9528419, confirming that these two methods are the
best predictive models.

In regards to which classifier is more appropriate, we believe that in the context of understanding voter
behavior which entails narrowing down the most important variables, the decision tree fails to answer this
election question better or equally as well as the lasso and logistic regression models. The lasso is able to
do so with our large data set, and the logistic regression model helps us better identify, through perfect
separation, the best candidate in the election for each variable group, thus giving us more insight on voter
behavior.

### Contributors
* Lauren Wong
* Alison Do
