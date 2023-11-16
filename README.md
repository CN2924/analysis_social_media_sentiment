# analysis_social_media_sentiment #

##Twitter Social Media Sentiment Analysis##

#Project Overview:

*This project performs sentiment analysis on tweets fetched from Twitter to classify them as positive, negative or neutral. 

*Python and various machine learning algorithms are used to build sentiment classification models.

#Installation:

*The code was developed and tested on Python 3.7. The following packages need to be installed:

1.nltk
2.pandas
3.sklearn
4.matplotlib
5.tweepy
6.textblob

#Install the packages using:

          pip install <package-name>

#Data Collection:

*Tweets are fetched from Twitter using the tweepy library which provides easy access to the Twitter API. 

*Query search terms like movie names, product names can be used to filter relevant tweets. Around 50,000 tweets are collected for model training.

#Data Preprocessing:

*The tweets are preprocessed to prepare the text for sentiment analysis. Steps include:

-Convert to lowercase
-Remove URLs, punctuation
-Tokenize into words
-Remove stop words
-Stemming

#Feature Extraction:

*Features like word counts, presence of positive or negative words, hashtags etc are extracted which represent the sentiment of the tweet text.

#Model Building:

*The preprocessed tweet text and extracted features are used to train machine learning models like Logistic Regression, Naive Bayes, SVM for sentiment classification. 

*The models predict if a tweet sentiment is positive, negative or neutral.

#Model Evaluation:

*The models are evaluated on a test set using accuracy, precision, recall and F1-score.The best performing model is selected for prediction.

#Visualizations:

*Interactive visualizations are created using Matplotlib and Plotly to analyze the sentiment trends across timeline, location, keywords etc.

#Deployment:

*The trained models are deployed as Flask web applications and exposed as APIs for real-time sentiment analysis of streaming tweets.

#Resources:

1.EDA Jupyter Notebook
2.Model Training Notebook
3.Flask App Code
4.Plotly Visuals
