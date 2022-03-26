# Sentiment-Analysis-of-Marathi-Tweets

We have performed a comparitive study of different transformer based architectures, on top of deep learning models like fully connected feed forward neural netword, LSTM and BiLSTM for a downstream task of sentiment analysis on Marathi tweets. The tweets can be classified in three classes, positive, negtive and neutral. Details about dataset and evaluation are given below.

## Dataset statistics
There are 15,864 tweets, that are divided into training set, test set and validation set, and are class balanced. The dataset statistics is shown below:

| Split | Positive | Negative | Neutral | Total |
|-------|----------|----------|---------|-------|
| Train | 4038 | 4038 | 4038 | 12114 |
| Test | 750 | 750 | 750 | 2250 |
| Validation | 500 | 500 | 500 | 1500 |

## Models
We have used Transformer based models for language modelling and feeded the generated embeddings in the deep learning models. The models used are:
- ### Transformer based:
  - mBERT
  - IndicBERT
  - MuRIL (baseline)

- ### Deep Learning models
  - Dense fully connected NN
  - LSTM
  - BiLSTM

- ### Machine Learning models
  - Naive Bayes
  - Linear SVM
  - SVM Radial basis functions kernel
  - Random Forest

