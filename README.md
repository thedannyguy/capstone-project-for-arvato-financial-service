# capstone-project-for-arvato-financial-service (Udacity - Data Science Nanodegree)

Note: my blog post can be viewed at https://thedannyguy.medium.com/capstone-project-for-arvato-financial-service-27322a1d2b09

# Description
The project has three major steps: the customer segmentation report, the supervised learning model, and the Kaggle Competition.

1. Customer Segmentation Report
Using unsupervised learning methods to analyze attributes of established customers and the general population in order to create customer segments.

2. Supervised Learning Model
Build a machine learning model that predicts whether or not each individual will respond to the campaign using MAILOUT TRAIN dataset as validation dataset.

3. Kaggle Competition
The best trained model is used to make predictions (probability of individuals being customers of a mailout campaign)  on MAILOUT TEST as part of a Kaggle Competition. 

# Dependencies
This repository is written in Python and the following Python packages are required: NumPy, Pandas, matplotlib.pyplot, pickle, xgboost, sklearn.metrics, xklearn.decomposition, sklearn.processing,
sklearn.cluster, sklearn.model_selecfion, hyperopt, csv, time, timeit

# File descriptions

Arvato Project Workbook (2).ipynb: contains all the codes required in performing the three major steps

website for my blog post.docx: contains the website address of my blog post in medium.com

arvato project report.docx:  a word document files containing description of the iterative steps i took to accomplish the 3 major steps

data cleaning and preprocessing.ipynb: notebook containing the codes for data cleaning and preprocessing

unsupervised learning model.ipynb: notebook containing codes for unsupervised learning model (K-Means) to idenfity core customers of the mail order company

supervised learning model.ipynb: notebook containing codes for supervised learning model to predict whether an individual will respond postively to the mailout campaign.

list of functions.ipynb: list of custom functions used in Arvato Project Workbook.

xgbcl model for mailout train best model with loss 0.235243.pkl : xgbooster model that is trained on MAILOUT TRAIN used to identify most important features

# Outcome
1) I managed to identify potential customers of the mail order company in the AZDIAS dataset. 
2) I managed to train a model that can identify the most important features.
3) I used my best trained model to predict on MAILOUT TEST and my predictions earned me top spot in Kaggle leaderboard with AUC score of 0.88149
