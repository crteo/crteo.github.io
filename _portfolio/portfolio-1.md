---
title: "Twitter Sentiment Analysis using NLP"
excerpt: "My first attempt at playing around with NLP. <br/><img src='/images/12-Fastdatascience-Blog-Natural-Language-Processing'>"
collection: portfolio
---

In this really quick attempt at my first project, I create a regresssion model utilising Natural Language Processing (NLP) to conduct sentiment analysis on a Kaggle Dataset containing tweets. The source of the labelled data is from [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140). 
I utilise Google Colab to create the machine learning model. (Access it [here](https://colab.research.google.com/drive/1qwW-AK9HDfSjlgXsV8tRIwvy7LTWIEmS?usp=sharing)

Libraries used:
Nltk - Natural Language Toolkit (to manipulate the tweet inputs)
Sklearn

Overview of the steps taken:
1. Obtaining a labelled dataset (Kaggle)
2. Data inspection using Pandas to look out for missing data and visually inspect how the data is represented
3. Data preprocessing via NLTK and Sklearn
Utilised nltk.port.stemmer and stopwords from nltk.corpus to trim the input data by reducing words to their root form and removing unnecessary words respectively

Use of tfidfvectorizer from the Sklearn package to transform text tweets to numerical features that can be fed into the ML model chosen
  What is tfidf? (Term Frequency-Inverse Document Frequency)
  TF: measure of importance of a word according to how often it appears in a document
  Idf: measure of how important a word is across a corpus of documents - rarer words across documents are given more weight
  The product of Tf and Idf values provide a numerical output of a word.

Split the data into training and testing datasets.

4. Training the model
Since we're predicting a binary outcome (positive or negative sentiment), I used logistics regression.
I tuned the parameters of the logistic regression by using CVgridsearch.

5. Test the model
The model returns an accuracy score of >75 on the test dataset. (% of correct predictions).

Reflections & further questions for myself.
How could I have appropriately evaluated the model using PR curve/ ROC curve? Which would have been more appropriate
Could I have used other ML models - KNN, Decision Tree, Neural Networks etc?

Next steps:
To reattempt this using different models, and attempt to evaluate each model and consider the practical application of a twitter sentiment analysis - is a PR or ROC curve more appropriate, and are we more interested in the positive or negative class based on the application of such a model?





