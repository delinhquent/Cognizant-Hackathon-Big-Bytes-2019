# Cognizant: Big Bytes Challenge 2019
Details of the challenge and dataset can be found at: http://bigbytes.sg/the-mission/ 

# Objective
To build a machine learning model to reduce the time and effort for investigations as well as improve on the fraud recover through early identification and proactive management of suspicious transactions

# Data preparation
Random Oversampling on minority class 0 for training data set
80% Training and 20% Testing split
Standardizing of features

# Chosen Model
Logistic Regression

# Reflection
This is my first time trying to build a Machine Learning Model and have learnt many things on it such as doing cross-validations (K-fold), undersampling, oversampling, interpreting descriptive data. I decided to use Logistic Regression as it was easy to understand but there are better models which can be used to detect fraudulant transactions better such as Neural Network. 

I have first done EDA to understand more about the dataset which led me to a decision to drop one of the feature. After which, as the data was highly imbalanced, I decided to use random oversampling technique instead of undersampling as the latter will have very little data to work with. I would have preferred to use SMOTE (Synthetic Minority Over-sampling Technique) oversampling but due to the limitation on IBM's platform, I am unable to do import the relevant libraries. I first split my dataset into 80% training data and 20% testing data. After which, I did a K-fold validation (20 folds, could set it to around 5 to 10 as it would not make much of a difference to the metrics) to check if the scores are similar.

In my opinion, other models such as Neural Network has the capability to be trained to be specialized to detect fraudulant transactions accurately based on the different features, unlike Logistic Regression. However, this is still a fun and interesting experience for me.
