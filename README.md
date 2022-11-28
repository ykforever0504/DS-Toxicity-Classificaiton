# DS-Toxicity-Classificaiton

This experiment was conducted using the controlled variable method. 

First, the dataset was processed using tfidf and the data was evaluated statistically after training with two models, naive bayes and logistic regression, respectively. 

Secondly, the prediction performance gap of the five groups is explored as well as the narrowing measures.

I divided the dataset into five groups according to identity, and counted the accuracy of each group trained by Logistic Regression (LR) and the variance of the accuracy of the five groups. 

I scaled the data categories distribution of the training and validation sets to be the same by downsampling the larger class and recorded the variance data of the accuracy. In addition, I used an overfitting countermeasure, i.e. training with a logistic regression bagging model.

The last is to explore the impact of different feature engineering on prediction accuracy. I used the bag of words model to vectorise the raw data, and the other conditions are as the same as the first one.
