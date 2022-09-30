# Credit_Risk_Analysis

## Overview:

Jill, a lead data scientist, wanted to build an algorithm dealing with three types of machine learning to predict credit risk. I was asked to assist Jill in this endeavor; in the meantime, Jill decided to teach me the strength and weaknesses compared to machine learning models and the difference between classified and predicted data. 

Jill asked that we apply my training by formatting the machine learning method using python and scikit-learn to solve the inherently unbalanced classification problem that credit risk brings to good loans that are outnumbered by risky loans. We will use the credit card dataset from Lending Club to resampling, oversample, and under ample data to get our recommendation on the performance of the models. 

## Results: 

**Naïve Random Oversampling** 

Here we compare two oversampling algorithms to determine the best performance. 

1.	The naïve random oversampling algorithm involves randomly selecting samples by duplicating from the minority class.  

2.	The SMOTE algorithm is when the synthetic is generated for the minority class. It helps to overcome overfitting problems posed by random oversampling. 

**Undersampling**

Here we test the undersampling algorithms to determine the best performance. 

1.	Undersampling balances uneven datasets by keeping the data in the minority class and decreasing the size. 

**Combination (Over and under) Sampling** 

Here we test the undersampling algorithms to determine the best performance. 

1.	Combination Sampling shows the effect of applying an undersampling algorithm after a smote 

**Ensemble Learners**  

An ensemble model is a composite model which combines a series of low-performing or weak classifiers intending to create a strong classifier. 

Here we compare two ensemble algorithms to determine the best performance. 

1.	Balance Random Forest Classifier

The balance random forest classifier bootstrapped set the same size, equal to the size of the minority class, are constructed: one minority and the other majority.  

2.	Easy Ensemble AdaBoost Classifier


Easy Ensemble AdaBoost Classifier combines multiple week classifiers to increase the accuracy of classifiers.

## Summary: 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.


