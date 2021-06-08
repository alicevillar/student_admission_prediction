# Predicting students admission with Logistic Regression, Decision Tree, SVM (SVC) and Random Forest

## Description 

The purpose of this project is to create and compare different ML models to predict students admission to graduate school. As a starting point, I used a tutorial from [UCLA](http://stats.idre.ucla.edu/r/dae/logit-regression/). This tutorial applies Logistic Regression with R, but I decided to use Python.

The dataset provided has unequal class distribution. This imbalancement was not handled in the tutorial, so it was such a great opportunity for me to fix the imbalanced dataset. After the resampling, I used the Logistic Regression again and, to take the project further, I also used other four algorithms. In conclusion, I created a graphic to compare the accuracies score for the diffrerent ML algorithms (Accuracy comparison graph).

#### Quick Start  
[Check out](          ) a static version of the notebook with Jupyter NBViewer from the comfort of your web browser.
 
## Problem Statement

A researcher is interested in how variables, such as GRE (Graduate Record Exam scores), GPA (grade point average) and prestige of the undergraduate institution,
effect admission into graduate school. The response variable, admit/don’t admit, is a binary variable.This data set has a binary response (outcome, dependent) variable called admit, which is equal to 1 if the individual was admitted to graduate school, and 0 otherwise. There are three predictor variables: gre, gpa, and rank. We will treat the variables gre and gpa as continuous. The variable rank takes on the values 1 through 4. Institutions with a rank of 1 have the highest prestige, while those with a rank of 4 have the lowest. [Source : UCLA](http://stats.idre.ucla.edu/r/dae/logit-regression/)

## Approach 

My project is organized in two Chapters:

#### => Chapter 1 - Predicting students admission with Logistic Regression 

The analysis is divided in three parts: 
* PART 1: Data Handling -> Importing Data with Pandas, Cleaning Data, Data description.
* PART 2: Data Analysis -> Supervised ML Technique:Logistic Regression.
* PART 3: Valuation of the Analysis -> Performance measurement + K-folds cross validation to evaluate results locally.

#### => Chapter 2 - Predicting students admission with Logistic Regression, Decision Tree, SVM (SVC) and Random Forest

he analysis is divided in three parts: 
* PART 1: Data Handling -> Importing Data with Pandas, Cleaning Data, Data description.
* PART 2: Data Analysis -> Supervised ML Technique:Logistic Regression, Decision Tree, SVM (SVC) and Random Forest
* PART 3: Valuation of the Analysis -> Performance measurement + K-folds cross validation to evaluate results locally + Accuracy comparison graph
 
## Dependencies 
 
* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [SciKit-Learn](https://scikit-learn.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
 
## Results
 In Chapter 1 the data has shown that one class dominates the other. In such a case, the model will have a hard time learning from data to predict future classes. Thus, I decided to apply a resampling method. After this, I used the Logistic Regression again to the new dataset and another three algorithms: Decision Tree, SVM (SVC) and Random Forest. Finally, I did the Valuation Analisis (Performance Measurement & K-Fold) of all the ML models and compared the accuracy of the different models on a graphic. 
 
