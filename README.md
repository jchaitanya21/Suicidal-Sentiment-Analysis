# Title: Suicidal Sentiment Analysis on Twitter Tweets

## Description: 

Every year close to 80,00,000 people attempt suicide (According to World Health Organization). Suicide has been one of cause of death around the world. Suicide occurs throughout the lifespan and was second leading cause of death among 15-29 years-old globally in 2016 (According to World Health Organization). In some or other ways, social media is also responsible for the increasing number of suicides. According to survey conducted which is been reported by The Hindu “8 out of 10 people in India have experienced some form of online harassment, with 41% women having experienced sexual harassment”. 
Social media is one of the medium, the people use to share thoughts and feeling regarding any matter occurs in their life. But this post could be an indicator that the one who post it is in serious trouble and require some help. Twitter is worldwide famous platform used by billions of people on daily basis. Many of people before attempting a suicide has posted the tweets before taking their life. Such suicidal-prone people require consultation immediately as soon as such activities has been seen on social media. Machine Learning and Natural Language Processing is field of Artificial Intelligence that can helps us to achieve this feature. Sentiment Analysis is a technique used by organization in order to achieve the thoughts or feedback about people related to services and product they have been using. The information and statistics about the feedback can help organization to find the problem “why-s” and solve the problem. Sentiment can be positive, negative or neutral. Sentiment knowledge can be used to figure out the sentiment of suicidal tweets. It would help to track the sentiment of people associated with suicides and futhur actions can be performed. In this project we have use the concept of Machine Learning and Natural Language Processing to create model that will predict the sentiment of tweet of text as positive or negative with respect to the suicide. 

## Cover Points:

•	The problem is binary classification whether the text data is suicidal or not

•	The dataset comprised 10000 records with a 50:50 ratio of both classes of data (suicidal text and normal text).

•	Positive Tweets acquired through Kaggle Website: https://www.kaggle.com/kazanova/sentiment140

•	Negative Tweets acquired through Github Repositories:  https://github.com/IE-NITK/TwitterSuicidalAnalysis

•	Positive Tweets Labelled as 0

•	Negative Tweet Labelled as 1

•	Balance Dataset created 5000 positive tweets 5000 Negative Tweets

## Procedure:

•	Data is viewed in a dataframe using pandas dataframe.

•	Data Preprocessing: Data processing is important in terms of textual data or unstructured data. Data Preprocessing or Cleaning is the process of removing unnecessary symbols, articles from text to make it easy for machine learning models to make better predictions.

•	The stopwords, digits, non alphanumerics, data fall under noise for Machine Learning estimators

•	Tokenization

•	Stemming

•	Lemmatization

•	Stopwords are removed

•	Tokens are converted into vectors via Tf Idf (Term Frequency Inverse Document Frequency) and Countvectorizer

•	The model is trained on Data after its lemmatized and stop words are removed.

•	4 Machine Learning Estimators/ Models are used 

  a. Logistic Regression 
  
  b. Random Forest Classifier 
  
  c. Support Vector Machine 
  
  d. Naive Bayes

•	Evaluation Metrics used. 

  a. Accuracy 
  
  b. Classification Report
  
  c. Confusion Matrix.

## Tools/Technologies/Algorithms 

•	Front-End: Python Programming Language 

•	Back-End: CSV Files (Comma Separated Values) 

•	Hardware: Not Applicable 

•	Libraries: Pandas, Numpy, Sckit Learn, NLTK, Matplotlib. 

•	Problem Domain: Natural Language Processing 

•	Problem Type: Binary Categorical Classification (Supervised Learning)
