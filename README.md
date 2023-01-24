# cs5265
Vanderbilt Computer Science 5265 Project

# Quick Navigation
[Background](#background)

# Background
In this assignment, we were asked to examine the default of credit card customers dataset from the UCI Machine Learning Repository. The raw dataset will be cleaned, validated, and then additional predictor variables will be engineered by discretizing some of the continuous variables and by combining variables into new summary statistics. The feature dataset will then used with several algorithms to determine the best predictor model. The models will then be evaluated and the best model will be selected for implementation in a production environment.

# Project Description
The Default of Credit Card Customer (DC3) data set, accessed from the UCI Machine Learning Repository, was retrieved in January, 2023. The data consists of 30,000 observations on 24 predictor variables and a single binary response variable of payment default of credit card customers in Taiwan from April, 2005 to September, 2005. Default indicates whether the customer failed to repay a debt (e.g., 1, yes; 0, no). A default can occur when a customer is unable to make timely payments, misses payments, or avoids or stops making payments.

# Performance Metrics
To evaluate model performance in each experiment, we will focus on the predictive balance accuracy. Balance accuracy can bet determined from the following equation:

$Balance Accuracy = \frac{Sensitivity + Specificity}{2}$

where $Sensitivity$ is the true positive rate, $Specificity$ is the true negative rate. Sensitivity or the True Positive Rate (TPR) is the percentage of true positive cases per total number of positive cases (i.e. true positive and false positive). 

$Sensitivity = \frac{TP}{TP + FP}$

Specificity or the True Negatie Rate (TNR) is the percentage of true negative cases per total number of negative cases (i.e. true negative and false negative).

$Specificity = \frac{TN}{TN + FN}$