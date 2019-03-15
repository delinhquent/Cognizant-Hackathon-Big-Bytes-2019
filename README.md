# Fraud Analysis using Logistic Regression
This model was built for Cognizant's Big Byte Hackathon during 2019. It is to help a global credit card company to detect fraudulent transaction. I have created a model based on Logistic Regression.

The dataset can be found here under 'Business Case Data Set': http://bigbytes.sg/the-mission/

This is my first time trying to build a Machine Learning Model and have learnt many things on it such as doing cross-validations (K-fold), undersampling, oversampling, interpreting descriptive data. I decided to use Logistic Regression as it was easy to understand but there are better models which can be used to detect fraudulant transactions better such as Neural Network. 

I have first done EDA to understand more about the dataset which led me to a decision to drop one of the feature. After which, as the data was highly imbalanced, I decided to use random oversampling technique instead of undersampling as the latter will have very little data to work with. I would have preferred to use SMOTE (Synthetic Minority Over-sampling Technique) oversampling but due to the limitation on IBM's platform, I am unable to do import the relevant libraries. I first split my dataset into 80% training data and 20% testing data. After which, I did a K-fold validation to check if the scores are similar.

In my opinion, Logistic Regression is not easily customizable to improve towards a certain metrics such as F1 score and Recall score. However, this is still a fun and interesting experience for me.
