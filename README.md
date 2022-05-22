# Credit_Risk_Analysis

## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Fir this analysis we will use the  imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the analysis will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Then we will use two new machine learning models to reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 


## Use Resampling Models to Predict Credit Risk
The first portion of the analysis with focus on the imbalanced-learn and scikit-learn libraries to use evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. 

### Naive Random oversampling model

![](https://github.com/timbialek/Amazon_Vine_Analysis/blob/main/Resources/PySpark%20File%20Import%20from%20S3%20bucket.PNG)

* Balanced Accuracy Score: 64.39%
* Precision Score
	High Risk: 1%
	 Low Risk: 100%
* Recall Score
	High Risk: 69%
	 Low Risk: 59%


### Oversampling using SMOTE

Undersampling using ClusterCentroids
![](https://github.com/timbialek/Amazon_Vine_Analysis/blob/main/Resources/customers_table%20in%20pgAdmin.PNG)

products_table
![](https://github.com/timbialek/Amazon_Vine_Analysis/blob/main/Resources/product_table%20in%20pgAdmin.PNG)

review_id_table
![](https://github.com/timbialek/Amazon_Vine_Analysis/blob/main/Resources/review_id%20table%20in%20pgAdmin.PNG)

vine_table
![](https://github.com/timbialek/Amazon_Vine_Analysis/blob/main/Resources/vine_table%20in%20pgAdmin.PNG)

## Deliverable 2 Determine Bias of Vine Reviews

Determine the total number of reviews, the number of 5-star reviews, and the percentage of 5-star reviews for the two types of review (paid vs unpaid).

Paid Reviews Metrics
![](https://github.com/timbialek/Amazon_Vine_Analysis/blob/main/Resources/paid_reviews_metrics.PNG)

Unpaid Reviews Metrics
![](https://github.com/timbialek/Amazon_Vine_Analysis/blob/main/Resources/unpaid_reviews_metrics.PNG)
