# PredictingWages_Regression

Python implementation of a case study in Module 2 of the MITProfessionalX course "Data Science: Data to insights". 

The case study is: "Module 2 Case Study - Regression and prediction". This case study is about doing linear regression in R on wages data. I did it in python using two different libraries. 

## Points of interest
The analysis is relatively simple (linear regression), but it might be interesting to see how to do it using the two libraries, [sklearn](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) and [patsy]([Patsy](https://patsy.readthedocs.io/en/latest/#) + [statsmodels](http://www.statsmodels.org/stable/index.html#). 

Also, it is interesting how features were created from the existing ones in the "flexible" model by calculating interactions between existing features. For this task [patsy]([Patsy](https://patsy.readthedocs.io/en/latest/#) was really handy.

Cross validating does not make fully sense in this case but it is intersting to see anyway.

---

## Project description

Our goals are:

1) Predict wages using various characteristics of workers. 

2) Assess the predictive performance using adjusted MSE and R^2 , and out-of-sample MSE and R^2.

## The data

Data is from the March Supplement of the U.S. Current Population Survey, year 2012.

*) Focus on the single (never married) workers with education levels equal to high-school, some college, or college graduates.

*) The sample is of size n ≈ 4,000.

*) The outcome Y is hourly wage, and X are various characteristics of workers.

## The notebook
[Linear Regression.ipynb](https://github.com/aless80/PredictingWages_Regression/blob/master/Linear%20Regression.ipynb)

---
