# Credit-Risk

For this project a csv file from LendingClub, a peer-to-peer lending services company will used to analyse Credit Risk.

Using the imbalanced-learn and scikit-learn libraries, three machine learning models are evaluated by using resampling to determine which is better at predicting credit risk.

*** Deliverable 1: Use Resampling Models to Predict Credit Risk

a) The data is loaded and data is split into Training and Testing data

b) Three algorithms are used:

OverSampling
* Naive Random Oversampling algorithm
* SMOTE Oversampling algorithm

UnderSampling
* Cluster Centroids algorithm

*** Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk

Use a combination of the two previous algorithms:

Combination (Over and Under)
* SMOTEENN algorithm


*** Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk 

a) The data is loaded and data is split into Training and Testing data

b) Two ensemble algorithms will be trained:
Balanced Random Forest Classifier algorithm
Easy Ensemble AdaBoost Classifier¶ algorithm

Overview of the analysis: 
We want to compare Machine Learning algorithms using Oversamplimg models and Ensemble Classifier models.

RESULTS: (Please refer to Images folder) 

*** Sampling ML models
a) Oversamling (Naive Random)
    - Balanced Accuracy: 0.65
    - Precision: 0.99
    - Recall: 0.59

b) SMOTE Oversampling
    - Balanced Accuracy: 0.66
    - Precision:b 0.99
    - Recall: 0.69

c) Undersampling
    - Balanced Accuracy: 0.54
    - Precision: 0.99
    - Recall: 0.40

d) Combination (Over and Under) Sampling
    - Balanced Accuracy: 0.64
    - Precision: 0.99
    - Recall: 0.57

*** Ensemble ML models
e) Balanced Random Forest Classifier
    - Balanced Accuracy: 0.78
    - Precission: 0.99
    - Recall: 0.87

f) Easy Ensemble AdaBoost Classifier
    - Balanced Accuracy: 0.93
    - Precision: 0.99
    - Recall: 0.94

SUMMARY:

Comparing all six models Sampling and Ensembled, for this particular case, it seems Ensembled models provide improved Balanced Accuracy, Precision and Recall records when compared to results using the Sampling models. Among the Sampling models, Oversampling proved to be outperform undersampling.

Whenever possibly, it should be used both approaches and draw conclusions from there. For this particular case, Essemble algorithms should be consider first.