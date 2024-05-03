# Twitter-Sentiment-Analysis-using-Python
Twitter-Sentiment-Analysis-using-Python
Twitter is one of those social media platforms where people are free to share their opinions on any topic. Sometimes we see a strong discussion on Twitter about someone’s opinion that sometimes results in a collection of negative tweets. With that in mind, if you want to learn how to do sentiment analysis of Twitter, this article is for you. In this article, I will walk you through the task of Twitter sentiment analysis using Python.

Twitter Sentiment Analysis
Sentiment analysis is a task of natural language processing. All social media platforms should monitor the sentiments of those engaged in a discussion. We mostly see negative opinions on Twitter when the discussion is political. So, each platform should continue to analyze the sentiments to find the type of people who are spreading hate and negativity on their platform.

For the task of Twitter sentiment analysis, I have collected a dataset from Kaggle that contains tweets about a long discussion within a group of users. Here our task is to identify how many tweets are negative and positive so that we can give a conclusion. So, in the section below, I’m going to introduce you to a task of Twitter sentiment analysis using Python.

Twitter Sentiment Analysis using Python
Let’s start the task of Twitter sentiment analysis by importing the necessary Python libraries and the dataset:

The tweet column in the above dataset contains the tweets that we need to use to analyze the feelings of those engaged in the discussion. But to go further, we have to clean up a lot of errors and other special symbols because these tweets contain a lot of language errors. So here is how we can clean up the tweet column:

Now, the next step is to calculate the sentiment scores of these tweets and assign a label to the tweets as positive, negative, or neutral. Here is how you can calculate the sentiment scores of the tweets:

Now I will only select the columns from this data that we need for the rest of the task of Twitter sentiment analysis:

Now let’s have a look at the most frequent label assigned to the tweets according to the sentiment scores:

So the most of the tweets are neutral, which means they are neither positive nor negative. Now let’s have a look at the total of the sentiment scores:

The total of neutral is way higher than negative and positive, but out of all the tweets, the negative tweets are more than the positive tweets, so we can say that most of the opinions are negative.

Summary
So this is how you can perform the task of Twitter sentiment analysis by using the Python programming language. Analyzing sentiments is a task of natural language processing. All the social media platforms need to keep a check on the sentiments of people engaged in a discussion. I hope you liked this article on Twitter sentiment analysis using Python. Feel free to ask your valuable questions in the comments section below.


