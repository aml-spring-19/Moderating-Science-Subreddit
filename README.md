# Moderating the science subreddit /r/science

Authors: *Arnaud Stiegler*, *Redouane Dziri*

The dataset is a csv of about 30k reddit comments made in /r/science between Jan 2017 and June 2018. 10k of the comments were removed by moderators; the original text for these comments was recovered using the pushshift.io API. Each comment is a top-level reply to the parent post and has a comment score of 14 or higher. 

(find the data here: https://www.kaggle.com/areeves87/rscience-popular-comment-removal)

This project aims at accurately classifying removed comments, leveraging some NLP tools (using `scikit-learn` and `gensim`) , with the following questions in mind:

Can we help reduce moderator burnout by automating comment removal? What features are most predictive of popular comments getting removed?
