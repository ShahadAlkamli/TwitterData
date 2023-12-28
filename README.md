# ChatGPT Twitter Data

This repository contains processed Twitter data related to ChatGPT. The data has undergone an enhanced preprocessing pipeline to improve its quality and relevance. The preprocessing techniques include:

1. **Lower-case Conversion**: All text content in the CSV file has been converted to lowercase for case-insensitive matching.

2. **Links Removal**: Hyperlinks present in the tweets have been removed using regular expressions.

3. **Mentions Removal**: Any mentions in the tweets, identified with the '@' symbol, have been removed.

4. **Tokenization**: The text has been tokenized into individual words using the NLTK library.

5. **Stopwords Removal**: Common English stop words that don't carry significant meaning have been removed from the tokenized text.

6. **Additional Privacy Filtering**: The tweets have been further filtered based on relevant privacy and security-related keywords. These keywords include terms such as 'security', 'privacy', 'cybersecurity', 'confidentiality', 'secure', 'hack', 'hacker', 'encryption', and 'theft'.

The processed data is available in the CSV file:[preprocessed_tweets.csv](preprocessed_tweets.csv). It contains a refined subset of tweets that focus on privacy and security discussions related to ChatGPT.

## Data Overview

The structure of the dataset includes 'original_tweet' and 'processed_tweet' columns, providing both the raw and preprocessed versions of the tweets.


| original_tweet | processed_tweet |
| -------------- | --------------- |
| Tweet 1        | Processed Text 1|
| Tweet 2        | Processed Text 2|
| ...            | ...             |


Feel free to explore this updated dataset for more nuanced insights into ChatGPT discussions, with a focus on privacy-related aspects.
