<h1 align="center">Machine-Learning - Text-Analysis</h1>

***

<p align="center">Hebrew explenation video</p>
<p align="center">https://www.youtube.com/watch?v=-18xmAskm1Q</p>


## ℹ️ Overview

In this task we have a corpus of stories written in Hebrew
we need to analyse the corpus and fit a machine learning model to predict the gender of the author

## 🌟 Highlights

- Tokenization
- Train Test Split
- Vectorization
- Cross Validation

***Tokenization***

Using Hebrew Tokenization we managed to split each word to a different token

***Train Test Split***

Splitting the train and test set with default values :
- test_size = 0.2
- random_state = 42

***Vectorization***

Using 2 variation of vectorization to find the best vectorizer for our module :
- Count Vectorization
- Tfid Vectorization

***Cross Validation***

with cross validation we could process our full data and apply our machine learning module, each time we process 10% of our corpus
