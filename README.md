# First_NLP_model
This project implements a Natural Language Processing (NLP) model that classifies messages as spam or ham (not spam). The model is trained using a spam collection dataset and utilizes text preprocessing techniques such as removing special characters, stopwords, and applying lemmatization. The processed text data is then transformed into a Bag of Words (BoW) representation, and a Naive Bayes classifier is used to predict the message category.

Dataset
The dataset used in this project is a collection of labeled SMS messages that are either spam or ham (not spam). Each message is pre-labeled to facilitate supervised learning.

Columns:
label: Indicates whether the message is spam or ham
message: The text content of the SMS message

Requirements
Python 3.x
Libraries:
nltk
scikit-learn
pandas
