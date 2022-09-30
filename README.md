# Credit_Risk_Analysis

## Overview:

Jill, a lead data scientist, wanted to build an algorithm dealing with three types of machine learning to predict credit risk. I was asked to assist Jill in this endeavor; in the meantime, Jill decided to teach me the strength and weaknesses compared to machine learning models and the difference between classified and predicted data. 

Jill asked that we apply my training by formatting the machine learning method using python and scikit-learn to solve the inherently unbalanced classification problem that credit risk brings to good loans that are outnumbered by risky loans. We will use the credit card dataset from Lending Club to resampling, oversample, and under sample data to get our recommendation on the performance of the models. We will also be looking at the accurate score to determine the percentage of accuracy of performace, and the precesion and recall percentage. The precision deals with how reliable is the prediction and recall or sensitivity which determines the actual outcome of the prediction   

## Results: 

**Naïve Random Oversampling** 

Here we compare two oversampling algorithms to determine the best performance. 

1.	The naïve random oversampling algorithm involves randomly selecting samples by duplicating from the minority class.  

<img width="680" alt="Screen Shot 2022-09-29 at 9 22 14 PM" src="https://user-images.githubusercontent.com/106892740/193189839-bf48ee96-f6af-41e0-89b0-b3e646b08ab0.png">

2.	The SMOTE algorithm is when the synthetic is generated for the minority class. It helps to overcome overfitting problems posed by random oversampling.

<img width="433" alt="Screen Shot 2022-09-29 at 9 23 21 PM" src="https://user-images.githubusercontent.com/106892740/193189960-12dc4ec0-9637-45ae-a197-8436358545b7.png">

<img width="767" alt="Screen Shot 2022-09-29 at 9 23 35 PM" src="https://user-images.githubusercontent.com/106892740/193189980-f4c7b068-4a3a-4b6f-8721-ed0987a611be.png">

**Undersampling**

Here we test the undersampling algorithms to determine the best performance. 

1.	Undersampling balances uneven datasets by keeping the data in the minority class and decreasing the size. 

<img width="500" alt="Screen Shot 2022-09-29 at 7 05 46 PM" src="https://user-images.githubusercontent.com/106892740/193178732-87192fc9-83fa-4544-bb74-6cbdd863759a.png">

<img width="816" alt="Screen Shot 2022-09-29 at 7 06 02 PM" src="https://user-images.githubusercontent.com/106892740/193178748-adfbc90d-74f8-4cdc-a396-0b79baca0b9c.png">


**Combination (Over and under) Sampling** 

Here we test the undersampling algorithms to determine the best performance. 

1.	Combination Sampling shows the effect of applying an undersampling algorithm after a smote 

<img width="629" alt="Screen Shot 2022-09-29 at 7 08 51 PM" src="https://user-images.githubusercontent.com/106892740/193178757-f75e9924-63e2-4d5e-a45a-be0ec3310c58.png">

<img width="804" alt="Screen Shot 2022-09-29 at 9 26 55 PM" src="https://user-images.githubusercontent.com/106892740/193190379-ed0b36ff-2761-4794-beba-0210be40a12e.png">

**Ensemble Learners**  

An ensemble model is a composite model which combines a series of low-performing or weak classifiers intending to create a strong classifier. 

Here we compare two ensemble algorithms to determine the best performance. 

1.	Balance Random Forest Classifier

The balance random forest classifier bootstrapped set the same size, equal to the size of the minority class, are constructed: one minority and the other majority.  

<img width="544" alt="Screen Shot 2022-09-29 at 9 29 11 PM" src="https://user-images.githubusercontent.com/106892740/193190557-69a734c9-4988-4964-a72a-f9ef05522d27.png">


<img width="737" alt="Screen Shot 2022-09-29 at 9 29 26 PM" src="https://user-images.githubusercontent.com/106892740/193190568-24d8ba0e-11ea-422c-99a1-41cb79a8c2a9.png">

2.	Easy Ensemble AdaBoost Classifier

Easy Ensemble AdaBoost Classifier combines multiple week classifiers to increase the accuracy of classifiers.

<img width="509" alt="Screen Shot 2022-09-29 at 9 30 13 PM" src="https://user-images.githubusercontent.com/106892740/193190690-9c911eaa-9cff-4b46-94b6-d5fae3f32a7b.png">


<img width="721" alt="Screen Shot 2022-09-29 at 9 30 45 PM" src="https://user-images.githubusercontent.com/106892740/193190697-c9d2c261-0862-4b46-98c8-53b05271fb91.png">

## Summary: 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.


