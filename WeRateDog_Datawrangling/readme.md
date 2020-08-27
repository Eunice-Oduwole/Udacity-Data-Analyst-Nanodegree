# WeRateDogs (Wragle and Analyze Data)
## by Eunice Oduwole

## Introduction

In this project, the goal is to use python libraries to gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, clean it and then analyse and produce visualizations. 

## Dataset

The dataset to be wrangle is the tweet archive of the user WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

The archive provided to Udacity by WeRateDogs containsbasic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017 but retweet count and favorite count are two of the notable column omitted.

## Wrangle Process
In other to gather the ommitted data, I will be using Tweepy to query Twitter's API for additional data beyond the data included in the WeRateDogs Twitter archive. This additional data will include retweet count and favorite count.




