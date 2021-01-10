# Tweet Sentiment Extraction
This project extracts support phrases for English tweets' sentimental labels. The training data includes 27,481 tweets with sentiments and selected texts (support phrases). Sentiments divide into 40% tweets being neutral, 31% being positive and 28% being negative.

Updates (01/07/2021)
* Investigate top common words, special characters, and proportional length of selected texts
* Clean part of stop words, special characters and punctuations according to investigation results
* Compare results from Named-entity Recognition trained on cleaned and raw data for each sentiment
* Train a four-layer Neural Network embedded with Roberta for each sentiment
