# Credit_Risk_Analysis

## Overview

FastLending a peer to peer lending services company wants to use machine learning to assess credit risk. Several resampling and testing models will be used predict credit risk. 

## Results

#### Naive Random Oversampling
![Naive_Oversampling.png](https://github.com/Brandonkish1/Credit_Risk_Analysis/blob/main/images/Naive_Oversampling.png)

The accuracy score was 63.7%. The precision for high risk loans was only 1% and recall was 62%.

#### SMOTE
![SMOTE_Oversampling.png](https://github.com/Brandonkish1/Credit_Risk_Analysis/blob/main/images/SMOTE_Oversampling.png)

The accuracy score was 63.0%. The precision for high risk loans was only 1% and recall was 62%.

#### Undersampling
![Undersampling.png](https://github.com/Brandonkish1/Credit_Risk_Analysis/blob/main/images/Undersampling.png)

The accuracy score was 52.9%. The precision for high risk loans was only 1% and recall was 61%.

#### Combination Oversampling and Undersampling
![Combo.png](https://github.com/Brandonkish1/Credit_Risk_Analysis/blob/main/images/Combo.png)

The accuracy score was 65.3%. The precision for high risk loans was only 1% and recall was 71%.

#### Balanced Random Forest Classifier
![Balance_Random_Forest.png](https://github.com/Brandonkish1/Credit_Risk_Analysis/blob/main/images/Balance_Random_Forest.png)

The accuracy score was 78.8%. The precision for high risk loans was only 4% and recall was 67%.

#### Easy Ensemble 
![Ensemble_AdaBoost.png](https://github.com/Brandonkish1/Credit_Risk_Analysis/blob/main/images/Ensemble_AdaBoost.png)

The accuracy score was 92.5%. The precision for high risk loans was only 7% and recall was 91%.


## Summary

The Easy Ensemble model seemed to give the best results. It had the highest accuracy score by far (92% vs. 53%-79%). Also it did the best predicting high risk loans(7% vs 1%-4%). It had the best recall rate (91%) of all the models too (62%-71%).
