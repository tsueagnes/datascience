Crypto Price Prediction Model

Cryptocurrency prices are notoriously volatile, driven by market trends, trading patterns, and the pulse of social media. Using machine learning, can we identify patterns from historical price data and public sentiment across Reddit, news headlines, and social platforms to predict the next day's price movement of a coin, and build a model accurate enough to be meaningfully better than random chance?

Price Data:
●	Source: Kaggle BITCOIN Historical Datasets 2018-2026 Binance API

●	Feature size: 12

●	Feature types: Numerical and date columns containing information about the price, the volume of trades, the open and closing dates as well as open and closing
trade prices.

●	Open price: We will use this feature to determine if the higher or lower price was impacted by the sentiment of reddit on the previous day

●	Known issues include determining which interval to use along with reddit sentiment analysis. Lining up the dates of the reddit post vs the opening and closing times of bitcoin trading will be difficult to line up as there is no unique value to merge those data points together other than inference and best guess. 

Reddit Sentiment:

●	Source: Reddit public JSON API — https://www.reddit.com/r/Bitcoin/hot.json

●	Subreddits: r/Bitcoin

●	Approximate size: ~25–100 posts per day, aggregated to a daily sentiment score

●	Feature types: Daily average VADER compound score (continuous, -1 to +1), post volume, comment count
