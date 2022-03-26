# Fintech-NLP

Welcome to an Natural Language Processing of Bitcoin and Ethereum articles on the internet using ![spacy](https://spacy.io/usage/visualizers), coded in Python, jupyternotebook.

Below you will find an overview of the analysis and henceforth the summary.

Here is the jupyter notebook kerenl for a deep dive into the code:

![Code_Kernel](Code/crypto_sentiment.ipynb)  

## Overview

### 1. Creating Dataframes

First we read in the csv files and turn them into dataframes to analyse the data.

![Bitcoin Dataframe](Images/1_bitcoin_ethereum_dataframes.png)

### 2. Sentiment Analysis

Secondly, we analyse the sentiment of the articles. This reveals the occurence of positive or negative emotion charged in words. This helps us identify the general theme of an article.

![Bitcoin Sentiment Analysis](Images/2_bitcoin_ethereum_sentimentanalysis.png) 
![Ethereum Sentiment Analysis](Images/2_ethereum_sentimentanalysis.png)

### 3. Tokenizing Text and NGRAM

Turn the text into tokens to later use it to create a word cloud.

![Bitcoin Tokens](Images/3_bitcoin_ethereum_NLP_tokenize.png)
![Bitcoin Tokens](Images/3_ethereum_NLP_tokenize.png)  

NGRAM Calculation on the token text.

![Bitcoin NGRAM](Images/4_bitcoin_ethereum_ngram_analysis.png)
![Etherem NGRAM](Images/4_ethereum_ngram_analysis.png)

### 4. Wordcloud it up

Generate a wordcloud using the token text data.


#### Bitcoin Wordcloud
![Bitcoin Wordcloud](Images/4_bitcoin_wordcloud.png)  

#### Etherem Wordcloud
![Ethereum Wordcloud](Images/4_ethereum_wordcloud.png)


### 5. Nnamed-entity Recognition (NER) Analysis

Finally, use the token data to perform a NER analysis.

![Bitcoin NER](Images/5_bitcoin_NER_analysis.png)  

![Ethereum NER](Images/5_ethereum_NER_analysis.png)


## Summary

In conclusion, we can see geopgraphical words come up in the anaylsis such as Russia and Ukraine. With some outside research we can identify the reason behind this, and mainly it is due to the conflict occuring in those countries. This has caused more news reports and articles highlighing this particular geographical regions.

Furthermore, we see primary words such as NFT in the ethereum analysis, which is a main product of the ethereum blockchain.

