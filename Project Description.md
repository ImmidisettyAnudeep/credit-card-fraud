## ML model for Credit Card fraud detection
This project is a part of course work for the Computing and Data Sciences course at ISI Kolkata, PGDBA 2019-21. The project group includes 5 members:
Anudeep (19BM6JP54) | Neha (19BM6JP30) | Srijan (19BM6JP19) | Swadesh (19BM6JP63) | Vaibhav (19BM6JP24)

### INTRODUCTION
Fraud Prevention systems form the core of card transactions happening over the world and in-fact are increasing in volume. Identifying a fraudulent transaction subsequently became equally important. The goal is to predict the probability of a transaction to be fraudulent under a binary target variable. Vesta Corporation provided the dataset which is available in Kaggle.

### DOMAIN INFORMATION
Fraud is a billion-dollar business and it is increasing every year. Identity fraud is a growing concern that affects both businesses and customers.
In this project, we will try to improve the efficacy of fraudulent transaction alerts for millions of people around the world, helping hundreds of thousands of businesses reduce their fraud loss and increase their revenue. And of course, we can save party people from the hassle of false positives.

### DATA DESCRIPTION
The data is broken into two files identity and transaction, which are joined by TransactionID. The train transaction dataset consists of 590,540 elements consisting of 394 variable features, along with train identity dataset also consists of 144,234 data elements and 41 variables. The modelled data is to be tested about 506,691 test transaction dataset and 141,908 test identity data.
The link for the available dataset is as follows: CLICK HERE
The dataset is highly imbalanced in favor of non-fraudulent activities. Only 3.6% of the 590,540 data entries are fraudulent activities.

### LEARNINGS
- We seek to get a hands-on exposure on how to deal with real life datasets
- We seek to learn implementation of feature engineering methods like memory optimization and dimension
reduction techniques, if required, because the data is very huge and sparse.
- Our dataset is highly skewed towards non fraud activities, so we intent to learn ways of dealing with imbalanced
dataset.
- We intend to learn about the various available classification and regression techniques and their enhanced
implementations like lightGBM and XGBoost.
### FINAL GOAL:
1. Importing the data and exploratory data analytics.
2. Feature engineering and Dimension Reduction
3. Dealing with the feature imbalance using resampling or over sampling methods
4. Implementing various classification techniques.
5. Selecting appropriate assessing metric for models because the dataset is highly imbalanced and generally used
techniques like confusion matrix will not serve the purpose.
6. Comparing the models based on the selected metric and trying to improve the accuracy if possible using feature
engineering.
REFERENCES
- IEEE resource on Credit Card Fraud Detection - Machine Learning methods
- IEEE-CIS Fraud Detection on Kaggle
- IEEE paper on “Online transaction fraud detection techniques: A review of data mining approaches”