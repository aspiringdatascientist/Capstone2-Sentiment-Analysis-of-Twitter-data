# Twitter Sentiment Analysis of Electoral College in U.S. 

Twitter is a treasure trove of sentiments. In this report, we assess the feasibility of using  Python based  supervised machine learning to classify tweets.The goal of this project is to predict Twitter users’ political sentiment towards  electoral college in U.S. for a given Twitter post. Many Americans are critical of the Electoral College, an attitude that seems to have intensified since Donald Trump defeated Hillary Clinton in the 2016 presidential election despite losing the popular vote.

Sentiment Analysis is simply gauging the feelings behind a piece of content.It maps and measures the relationships and flows of information between people, communities and organizations In this work, we will build a machine learning classifier that can detect sentiment  to classify tweets (pieces of text) as positive, negative or neutral  by analyzing the feeling that Twitter users have towards “electoral college”.In this report, we discuss the nuisances met in handling the data , cleaning the data, and extracting features from the data. Finally, using the extracted features, classification algorithms are trained, and their performance  is assessed. Python code used for data preprocessing, analysing, modeling in this [Github link](https://github.com/aspiringdatascientist/Capstone2-Sentiment-Analysis-of-Twitter-data/blob/master/Twitter%20sentiment%20analysis%20-%20final%20report.ipynb).
o create target variable, we have compared several sentiment analyzer tools which are widely available for classifying the data such as VADER, Textblob, SentiWordNet lexicon from NTLK, StanfordCoreNLP, Afinn as provided in this [link](https://github.com/aspiringdatascientist/Capstone2-Sentiment-Analysis-of-Twitter-data/blob/master/label_tweets.ipynb).


__Approach:__

A project flowchart below shows the order of methods involved in the completion of this project.


![Capstone2flowchart](https://user-images.githubusercontent.com/48024013/72182262-1efbb480-33b9-11ea-9a82-65994fbde473.png)

Example snippets:

![mostusedhash](https://user-images.githubusercontent.com/48024013/72188412-41e19500-33c8-11ea-9e21-1c5d2af4dc76.png)

![wc](https://user-images.githubusercontent.com/48024013/72225060-f5749180-354e-11ea-8a5e-438acfba87b0.png)

![stdr](https://user-images.githubusercontent.com/48024013/72225090-5734fb80-354f-11ea-8ca1-c61fbfcf2286.png)

![ee](https://user-images.githubusercontent.com/48024013/72225106-851a4000-354f-11ea-9f47-86b26d3fe5d7.png)

Model Comparison and Selection:

The performance of all models can be compared in the score table below:

![nm](https://user-images.githubusercontent.com/48024013/72225137-d4f90700-354f-11ea-8824-50d1f0d06899.png)









