# Nlp With Disaster Tweets
Binary Classification Problem

## Information
With today’s technology, each person’s online footprint opens the door for a large treasure trove of information that can be used for many purposes that varies from analyzing market trends to understanding the general emotion of a group of people. Twitter data is especially very useful for a variety of purposes when it comes to the latter use case, mainly because there are more than 6000 new tweets every second. With the advancement of technology and Natural Language Processing methodologies, the process of text and sentiment analysis has become much easier than a few years earlier. If in case, a person tweets a message which was about an emergency or an impending disaster and this was recognized immediately by our NLP models, we would be able to react quicker than normal which would help save lives. This is pretty much the crux of our project. The main aim of our project is to distinguish if a tweet talks about a real disaster or not. This is for a competition hosted by Kaggle and the dataset provided consists of a training set of 10,000 hand classified tweets on which we built our models. For the purpose of identifying if a tweet is pertaining to a disaster or not.

Python libraries that are used in this project are:

Pandas
nltk(Natural Language Toolkit)
re(Regular Expression)
Using nltk (Natural Language Toolkit) library to perform these tasks:

Tokenization (Tokenization is a way of separating a piece of text into smaller units called tokens.)
Removing stopwords (eliminate words that are so commonly used that they carry very little useful information.)
Stemming (Stemming is the process of reducing a word to its word stem that affixes to suffixes and prefixes or to the roots of words known as a lemma)
Converting comment_text column into vectors by using CountVectorizer().

Then train our machine learning model(Multinomial Naive Bayes algorithm).

## Dataset
https://www.kaggle.com/c/nlp-getting-started/data
