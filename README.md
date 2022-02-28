# NLP Assignment
NLP Assignment Repo 

# General Instructions

- Each group is expected to submit jupyter notebook (.ipynb).
- Inside each jupyter notebook, you are required to mention your name, Group details, and the Assignment dataset you will be working on. Organize your code in separate sections for each task. Add comments to make the code readable. Also, Notebooks without output shall not be considered for evaluation.
- Convert the notebook to HTML format and upload it on Canvas.

# Problem Statement

Prepare a python notebook (recommended- use Google Colab) to classify racist or sexist tweets from other tweets and build a sentiment analysis model on this data. Read the instructions carefully.

## Dataset : 

- Training data https://raw.githubusercontent.com/prateekjoshi565/twitter_sentiment_analysis/master/train_E6oV3lV.csv (Links to an external site.)
- Test Data https://raw.githubusercontent.com/prateekjoshi565/twitter_sentiment_analysis/master/test_tweets_anuFYb8.csv (Links to an external site.)

## Operations

- Download the data set and convert it in the required csv file for the computation. Perform pre-processing steps by Removing Twitter Handles (@user), Removing Punctuations, Numbers, and Special Characters, Removing Short Words in dataset.  
- Tokenize and Pos tag the words. Generate word clouds of the text. 
- Plot two different word clouds “Words in non racist/sexist tweets” and “Words in racist/sexist tweets” and understand the impact of Hashtags on tweets 
- Extract Features from Cleaned Tweets like Bag-of-Words Features, TF-IDF Features, Word Embeddings 
- Build the classification model using Bag-of-Words, TF-IDF, word2vec vectors, and doc2vec vectors 