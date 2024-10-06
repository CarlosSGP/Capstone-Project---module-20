# Capstone-Project---module-20

**Title: Plant identification based on image processed leaf data**
 

*Objective:* 

The objective of this project is to develop a machine learning algorithm that is able to accurately identify a plant species based on data extracted from processed images. 

 

*Question:* 

What plant am I looking at? 

 

*Data Requirements:*

I will use an open source dataset on Kaggle (https://www.kaggle.com/c/leaf-classification/data Links to an external site.) that contains data for up to 99 species of plants based on 1500+ images. 

 

*Techniques:*

Given this is a multiclass classification problem, I had to go through a number of steps and techniques with the provided dataset. This capstone project is using a dataset from an open Kaggle competition which provides a train and test set to measure against peers. The test set does not have labels so I was not able to use it for my capstone project. Instead, I split the train set data into a train and validation sets for the training and measurement of effectivements of my classifier models. Further, I used k-fold split for enhancement of the models performance with a 10 fold split. Since species are categorical values, I used label encoder to convert them to numbers that the models could use. 

Once I had split my data, encoded it and had done k-fold for cross validation I then trained 4 models: SVM, Naive Bayes, K-nearest neihghbors and Logistic regression. The two key metrics I was using to evaluate these models were Accuracy and log loss

The model that performed best was logistic regression with an accuracy of 98.56% and a log loss of 0.19. 
 
