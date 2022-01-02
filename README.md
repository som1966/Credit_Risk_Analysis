# Credit_Risk_Analysis
## Overview of Analysis
  A credit card credit dataset from LendingClub was used to assess credit risk.  To assist with the analysis, Imbalanced-learn and scikit-learn libraries were used to build, evaluate models and resampling techniques.  Oversampling (RandomOverSampler and SMOTE), undersampling(ClusterCentroids) and a combinatorial(SMOTEENN) approach of over and under sampling was completed.  Finally, two new machine learning models were used (BalanceRandomForestClassifier, EasyEnsembleClassifier) to predict credit risk.  Accuracy (performance), Precision(predictive) and Recall(sensitivity) will be evaluated for each technique.

## Results
### Naive Random Oversampling

-Accuracy: 64.4%
  
-Precision: 99.0%
  
-Recall: 64.0%

![image](https://user-images.githubusercontent.com/89953246/147890219-4b10facf-6b7e-4b87-9ff7-62a0df2f2d7b.png)

### SMOTE (Oversampling)

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

### Balanced Random Forest Classifier

-Accuracy:  78.2%

-Precision:  99.0%

-Recall:  88.0%

![image](https://user-images.githubusercontent.com/89953246/147890531-a8836a2a-bf24-4cee-a7b2-171f303dc29b.png)

### Easy Ensemble AdaBoost Classifier

-Accuracy:  91.8%

-Precision: 99.0%

-Recall: 94.0%

![image](https://user-images.githubusercontent.com/89953246/147890552-65a63e35-cad3-49a2-acc3-9adcf75cdf04.png)


## Summary
Accuracy, precision and recall scores were reveiwed for each technique.  The accuracy score (performance) was heavily weighted in providing the recommendation for which technique should be used.  The ensemble algorithms were the better choice for this type of analysis; the Easy Ensemble AdaBoost Classier would be the first choice with an accuracy score of 92% followed by the Balanced Random Classifier (78%).  Precision scores were the same for all the models. Naive and SMOTE oversampling techniques were comparative in accuracy.  Finally, the techniques used for future analyses should be reflective of the dataset and the analysis that is required.
