﻿# Text_Summarizer_with_RNN

This is a project for our bigdata ecosystem class. We're developing a Text Summarizer using Recurrent Neural Network and Sequence-to-Sequence model. We'll be using Encoder/Decoder model with attention mechanism. The data set being used is DeepMind's CNN and Dailymail dataset of news stories.

The dataset stories can be downloaded from [here](https://cs.nyu.edu/~kcho/DMQA/). We will be using stories dataset from the both.

Our code is inspired from tensorflow's [textsum](https://github.com/tensorflow/models/tree/master/research/textsum).

The processed dataset has been uploaded to dropbox. Data can also be manually processed by running the make_datafiles.py code which first tokenizes the code using stanford nlp PTBtokenizer and then process them into binaries.

We have also added a skip gram model code which generates a word vector from a book. The book is retrieved from project gutenberg and we have used Keras libraries with tensorflow in the backend. We have worked on this code to get started with the RNN and NLP. We can get word similarities after training this network which has one hidden layer.
Sequence diagram and model diagram are presented in the report.
