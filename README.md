# Sentiment-Analysis-of-Twitter-Data
- This project is to analyze the negative, positive and neural sentiment in twitter.
- For this project you need to apply for [tweeter developer](https://developer.twitter.com/en/apply-for-access)

- In the code 4 function had been built.
  - Clean_tweet = the tweet will be undergoes pre-processing by clean symbol and split the text into proper word
  - Get_tweet_sentiment = get tweet sentiment positive, negative and neutral
  - The sentiment is detected based on the polarity of the word.
  - Get_tweets = using api.search in the tweepy 
  - This api only give 7 days of latest tweet the count of tweet extract can be set but not the date
  - Get_tweets_time = using api.search_full_archive sandbox that needs to upgrade subscription for more tweets.
    - https://developer.twitter.com/en/account/subscriptions 
    - https://developer.twitter.com/en/account/subscriptions/search-fullarchive here you can see the limited of tweeter tweet extraction

