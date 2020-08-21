# TWITTER-SENTIMENT-ANALYSIS
This project addresses classification of sentiments in tweets as positive, negative or neutral. Tweets are short status updates of up to 140 characters, posted on microblogging platform twitter.com. Sentiments generated can be used to identify public opinion on any topic, products, policies, individuals or companies. Policies or services can be improved accordingly increasing the value offered to masses.  At a high level, the approach uses Naïve Bayes theorem to classify the sentiments. 
Problem that We solved - Classify a set of tweets present in the test dataset into three sentiments - Positive, Neutral or Negative.
Skills and approaches that we acquired - 
First cleaned the train dataset by removing URLs, emojis, punctuations. Then Pre-Processed it by tokenization, removing stop words and using Spacy lemmatizer (determines the POS tag also).
Training the train dataset into five different ways - First is Bag of Words (BoW) and Sklearn Naive Bayes Approach (using the BernoulliNB model), second is Random Forest approach, third one is XGBoost, 4th one is the NLTK based Naive Bayes approach and the last one is the SVM on TF-IDF Vectorizer. Out of these 5, the last two were used. (The First three we can’t use due to limited hardware resources, were taking too much time, also moderate accuracy results <0.65 (F1-score)  and the last two are simpler to code, easy to interpret the results, training can be done faster and achieved better accuracy results). 
The results can be improved by not removing emojis, having a larger dataset which helps to build generic models.
We classify the texts into three sentiments - Positive, Neutral and Negative. Overall, we achieved a good F1-score of 0.65053.  
Programming Language used - Python
Libraries used - Numpy, Pandas, Matplotlib, Seaborn, Sklearn, spaCy, nltk, XGBoost.
