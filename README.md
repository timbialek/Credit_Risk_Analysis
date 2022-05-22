# Credit_Risk_Analysis

## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Fir this analysis we will use the  imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the analysis will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Then we will use two new machine learning models to reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 


## Use Resampling Models to Predict Credit Risk
The first portion of the analysis with focus on the imbalanced-learn and scikit-learn libraries to use evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. 

### Naive Random oversampling model

![](https://github.com/timbialek/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Sampling.PNG)

* Balanced Accuracy Score: 64.39%
* Precision Score:<br>
	* High Risk: 1%  
	 * Low Risk: 100%
* Recall Score"<br>
	* High Risk: 69%
	 * Low Risk: 59%


### Oversampling using SMOTE

![](https://github.com/timbialek/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling.PNG)

### Undersampling using ClusterCentroids

![](https://github.com/timbialek/Credit_Risk_Analysis/blob/main/Resources/Undersampling%20ClusterCentroids.PNG)

### Balance Random Forests

![](https://github.com/timbialek/Credit_Risk_Analysis/blob/main/Resources/Balance%20Random%20Forest.PNG)

### Easy Ensemble AdaBoost

![](https://github.com/timbialek/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost.PNG)

### Combiniation Sampling

![](https://github.com/timbialek/Credit_Risk_Analysis/blob/main/Resources/Combination%20Sampling.PNG)

