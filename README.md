# Cognizant: Big Bytes Challenge 2019
This challenge was organized by Cognizant and I had the opportunity to build my model on IBM's Cloud Private Experiences Platform. Details of the challenge and dataset can be found at: http://bigbytes.sg/the-mission/.

# Objective
To build a machine learning model to reduce the time and effort for investigations as well as improve on the fraud recover through early identification and proactive management of suspicious transactions

# Data preparation
1) Random Oversampling on minority class 0 for training data set
2) 80% Training and 20% Testing split
3) Standardizing of features

# Chosen Model
Logistic Regression

# Reflection
This is my first time trying to build a Machine Learning Model and have learnt many things on it such as doing cross-validations (K-fold), undersampling, oversampling, interpreting descriptive data. I built a Logistic Regression model as a baseline model as it was easy to understand and simple to implement.

I have first done EDA to understand more about the dataset which led me to a decision to drop one of the feature. After which, as the data was highly imbalanced, I decided to use random oversampling technique instead of undersampling as the latter will have very little data to work with. I would have preferred to use SMOTE (Synthetic Minority Over-sampling Technique) oversampling but due to the limitation on IBM's platform, I am unable to do import the relevant libraries. I first split my dataset into 80% training data and 20% testing data, then proceeded to oversample only the training set. A K-fold validation was then conducted using the same process.

My team used the Neural Network as our final submission. However, after this challenge, we felt that interpretability was important for businesses to understand what features caused the model to label the transaction important. Hence, we should not be using Neural Network but use ensemble methods. This is still a fun and interesting experience for me.

# Note
The one we submitted for the challenge was not this model. It was done with Neural Network by my group mate. His project's git url: https://github.com/junronglau/Big-Bytes-Challenge-2019
