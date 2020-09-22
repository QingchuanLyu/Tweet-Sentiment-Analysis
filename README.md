# Tweet-Sentiment-Analysis
Given a dataset of tweets and their sentiments (positive, negative or neutral), predict what part of each tweet could imply its sentiment. Training data (3.34 MB) was from Kaggle. I attacked this problem by using Roberta CNN. The highest Jaccard Index was 0.714, measured by unseen test data. Potential improvement could be a meta model with RoBERTa, NER and Question-Answering System.

The pretrained TensorFlow RoBERTa base model can be downloaded from Kaggle: https://www.kaggle.com/cdeotte/tf-roberta
