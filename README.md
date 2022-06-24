# Stock-market-sentiment-analysis-and-prediction
Abstract: To analyze the stock market system and the impact of public opinion on company’s market value, in this paper, we collected twitter data set and preprocessed it. Then we used Sentiment analysis on the extracted data and we analyzed using Spark and other big data tools that assist in making predictions about the stock movement.

Data Collection: We collected four different data sets related to company, tweets, ticker symbols and daily stock value from Kaggle open source. We gathered this data for four major companies like Apple, Google, Tesla and Amazon. Over a 6-year time period i.e., from 2015 to 2021, more than 3 million tweets data is collected.

Sentiment Analysis: We classified tweets into three types: Positive, Negative and Neutral. We then used Vader sentiment (Valence Aware Dictionary for Sentiment Reasoning is a text sentiment analysis model that is sensitive to both emotion polarities positive and negative and intensity of emotion) to determine sentiment of each post. We removed neutral tweets, as they do not have any effect on the stock price.
