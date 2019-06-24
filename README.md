# Sentiment-RNN

In this repository I have sample code that conducts sentiment analysis using a Recurrent Neural Network (RNN).

I have a bunch of fake movie reviews, which you can get from here [reviews.txt](https://github.com/the-john/Sentiment-RNN/blob/master/data/reviews.txt).  I also have labels for those reviews that you can get from here [labels.txt](https://github.com/the-john/Sentiment-RNN/blob/master/data/labels.txt).

In the Jupyter Notebook [Sentiment_RNN_Solution.ipynb](https://github.com/the-john/Sentiment-RNN/blob/master/Sentiment_RNN_Solution.ipynb) you can find sample code that does the following:
- load the data
- visualize the loaded data
- pre-process the data
- encoding the data into tokens
- encoding the labels
- removal of data outliers
- padding sequences
- Data loaders and batching
- the addition of an embedding layer in the model
- the creation of Long-Short Term Memory (LSTM) layer in the model
- the creation of a Fully Connected (FC) layer in the model
- finally the creation of a Sigmoid Activation layer in the model
- setting up hyperparameters
- training the model
- validating the model
- testing the model

The final model be able to take in a text movie review and determine if the review was positive or negative.
