# Coronavirus twitter analysis

Approximately 500 million tweets are sent everyday. Of those tweets, about 1% are geotagged. That is, the user's device includes location information about where the tweets were sent from. The lambda server's /data-fast/twitter\ 2020 folder contains all geotagged tweets that were sent in 2020. In total, there are about 1.1 billion tweets in this dataset. 

## Background

These tweets are stored in zip files with a each single tweet per line in JSON format. We will use map reduce to analyze these tweets using following skills:
1. Work with Large Dataset
2. Work with multilingual text
3. Use the map-reduce divide-and-conquer paradigm to create parallel code

Within each /viz folder there is a count of tweets from the hashtags stored in the map.py file. 

I throughly enjoyed working with large volume of data and using this strategy to analyze these tweets and get insight into COVID-19 at scale. 

