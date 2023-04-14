# Sentiment-Analysis-of-Cryptocurrency-Tweets

**Here are the steps for sentiment analysis of cryptocurrency tweets:**

1-**Import and install important libraries:**
Begin by importing the necessary libraries for the project, such as Tweepy, Pandas, NLTK, and Plotly.

2-**EDA on data:**
Explore the data and get a basic understanding of the dataset. Check for missing values, data types, and unique values in the columns.
                                                                                           ![fhddgjfk](https://user-images.githubusercontent.com/121633990/231948107-5e985f29-8718-41c4-8910-d95b2e32d591.PNG)


![fgkjhkfg](https://user-images.githubusercontent.com/121633990/231947385-7a0b6fb3-a344-4acc-a213-157b16fd531a.PNG)

![fhfgjgfjkhk](https://user-images.githubusercontent.com/121633990/231947461-8fcd6714-5386-489b-9ab6-ec270d3afaf3.PNG)


3-**Data wrangling:**
Clean the data by removing unwanted columns, duplicates, and irrelevant data. Convert the data into a suitable format for analysis.

  a-**Tokenizing:** Tokenize the data by breaking it down into individual words or phrases to help the analysis process.

  b-**Removing Stop Words and Lemmatizing:**
      Remove stop words from the data to improve the quality of the analysis. Also, lemmatize the data by reducing words to their base form
      to reduce the number of unique words in the dataset.

4-**Check the sentiment using different models:**

a-**TextBlob:** Use TextBlob to determine the sentiment of each tweet by analyzing its polarity and subjectivity.
![download (1)](https://user-images.githubusercontent.com/121633990/231947517-71acd7ad-ab7d-4abf-a399-eddf82603dde.png)

b-**VADER Sentiment Analysis:**
  Use VADER Sentiment Analysis to identify the sentiment of each tweet by analyzing the positive, negative, and neutral words used in the tweet.
  ![fhfjhghj](https://user-images.githubusercontent.com/121633990/231947601-8466bcce-7fab-4d05-a1a6-2ac96c41d438.PNG)
   ![hgjgkjgl](https://user-images.githubusercontent.com/121633990/231947691-32fa545b-d9cd-487e-891a-56810c3e2cc7.PNG)
  ![download (2)](https://user-images.githubusercontent.com/121633990/231947727-bd90f534-7fe3-4ffd-908a-3897c7ee083b.png)

c-**Transfer Larning with Distilled BERT and RoBERTa:**
  Use pre-trained language models like Distilled BERT and RoBERTa to classify the tweets into positive, negative, and neutral sentiment.

5-**Evaluating the models:** Compare the performance of the different models by calculating their accuracy, precision, recall, and F1-score. 
  Choose the best model based on the evaluation metrics.
  
  ![fghfgjhgj](https://user-images.githubusercontent.com/121633990/231947879-8b5ea868-8fae-4242-90e2-cc6b1dc1df9f.PNG)
  
  ![gdfghdfhs](https://user-images.githubusercontent.com/121633990/231947956-29bf23ca-f81b-4a9e-a47e-a13949168cf7.PNG)


**Overall, the sentiment analysis of cryptocurrency tweets involves cleaning and processing the data, using different models to
determine the sentiment, and evaluating the performance of these models to select the best one for the task.**
