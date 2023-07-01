This data science project explains how to perform **sentimental analysis of customers reviews** for
the **Flipkart Product reviews** dataset from Kaggle.com.

During the model building I have done
#### Data Cleaning
#### Feature Engineering (Removing errors from the data)
    1. Remove Stop Words Remove the stopwords like "a", "the", "I" etc. Remove symbols and special characters.
    2. Remove the special characters from our reviews like '#' ,'&' ,'@' etc.
    3. Tokenize the words. 
    4. We will split the sentences with spaces e.g "I might come" --> "I", "might", "come"
    5. Stemming -Remove the suffixes from the words to get the root form of the word. e.g 'Wording' --> "Word"
#### Perfomerd EDA
    1. Almost 60% of the reviewers have given 5 out of 5 ratings to the products they buy from Flipkart and 80% are Positive reviews
    
![Rating!](https://github.com/rahul77777/Customer_Review_Sentiment_Analysis/blob/main/Rating.PNG)

![Sentiments!](https://github.com/rahul77777/Customer_Review_Sentiment_Analysis/blob/main/Sentiments.PNG)
    2. I have use a word cloud to visualize the most used words in the reviews column

![WordCloud!](https://github.com/rahul77777/Customer_Review_Sentiment_Analysis/blob/main/word%20cloud.PNG)

![WordCloud1!](https://github.com/rahul77777/Customer_Review_Sentiment_Analysis/blob/main/word%20cloud1.PNG)

#### Label Ecoding for target variable

# This project addresses, in terms of technology and tools,
1. Python
2. Numpy and Pandas for data cleaning
3. Matplotlib for data visualization
4. NLTK , TFIDF and Word Cloud for text processing
5. Sklearn for model building
6. Jupyter notebook


# Model Comparision
![ModelComparision!](https://github.com/rahul77777/Customer_Review_Sentiment_Analysis/blob/main/model%20comparision.PNG)


