Crypto Price Prediction Model

Cryptocurrency prices are notoriously volatile, driven by market trends, trading patterns, and the pulse of social media. Using machine learning, can we identify patterns from historical price data and public sentiment across Reddit, news headlines, and social platforms to predict the next day's price movement of a coin, and build a model accurate enough to be meaningfully better than random chance?

Price Data:

●	Source: https://www.kaggle.com/datasets/novandraanugrah/bitcoin-historical-datasets-2018-2024


Reddit Sentiment:

●	Source: Reddit public JSON API — https://www.reddit.com/r/Bitcoin/hot.json

●	Subreddits: r/Bitcoin

●	Approximate size: ~25–100 posts per day, aggregated to a daily sentiment score

●	Feature types: Daily average VADER compound score (continuous, -1 to +1), post volume, comment count
