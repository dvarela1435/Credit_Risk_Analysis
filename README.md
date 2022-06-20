# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of the analysis is to employ different techniques to train and evaluate models with unbalanced classes because good loans easily outnumber risky loans.

## Results: 
Using data from Loanstats 2019 1st Quarter
- Random Over Sampler algorithms

	Accuracy score: .62
	
	Confusion Matrix
	
|                  | Predicted True  | Predicted False |
| -                | -               | -               | 
| Actually True    | 52              | 35              |
| Actually False   | 5,952           | 1,116           |
	
Classification Report Imbalance

![screen_1](/Resources/RandomOverSampler_report.png)

- Synthetic Minority Oversampling Technique (SMOTE) Algorithms

Accuracy score: .65
	
Confusion Matrix
	
|                  | Predicted True  | Predicted False |
| -                | -               | -               | 
| Actually True    | 56              | 31              |
| Actually False   | 5,840           | 1,1278          |

Classification Report Imbalance

![screen_2](/Resources/SMOTE_report.png)


- Cluster Centroids Algorithms

	Accuracy score was .51
	
	Confusion Matrix
	
|                  | Predicted True  | Predicted False |
| -                | -               | -               | 
| Actually True    | 51              | 36              |
| Actually False   | 9,681           | 7,437           |

Classification Report Imbalance
	
![screen_3](/Resources/Cluster_Centroids_report.png)

- Synthetic Minority Oversampling Technique and Edited Nearest Neighbors (SMOTEENS) Algorithms

	Accuracy score was .63

	Confusion Matrix
	
|                  | Predicted True  | Predicted False |
| -                | -               | -               | 
| Actually True    | 61              | 26              |
| Actually False   | 7,294           | 9,824           |
	
Classification Report Imbalance
	
![screen_4](/Resources/SMOTEENN_report.png)

- Used the Balanced Random Forest Classifier Algorithms

	Accuracy score was .79

	CConfusion Matrix
	
|                  | Predicted True  | Predicted False  |
| -                | -               | -                | 
| Actually True    | 59              | 28               |
| Actually False   | 1,475           | 15,643           |

Classification Report Imbalance
	
![screen_5](/Resources/Balanced_Random_Forest_Classifier_report.png)

- Used the Easy Ensemble AdaBoost classifier Algorithms

	Accuracy score was .92
	
	Confusion Matrix
	
|                  | Predicted True  | Predicted False  |
| -                | -               | -                | 
| Actually True    | 79              | 8                |
| Actually False   | 979             | 16,139           |
	
Classification Report Imbalance
	
![screen_6](/Resources/Easy_Ensemble_AdaBoost_Classifier_report.png)



## Summary: 

After testing all 6 machine learning models, the one with the best accuracy score was Easy Ensemble AdaBoost. The accuracy score was .92. Looking closer at the other factors like the confusion matrix, Easy Ensemble Adaboost had the least false positives and the least false negatives. Finally, the Easy Ensemble Adaboost f1 score was the closest to 1. Comparing all the scores with the other 5 machine learning algorithms, Easy Ensemble AdaBoost gave the better scores to use, which would be the recommendation to use for the highly unbalanced data. 
