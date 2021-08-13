# Fake-News-classification



#Dataset Source:

Link of the dataset: https://www.kaggle.com/c/fake-news/data

# About the Dataset: 

train.csv: A full training dataset with the following attributes:
id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks the article as potentially real or fake
test.csv: A testing training dataset with all the same attributes at train.csv without the label.

# Type of Model
This is a classification model.

# Libraries Used

1: Pandas (https://github.com/pandas-dev/pandas)

2: NumPy (https://github.com/numpy/numpy)

3: ScikitLearn (https://github.com/scikit-learn/scikit-learn)

4: Flask(https://github.com/pallets/flask)

5: MatplotLib (https://github.com/matplotlib/matplotlib)

6: NLTK (https://www.nltk.org/)


# Algorithm Used:

Naive Bayes Classifier
Random Forest Model
Logistic Regression

# About this Repo:
This repo consists of following files:

1: static/css , Template: Used for web app.

2: App.py : Flask based main app to deploy/run.

3: Fake_news_classificatiom.ipynb: Jupyter file for EDA/ Model Building / Model evaluation/ Saving Model.

4: Procfile: For Heroku deployment.

5: Logistic_model.pkl : Model Saved pickle file to be used for prediction.

6: requirements.txt : Requirements to be installed in Heroku(Cloud platform) for deployment.

7: cv-transform.pkl : Pickle file of countvectoriser



# To Run the file:
1: Clone the Model.

2: Run the Jupyter file to get the model pickle file.

3: Run the App.py file and file will run in your local system at "http://127.0.0.1:5000/".

4: Open the browser and go to "http://127.0.0.1:5000/". 

5: Web app will run in your browser .

6: Make the prediction.

# Technologies Used:

Python

HTML

CSS


# GitHub Link:
https://github.com/atulkmr011/Fake-News-classification_Deployment

# Heroku Deployment Link:
If you want to view the deployed model, then go to following link:
https://fakenewsappdata.herokuapp.com/
