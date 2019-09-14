# Guess-who-tweeted-this-Hillary-or-Trump
This program mines the tweets from twitter using the twitter api.
Once the connection is authorised, tweets are fetched from twitter and converted into data frames.
The tweets are then tokenized and transformed using tfidf vectorizer.
Using logistic regression, the data is fitted.
After that, this model is tested on some other tweets and with the highest accuracy achieved being 95%
