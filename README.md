# Credit_Risk_Analysis

# Overview 

The purpose of this analysis was to build and evaluate various machine learning models to evaluate individual customer credit risk. The dataset that was used for this challenge is from LendingClub, a peer-to-peer lending services company. 

The machine learning algorithms used were:

RandomOverSampler
SMOTE
ClusterCentroids
SMOTEENN
BalancedRandomForestClassifier
EasyEnsembleClassifier
The models were run and then evaluated for performance and accuracy at predicting credit risk.


# Results 

## Naive Random Oversampling 

![Naive Random Oversamping](https://user-images.githubusercontent.com/107447648/205473202-79bdf8e4-7a76-4c93-b661-acfbc05a9d88.png)

Balanced Accuracy: 0.6361855437510828
Precision: low for High-risk loans and is high for Low-risk loans
High/Low risk = .60/.67

## SMOTE Oversampling

![SMOTE Oversamping](https://user-images.githubusercontent.com/107447648/205473354-1e5e58ef-4000-43d4-a574-949b5685a63e.png)

Balanced Accuracy: 0.6289276059481651
Precision: low for High-risk loans and is high for Low-risk loans
High/Low risk = 0.62/0.64

## Undersampling 

![Undersampling](https://user-images.githubusercontent.com/107447648/205473871-b88f082c-4632-4fec-ae59-d6f426e440e6.png)

Balanced Accuracy: 0.6289276059481651
Precision: low for High-risk loans and is high for Low-risk loans
High/Low risk = 0.62/0.64

## Combination (Over and Under) Sampling 

![Combination (Over and Under) Sampling ](https://user-images.githubusercontent.com/107447648/205474034-346891ef-97d5-4091-b39b-5777ce8806bf.png)

Balanced Accuracy: 0.6630316545197432
Precision: low for High-risk loans and is high for Low-risk loans
High/Low risk =  0.73/ 0.59 

## Balanced Random Forest Classifier 

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/107447648/205474263-2d6b2dec-4db6-4606-999e-4656ffc8ddad.png)

Balanced Accuracy: 0.7877672625306695
Precision: low for High-risk loans and is high for Low-risk loans
High/Low risk = .67/.91

## Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/107447648/205474321-5e804918-139b-4172-9b06-e604334260dc.png)

Balanced Accuracy: 0.925427358175101
Precision: low for High-risk loans and is high for Low-risk loans
High/Low risk = .91/.94

# Summary

In conclusion, credit-risk is a difficult thing to predict, even for advanced machine learning algorithms with 93 columns of data to process.
