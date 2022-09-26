Sentiment Analysis for stock markets is done using scraped data from social media provided as part of the Udemy course "Machine Learning for Finance". This is an NLP problem. **Wordcloud** is also visualized after performing pre-processing. "Long" and "Buy" are associated with positive sentiment and also reflected in the word cloud. Similarly "Short" and "Sell" are associated with negative sentiment. Correctly identifying sentiment of a social media statment is crucial to predict future stock market behavior

## KEY TAKEAWAYS

* The text from social media is classified as a positive and negative sentiment. So this is a binary classification problem

* NLTK package is used to perform data preprocessing like "stopwords/punctuation removal", "lemmatization", "tokenization" etc.

* Wordcloud visualization for the corpus of texts is done to highlight the frequently occuring words associated with each sentiment.

* A 1D CNN, LSTM, and combination of both used for final training with the combination model perfoming the best. 


### Positive Wordcloud

![1](./positive.png =100x20)

### Negative Wordcloud

![2](./negative.png =100x20)
