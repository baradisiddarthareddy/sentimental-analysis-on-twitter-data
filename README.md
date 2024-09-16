# sentimental-analysis-on-twitter-data
In this module we are going to analyze Twitter sentiment analysis using machine learning algorithms, the sentiment of tweets provided from the Sentiment140 dataset by developing a machine learning pipeline involving the use of three classifiers (Logistic Regression, Bernoulli Naive Bayes, and SVM) along with using Term Frequency- Inverse Document Frequency (TF-IDF). The performance of these classifiers is then evaluated using accuracy and F1 Scores.
For data preprocessing, we will be using Natural Language Processing’s (NLP) NLTK library.
Twitter Sentiment Analysis: Problem Statement
In this project, we try to implement an NLP Twitter sentiment analysis model that helps to overcome the challenges of sentiment classification of tweets. We will be classifying the tweets into positive or negative sentiments. The necessary details regarding the dataset involving the Twitter sentiment analysis project are:
The dataset provided is the Sentiment140 Dataset which consists of 1,600,000 tweets that have been extracted using the Twitter API. The various columns present in this Twitter data are:
•	target: the polarity of the tweet (positive or negative)
•	ids: Unique id of the tweet
•	date: the date of the tweet
•	flag: It refers to the query. If no such query exists, then it is NO QUERY.
•	user: It refers to the name of the user that tweeted
•	text: It refers to the text of the tweet


#Twitter Sentiment Analysis: Project Pipeline
The various steps involved in the Machine Learning Pipeline are:
•	Import Necessary Dependencies
•	Read and Load the Dataset
•	Exploratory Data Analysis
•	Data Visualization of Target Variables
•	Data Preprocessing
•	Splitting our data into Train and Test sets.
•	Transforming Dataset using TF-IDF Vectorizer
•	Function for Model Evaluation
•	Model Building
•	Model Evaluation
