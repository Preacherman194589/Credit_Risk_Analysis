# Credit_Risk_Analysis

## Overview:

Jill, a lead data scientist, wanted to build an algorithm dealing with three types of machine learning to predict credit risk. I was asked to assist Jill in this endeavor; in the meantime, Jill decided to teach me the strength and weaknesses compared to machine learning models and the difference between classified and predicted data. 

Jill asked that we apply my training by formatting the machine learning method using python and scikit-learn to solve the inherently unbalanced classification problem that credit risk brings to good loans that are outnumbered by risky loans. We will use the credit card dataset from Lending Club to resampling, oversample, and under ample data to get our recommendation on the performance of the models. 

## Results: 

**Naïve Random Oversampling** 

Here we compare two oversampling algorithms to determine the best performance. 

1.	The naïve random oversampling algorithm involves randomly selecting samples by duplicating from the minority class.  

<img width="1160" alt="Screen Shot 2022-09-29 at 7 00 06 PM" src="https://user-images.githubusercontent.com/106892740/193178422-603cdf62-09ca-4158-8138-987147b3a5c7.png">


2.	The SMOTE algorithm is when the synthetic is generated for the minority class. It helps to overcome overfitting problems posed by random oversampling.

<img width="1097" alt="Screen Shot 2022-09-29 at 7 01 00 PM" src="https://user-images.githubusercontent.com/106892740/193178520-445b127d-faf4-4726-95ba-25855bb47d56.png">

<img width="1134" alt="Screen Shot 2022-09-29 at 7 01 14 PM" src="https://user-images.githubusercontent.com/106892740/193178616-64e1684e-4b23-409c-a3a5-1bb1335998f2.png">

**Undersampling**

Here we test the undersampling algorithms to determine the best performance. 

1.	Undersampling balances uneven datasets by keeping the data in the minority class and decreasing the size. 

<img width="500" alt="Screen Shot 2022-09-29 at 7 05 46 PM" src="https://user-images.githubusercontent.com/106892740/193178732-87192fc9-83fa-4544-bb74-6cbdd863759a.png">

<img width="816" alt="Screen Shot 2022-09-29 at 7 06 02 PM" src="https://user-images.githubusercontent.com/106892740/193178748-adfbc90d-74f8-4cdc-a396-0b79baca0b9c.png">


**Combination (Over and under) Sampling** 

Here we test the undersampling algorithms to determine the best performance. 

1.	Combination Sampling shows the effect of applying an undersampling algorithm after a smote 

<img width="629" alt="Screen Shot 2022-09-29 at 7 08 51 PM" src="https://user-images.githubusercontent.com/106892740/193178757-f75e9924-63e2-4d5e-a45a-be0ec3310c58.png">

Screen Shot 2022-09-29 at 7.09.09 PM

**Ensemble Learners**  

An ensemble model is a composite model which combines a series of low-performing or weak classifiers intending to create a strong classifier. 

Here we compare two ensemble algorithms to determine the best performance. 

1.	Balance Random Forest Classifier

The balance random forest classifier bootstrapped set the same size, equal to the size of the minority class, are constructed: one minority and the other majority.  

<img width="614" alt="Screen Shot 2022-09-29 at 7 26 41 PM" src="https://user-images.githubusercontent.com/106892740/193178806-b267a4b9-e73d-47a1-88d6-f191bc227253.png">

<img width="918" alt="Screen Shot 2022-09-29 at 7 26 57 PM" src="https://user-images.githubusercontent.com/106892740/193178825-1f0b9108-a2b5-4a24-a9b4-45cee5ab3175.png">


2.	Easy Ensemble AdaBoost Classifier

Easy Ensemble AdaBoost Classifier combines multiple week classifiers to increase the accuracy of classifiers.

<img width="579" alt="Screen Shot 2022-09-29 at 7 28 24 PM" src="https://user-images.githubusercontent.com/106892740/193178913-35d92a91-b908-40ee-a4df-7294b7d7387d.png">

<img width="787" alt="Screen Shot 2022-09-29 at 7 28 38 PM" src="https://user-images.githubusercontent.com/106892740/193179005-bba39b49-adbe-465e-ad36-94eba4be577e.png">



## Summary: 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.


