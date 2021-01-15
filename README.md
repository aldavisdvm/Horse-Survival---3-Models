# Horse-Survival---3-Models
Comparison of 3 models predicting outcome of horses with colic
## Project Description
The purpose of this project is to compare three machine learning models predicting the outcomes for horses with colic.
The models compared are logistic regression, random forest classifier, and k-nearest neighbor classifier. 
The outcome here has three categories: died on their own, euthanized, or lived.

### Methods Used

* Data Cleaning
* Machine Learning
* Data Visualization
* Predictive Modeling
* Randomized Search Cross Validation

### Technologies

* Jupyter Notebook
* Python
* Pandas and numpy
* Scikit-Learn
* Seaborn and Matplotlib

### Data available from:

https://archive.ics.uci.edu/ml/datasets/Horse+Colic
or
https://www.kaggle.com/uciml/horse-colic

## Project Summary

Three features had to be dropped due to too many missing values (NAN> 50% of data), with the rest of missing
values replaced with mean or mode of the feature. Obviously these decisions would have an impact
on the model performance, and perhaps using a median instead of a mean would be a better choice. 
The three models were fit and scored, with logistic regression and random forest classifier being the top models.
After tuning these top two models using randomized search cross validation, 
it was found that a logistic regression model scored the highest.
