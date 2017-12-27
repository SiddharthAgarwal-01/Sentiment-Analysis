# Sentiment-Analysis

Twitter Sentiment Analysis with Machine Learning in Python.

Libraries used:
- Numpy
- Pandas
- Matplotlib
- Seaborn
- NLTK
- Sklearn

Dataset contains 99990 different tweets along with the Sentiment associated with them in terms of 0 or 1 indicating Negative and Positive Sentiments repectively.

Data Cleansing is done in order to remove unwanted characters/words present in the tweets.

Data Processing is done by Stemming and Tokenisation of tweets and then creating the Bag of Words using the tokenised words.

Dataset is splitted into Train and Test Datasets in order to apply Classification algorithms and to evaluate the performance of the Models.

Classification Algorithms used here:
- Logistic Regression
- Naive Bayes Classification
- Random Forest Classification

Performance evaluation is done using:
- Confusion Matrix which gives True Positives, True Negatives, False Positives and False Negatives.
- Classification Report which gives Precision, Recall and F1-Score.
