# Credit_Risk_Analysis
## Overview of Analysis
A credit card credit dataset from LendingClub was used to assess credit risk.  To assist with the analysis, Imbalanced-learn and scikit-learn libraries were used to build, evaluate models and resampling techniques.  Oversampling (RandomOverSampler and SMOTE), undersampling(ClusterCentroids) and a combinatorial(SMOTEENN) approach of over and under sampling was completed.  Finally, two new machine learning models were used (BalanceRandomForestClassifier, EasyEnsembleClassifier) to predict credit risk.  Accuracy, Precision and Recall will be evaluated for each technique.

## Results
### Naive Random Oversampling

  -Accuracy: 64.4%
  
  -Precision: 99.0%
  
  -Recall: 64.0%

![image](https://user-images.githubusercontent.com/89953246/147890219-4b10facf-6b7e-4b87-9ff7-62a0df2f2d7b.png)

### SMOTE Oversampling

  -Accuracy:  66.1%
  
  -Precision: 99.0%
  
  -Recall: 66.0%
  
 ![image](https://user-images.githubusercontent.com/89953246/147890333-1116ca2f-6aad-4243-9215-c2f0714e6751.png)
 
 ### Undersampling (ClusterCentroids)
 
 -Accuracy:  45.0%
 
 -Precision: 99.0%
  
 -Recall: 45.0%
 
 ![image](https://user-images.githubusercontent.com/89953246/147890369-3b6c5bd1-4131-40a8-92b5-f0598122242e.png)
 
 ### SMOTEENN (Combination of Over and Under Sampling)

-Accuracy: 54.2%

-Precision: 99.0%

-Recall:  54.0%

![image](https://user-images.githubusercontent.com/89953246/147890422-90346784-e909-4f77-9a83-04144065d10c.png)



## Summary
