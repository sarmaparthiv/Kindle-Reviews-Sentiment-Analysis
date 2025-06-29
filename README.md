# Kindle-Reviews-Sentiment-Analysis
Sentiment classification of Amazon Kindle reviews using Bag of Words &amp; TF-IDF vectorization technique
This project performs binary sentiment classification (positive or negative) on Kindle product reviews from Amazon.
It uses Bag of Words & TFIDF text vectorization techniques

Each feature set is evaluated using:Logistic Regression

Dataset used:[Amazon Kindle Store Reviews](http://jmcauley.ucsd.edu/data/amazon/)

Columns Used:

    reviewText – The actual review

    rating – Original star rating (converted: >=3 = positive, <3 = negative)

    
Techniques Used

    Text Preprocessing:

    Lowercasing

    Tokenization

    Stopword removal

    Lemmatization

🔹 Feature Engineering:

    CountVectorizer (BoW)

    TfidfVectorizer


