# Project 3 - Web APIs & NLP

Brian Cho

### Problem Statement:  

Lyft and Uber are two competitors in the rideshare market. In order to promote their brand, both companies must be able to deliver optimal service to riders and provide a healthy environment for workers as well. In today's market, it is imperative for businesses to be customer centric. Customers who are advocates for brands widely utilize social media to share their opinions and experiences.  

Reddit has been a popular source for consumers and brand owners alike to provide the untarnished truth about a product or service. Reddit inventivizes authors through karma points. Posts that have more upvote points (karma) end up being at the top of the page. This allows Reddit to provide users with the most relevant content.

In order to implement the concept of customer-centricity into practice, I explored reddit posts to create a model that predicts which post falls into a certain Subreddit. This serves as a basis for these companies to evaluate and train this model on twitter data, google reviews, yelp, and other social media platforms where customers voice their opinions on a product or service.

**In this project, I will be creating a model that can predict whether a post originated from the Lyft or Uber subreddit. Success will be evaluated on the classification metrics for each model.**   

**Datasets Used:**

Approximately 7,000 posts were collected from Reddit utilizing pushshift's api: [Pushshift's API](https://github.com/pushshift/api)

**Summary:**  

The analysis is broken down into three notebooks:

1. Data Preparation
2. Data Cleaning and EDA
3. Modeling and Conclusions/Recommendations

**Conclusions and Recommendations:**

In this project, I explored how a company like Lyft can understand the customer voice through Natural Language Processing. A NLP Machine Learning model was created to predict whether text data came from the Lyft or Uber subreddit. I was able to achieve success with a logistic regression model with a TFID Vectorizer that classified posts with 84% accuracy. This was a major improvement of the baseline model which had a 50% accuracy. Although the model was slightly overfit, the model had the highest test R2 score of 0.84.

**Recommendations**  
Lyft can utilize this model to pull text data from other social media platforms in order to evaluate and collect service feedback in realtime. Further analysis of the sentiment polarity scores can be conducted in order to figure out the positive, negative, or neutral sentiments towards the brand. The sentiment analysis scores can also serve as a company wide metric as a basis for measuring customer satisfaction. The model provides leaders to drive better strategic decisions based on feedback from customers.

In order to improve upon the model, a larger pool of data can be collected and fed into the model. The model will learn from the greater set of data and provide more accurate predictions. Furthermore, the data can be cleaned deeply by stemming/lemmatizing each post. By simplifying the text data, the model can learn from a uniform data set and therefore provide better predictions.