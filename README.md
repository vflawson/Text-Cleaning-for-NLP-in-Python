# Text-Cleaning-for-NLP-in-Python
Python-based text cleaning of comments scraped from social media platforms for NLP-based brand sentiment analysis

Gensim pre-processing and re packages 

In order to perform NLP-based models and analysis (such as brand sentiment analysis in this case), the underlying text data needs to be properly 
cleaned to aid model performance and quality.

In particular, text data scraped from social media platforms such as Twitter, Facebook, and Reddit have their own challenges in terms of data cleaning.

This code filters by the English language (as the Gensim NLP model used was for English), removes numbers, punctuation, stopwords, and makes text lowercase.

It also tackles some social media-specific challenges, such as handle removal, emoji removal, truncating longer comments, and removing URLs.
