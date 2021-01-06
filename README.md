# Tweet Sentiment Extraction
This project extracts part of a tweet as the strong signal of its sentiment. The input training data includes 27,481 tweets with its sentiments and selected texts. Sentiments divide into 40% tweets being neutral, 31% being positive and 28% being negative. I removed stop words and special characters to train positive, negative and neutral tweets with Named-entity Recognition separately. I also trained the raw data with bidirectional encoder system, Roberta.

Updates (01/05/2021)
* Investigate top common words, texts with only special characters, and the difference between the length of selected and original texts
* Clean stop words, special characters and punctuations according to investigation results
* Train cleaned and raw data with Named-entity Recognition for each sentiment
* Train Roberta with raw data for different sentiment
