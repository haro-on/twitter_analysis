# twitter_analysis

In this project will use the dataset of Twitter user called @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.
The objective of this project is to do a wrangling, analyzing then insight on some visualizing about tweet of @dog_rates user. https://twitter.com/dog_rates?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor  
First, will gather the data from a variety of sources and in a variety of formats: 
-  twitter_archive_enhanced file, WeRateDogs downloaded their Twitter archive and shared it exclusively for use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.
- The tweet image predictions, classify the breed of dog (or other object, animal, etc.) is present in each tweet according to a Convolutional Neural Networks and Image Recognition.
- tweet json file, using Python's Tweepy library to access twitter api to qeury additinal information about user tweet then store each tweet's entire set of JSON file.  
Second, will assess the data of its quality and tidiness, then clean it.  
Last, will do some analysis and visulization on the dataset.

Files discreption:
- wrangle_act.ipynb: Full project code can be found in this Jupyter Notebook.
- wrangle_report.pdf: Report file to describe the wrangling part of the project.
- act_report.pdf: Report file to communicate the findings to a non-techical audience.


This project is part of the Data Analyst Nanodegree Program by Udacity.
