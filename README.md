# Atlanta-reputation-index-tracker
Read Twitter json file from database every hour

Clean and tokenized the tweets

Using trained model to classify Tweets into relevant and irrelevant

Saving Tweets into dataframe with specific confidence level (>0.99 | <= 0.01) for re-training purpose

Doing Sentiment Analysis on relevant Tweets

Sleep for an hour then re-do the whole process above

Re-train model every Sunday 10am
