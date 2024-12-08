# Twitter-sentiment-analysis
Created a Machine Learning Model that predicts stock price movement based on twitter comments or sentiments of users

**What is Twitter sentiment analysis?**
Twitter sentiment analysis determines whether a tweet is positive, negative, or neutral.
You can do it manually by analyzing each tweet and evaluating whether it is positive or negative. But it is a time-consuming process. 
Some tools can do the job for you. Such software can automatically detect the sentiment by analyzing the words used in the tweet and their context. 

**Methodology**

1.	Data collection: Twitter data is collected using APIs or web scraping techniques, focusing on keywords related to specific companies or stock market indices.

2.	Preprocessing: Tweets are preprocessed to remove noise, stop words, and punctuation, and to convert text to a suitable format for analysis.
	
3.	Sentiment analysis: NLP models are applied to the preprocessed tweets to extract sentiment scores (positive(1), negative(0), or neutral(2)).
	
4.	Feature engineering: Additional features, such as tweet volume, user engagement, and hashtag usage, are extracted and incorporated into the analysis.
		
5.	Model training and evaluation: Machine learning models are trained and evaluated using historical data, and their performance is assessed using metrics such as accuracy, precision, and F1-score.

   
**Conclusion**

Twitter sentiment analysis has shown promise in predicting stock market movements, particularly when combined with machine learning techniques and real-time data processing. However, the complexity of stock market dynamics and the noise inherent in Twitter data require careful consideration of model selection, feature engineering, and evaluation metrics. This README provides a comprehensive overview of the current state of research in this area, highlighting the potential applications and challenges of using Twitter sentiment analysis for stock market prediction.

**IMPROVEMENT SCOPE:**

My training datset has more accuracy than my test dataset ,thus resulting in overfitting,this could be removed by:
1.Using a consistent evaluation metric (e.g., mean squared error, mean absolute error) to monitor model performance.

2.Regularly inspect the model’s coefficients and residuals to identify potential issues.

3.Consider using techniques like gradient boosting or random forests, which are inherently more robust to overfitting.

