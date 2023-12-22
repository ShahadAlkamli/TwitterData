# ChatGPT Twitter Data

This repository contains processed Twitter data related to ChatGPT. The data has undergone the following preprocessing steps:

1. **Lower-case Conversion**: All text content in the CSV file has been converted to lowercase for case-insensitive matching.

2. **Links Removal**: Any hyperlinks present in the tweets have been removed using regular expressions.

3. **Privacy-Related Keywords Extraction**: The tweets have been filtered based on privacy and security-related keywords, such as 'privacy', 'private', 'security', 'secure', 'data protection', 'confidentiality', 'confidential', 'personal data'.

## Data Overview

The processed data is available in the CSV file: [processed-tweets.csv](processed-tweets.csv). It contains 9430 tweets with the following structure:

| content |
| ------- |
| Tweet 1 |
| Tweet 2 |
| ...     |

