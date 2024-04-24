# FinalBiasDetectionInSentiments
## The code is running off Python 3.11
## This project will use all of the following imports 
- import pandas as pd
- import numpy as np 
- import matplotlib.pyplot as plt
- import seaborn as sns
- from wordcloud import WordCloud, STOPWORDS

- import string

- from keras.layers import Embedding
- from keras.models import Sequential
- from keras.layers import LSTM, Dense, Bidirectional, Flatten, Dropout, SimpleRNN, GRU
- from keras.preprocessing.text import Tokenizer
- from keras.preprocessing.sequence import pad_sequences
- from sklearn.model_selection import train_test_split

- from nltk.corpus import stopwords
- from keras.utils import to_categorical


## Running the program
1. This program starts off with all the data pre loaded if you simply want to look at it that way. 
2. If you want to run the program there will need to be 3 data files found within the code. Locations can be found using Ctrl F and looking for pd.readcsv.
3. The three files must be located in the same level directory as the project itself. 
    - the location of the three data sets and their use in order
    - covid-19_vaccine_tweets_with_sentiment.csv = https://www.kaggle.com/datasets/datasciencetool/covid19-vaccine-tweets-with-sentiment-annotation
    - covidvaccine.csv = https://www.kaggle.com/datasets/kaushiksuresh147/covidvaccine-tweets
    - 'vaccination_all_tweets.csv' = https://www.kaggle.com/datasets/gpreda/all-covid19-vaccines-tweets
4. Once done you simply press play and the code will run without issue. 
5. If you want to change the models that had been listed comment out the one that is trained in the beggining and uncomment the others (The others are much worse and were experiments with models.)

## General advice

The code is a mess as it was a lot of plug and play to discover what I wanted. There are general headers in the notebood that use mark down lang. Those are going to be the best bet for making sense of the section that you find yourself. If there are questions please reach out to me at the email listed in my Research paper. 

The code should run in about 5 mins. 

I hope you enjoy!