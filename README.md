# Topic-modelling-with-twitter-data

In this project, we will use the IPython notebook to mine data from Twitter with the Tweepy library. Once we have fetched the raw stream for a specific query, we will at first do some basic word frequency analysis on the results using Python's built in dictionaries, and then we will use the excellent NetworkX library developed at Los Alamos National Laboratory to look at the results as a network and understand some of its properties.

Using NetworkX, we aim to answer the following questions: for a given user, which words tend to appear together in tweets, and global pattern of relationships between these words emerges from the entire set of results?

Obviously, the analysis of text corpora of this kind is a complex topic at the intersection of natural language processing, graph theory and statistics, and here we do not pretend to provide an exhaustive coverage of it. Rather, we want to show you how with a small amount of easy to write code, it is possible to do a few non-trivial things based on real-time data from the Twitter stream. 
