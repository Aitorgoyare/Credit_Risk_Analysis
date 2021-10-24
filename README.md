# Credit_Risk_Analysis

## Overview of the analysis: 

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: 

![](https://github.com/Aitorgoyare/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling.png)
![](https://github.com/Aitorgoyare/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.png)
![](https://github.com/Aitorgoyare/Credit_Risk_Analysis/blob/main/Resources/Combination(over%20and%20undersampling).png)
![](https://github.com/Aitorgoyare/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png)
![](https://github.com/Aitorgoyare/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20oversampling.png)
![](https://github.com/Aitorgoyare/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)




## Summary: 

After running the different models and combining them we can determine that the most effective model for predicting which loans are most at risk is the Easy Ensemble. It would appear that the Easy Ensemble seems to have the best balance of all the models because of it is high accuracy score and good balance of accuracy and recovery scores.
