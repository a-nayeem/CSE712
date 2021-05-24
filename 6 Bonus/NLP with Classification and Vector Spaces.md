# Natural Language Processing with Classification and Vector Spaces



Week 1

- Review of Supervised Machine Learning

- Sentiment analysis using supervised ML

- Use logistic regression as classifier

- Capable of processing sentiment of arbitrary tweets.



How to represent a text as a vector? 

basic way to do so is to build a vocabulary which will allow us to encode any text or tweet as an array of numbers. Vocabulary V = List of unique words from list of tweets.

Now the tweet vector will be of same dimension of vocabulary vector V, the word which appears in the tweet will have 1 as it's value with respect to their position in the vocabulary vector. 0 in all the words that doesn't appear in the tweet.

This is called sparse representation


