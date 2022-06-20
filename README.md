# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of the analysis is to employ different techniques to train and evaluate models with unbalanced classes because good loans easily outnumber risky loans.

## Results: 
Using data from Loanstats 2019 1st Quarter
- Random Over Sampler algorithms
	Accuracy score: .62
	Confusion Matrix
	52, 35
	5952, 1116
	Classification Report Imbalance
Insert Photo

- Synthetic Minority Oversampling Technique (SMOTE) Algorithms
	Accuracy score was .65
	Confusion Matrix
	56,31
	5840,11278
	Classification Report Imbalance
Insert Photo


- Cluster Centroids Algorithms
	Accuracy score was .51
	Confusion Matrix
	51, 36
	9681, 7437
	Classification Report Imbalance
Insert Photo

- Synthetic Minority Oversampling Technique and Edited Nearest Neighbors (SMOTEENS) Algorithms
	Accuracy score was .63
	Confusion Matrix
	61, 26
	7294, 9824
	Classification Report Imbalance
Insert Photo

- Used the Balanced Random Forest Classifier Algorithms
	Accuracy score was .79
	Confusion Matrix
	59, 28
	1475, 15643
	Classification Report Imbalance
Insert Photo

- Used the Easy Ensemble AdaBoost classifier Algorithms
	Accuracy score was .92
	Confusion Matrix
	79, 8
	979, 16139
	Classification Report Imbalance
Insert Photo



## Summary: 

After testing all 6 machine learning models, the one with the best accuracy score was Easy Ensemble AdaBoost. The accuracy score was .92. Looking closer at the other factors like the confusion matrix, Easy Ensemble Adaboost had the least false positives and the least false negatives. Finally, the Easy Ensemble Adaboost f1 score was the closest to 1. Comparing all the scores with the other 5 machine learning algorithms, Easy Ensemble AdaBoost gave the better scores to use, which would be the recommendation to use for the highly unbalanced data. 
