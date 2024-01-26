# Twitter-Sentiment-Analysis
The research has been on Natural Language Processing Problem where Sentiment Analysis is done by Classifying the Positive tweets from negative tweets by machine learning models for classification, text analysis, data analysis and data visualization
# Tweets Preprocessing and Cleaning
Preprocessing the text data is a crucial step since it prepares the unprocessed text for mining, which makes it simpler to take information out of the text and use machine learning algorithms on it. There's a greater likelihood that you're working with inconsistent and noisy data if we omit this stage. This stage is to remove extraneous information from tweets that isn't very important to understand the sentiment behind them, such as punctuation, special characters, numerals, and terms that don't have much meaning in relation to the text.
# Visualization from Tweets
i examined the cleaned tweet text in this part. Gaining insights requires analyzing and displaying data, whether it be text or other types of data.  Which includes: 
- Distribution of Sentiment Across Airlines: Compare the distribution of sentiments (positive, neutral,
negative) across different airlines.

![Imgur](https://imgur.com/RWJx93D.png)

- Analysis of Negative Tweet Reasons by Airline: Identify the most common reasons for negative
sentiments towards each airline.

![Imgur](https://imgur.com/TDpmKVk.png)

- Relationship Between Sentiment Confidence and Retweet Count: Examine if tweets with higher
sentiment confidence are more likely to be retweeted.

![Imgur](https://imgur.com/216HbMr.png)


# Sentiments analysis and Modeling
- Pre-process the dataset was carried out 
- Experimentation with diffent machine learning models. The best performed model was fruther selcted for further tunning by experimenting with various data
transformation techniques to improve accuracy. TF-IDF and N-grams was used, It can be seen form the data trasformation techniques that TF-IDF used to tunned the model performed best with data.selecting the best performed Nodel and Progressively refine the model by experimenting with various data transformation techniques to improve accuracy makes TF-IDF to perform best in tunning the Logistic regression model with acuracy value of 0.785519 more than N-grams accuracy of 0.771858 and also more than initial Logistic regression accuracy of 0.782104