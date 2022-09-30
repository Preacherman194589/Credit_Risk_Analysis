# Credit_Risk_Analysis

## Overview:

Jill, a lead data scientist, wanted to build an algorithm dealing with three types of machine learning to predict credit risk. I was asked to assist Jill in this endeavor; in the meantime, Jill decided to teach me the strength and weaknesses compared to machine learning models and the difference between classified and predicted data. 

Jill asked that we apply my training by formatting the machine learning method using python and scikit-learn to solve the inherently unbalanced classification problem that credit risk brings to good loans that are outnumbered by risky loans. We will use the credit card dataset from Lending Club to resampling, oversample, and undersample data to get our recommendation on the performance of the models. We will also be looking at the accurate score to determine the percentage of accuracy of performance and the precision and recall percentage. The precision deals with how reliable the prediction is and recall or sensitivity which determines the actual outcome of the prediction   

## Results: 

**Naïve Random Oversampling** 

Here we compare two oversampling algorithms to determine the best performance. 

1.	The naïve random oversampling algorithm involves randomly selecting samples by duplicating from the minority class.  

As we look at the accurate score, we notice a score of 63% of accuracy. However, the precision for high risk is only 0.01%, and the low risk is 1.0%. But when we look at recall, we see a 59% high risk and 69% low risk. These numbers are based on my first model used for the outcome. 

<img width="680" alt="Screen Shot 2022-09-29 at 9 22 14 PM" src="https://user-images.githubusercontent.com/106892740/193189839-bf48ee96-f6af-41e0-89b0-b3e646b08ab0.png">

2.	The SMOTE algorithm is when the synthetic is generated for the minority class. It helps to overcome overfitting problems posed by random oversampling.

As we look at the accurate score, we notice a score of 62% of accuracy. However, the precision for high risk is only 0.01%, and the low risk is 1.0%. But when we look at recall, we see a 57% high risk and 46% low risk. These numbers are based on my first model used for the outcome. 

<img width="433" alt="Screen Shot 2022-09-29 at 9 23 21 PM" src="https://user-images.githubusercontent.com/106892740/193189960-12dc4ec0-9637-45ae-a197-8436358545b7.png">

<img width="767" alt="Screen Shot 2022-09-29 at 9 23 35 PM" src="https://user-images.githubusercontent.com/106892740/193189980-f4c7b068-4a3a-4b6f-8721-ed0987a611be.png">

**Undersampling**

Here we test the undersampling algorithms to determine the best performance. 

1.	Undersampling balances uneven datasets by keeping the data in the minority class and decreasing the size. 

As we look at the accurate score, we notice a score of 62% of accuracy. However, the precision for high risk is only 0.01%, and the low risk is 1.0%. But when we look at recall, we see a 61% high risk and 45% low risk. These numbers are based on my first model used for the outcome. 

<img width="483" alt="Screen Shot 2022-09-29 at 9 55 48 PM" src="https://user-images.githubusercontent.com/106892740/193193304-dd819cfd-115b-4ea9-82c3-2de77262e1b7.png">

<img width="734" alt="Screen Shot 2022-09-29 at 9 56 01 PM" src="https://user-images.githubusercontent.com/106892740/193193321-20856ab2-8ee2-4bf2-b110-be142efad2e3.png">

**Combination (Over and under) Sampling** 

Here we test the undersampling algorithms to determine the best performance. 

1.	Combination Sampling shows the effect of applying an undersampling algorithm after a smote 

As we look at the accurate score, we notice a score of 62% of accuracy. However, the precision for high risk is only 0.01%, and the low risk is 1.0%. But when we look at recall, we see a 72% high risk and 57% low risk. These numbers are based on my first model used for the outcome. 

<img width="629" alt="Screen Shot 2022-09-29 at 7 08 51 PM" src="https://user-images.githubusercontent.com/106892740/193178757-f75e9924-63e2-4d5e-a45a-be0ec3310c58.png">

<img width="804" alt="Screen Shot 2022-09-29 at 9 26 55 PM" src="https://user-images.githubusercontent.com/106892740/193190379-ed0b36ff-2761-4794-beba-0210be40a12e.png">

**Ensemble Learners**  

An ensemble model is a composite model which combines a series of low-performing or weak classifiers intending to create a strong classifier. 

Here we compare two ensemble algorithms to determine the best performance. 

1.	Balance Random Forest Classifier

The balance random forest classifier bootstrapped set the same size, equal to the size of the minority class, are constructed: one minority and the other majority.  

As we look at the accurate score we noticed a score of 78% of accuracy, however the precision for high risk is only 0.04% and the low risk is 1.0%. But when we look at recall, we see a 67% high risk and 91% low risk. This numbers are based on my first model used for outcome. 

<img width="544" alt="Screen Shot 2022-09-29 at 9 29 11 PM" src="https://user-images.githubusercontent.com/106892740/193190557-69a734c9-4988-4964-a72a-f9ef05522d27.png">


<img width="737" alt="Screen Shot 2022-09-29 at 9 29 26 PM" src="https://user-images.githubusercontent.com/106892740/193190568-24d8ba0e-11ea-422c-99a1-41cb79a8c2a9.png">

2.	Easy Ensemble AdaBoost Classifier

Easy Ensemble AdaBoost Classifier combines multiple week classifiers to increase the accuracy of classifiers.

As we look at the accurate score we noticed a score of 92% of accuracy, however the precision for high risk is only 0.07% and the low risk is 1.0%. But when we look at recall, we see a 91% high risk and 94% low risk. This numbers are based on my first model used for outcome. 

<img width="509" alt="Screen Shot 2022-09-29 at 9 30 13 PM" src="https://user-images.githubusercontent.com/106892740/193190690-9c911eaa-9cff-4b46-94b6-d5fae3f32a7b.png">


<img width="721" alt="Screen Shot 2022-09-29 at 9 30 45 PM" src="https://user-images.githubusercontent.com/106892740/193190697-c9d2c261-0862-4b46-98c8-53b05271fb91.png">

## Summary: 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.


