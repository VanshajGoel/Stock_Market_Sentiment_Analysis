# Stock_Market_Sentiment_Analysis
Steps ued in doing the project- 
- Taken some data (Data.csv) from an online source.
- Data consistes of 25 Top Headlines of news of a particular company
- Data has a labeled variable 0 and 1.
- 0 represent the stock prices may fall for that company and 1 represents stock prices may increase.
- Punctuation symbols have been removed from the text.
- Text has been converted to lowercase.
- Then CountVectorizer if used by taking 2 ngrams for making matrix of bag of words.
- NAive Bayes algorithm is used to train the model.
- Model achieved 84% accuracy on test data.
- Then some news summary is fetched from Yahoo API.
- The text extracted is converted into dataframe.
- Then new dataframe is pre-processed and send to classifier.
- The classifier outputs 1, which means it is good to buy stock of that company.
- By manually reading the news extracted from API, we can analyse that the news is positive and stocs of that company may increase.
- Hence the model's prediction is correct  
