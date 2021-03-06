# us-election-tweets

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/theDrake1010/us-election-tweets/main)
<a href="https://github.com/theDrake1010"><img src="https://img.shields.io/badge/Made%20by-theDrake1010-orange.svg"/></a>
<a href="https://github.com/vaibhavjswl"><img src="https://img.shields.io/badge/Made%20By-Vaibhav%20Jaiswal-red.svg"/></a>
<a href="https://github.com/Raiden1331"><img src="https://img.shields.io/badge/Made%20By-Adith%20Sanjeeve-blue.svg"/></a>

The US Presidential Elections for 2020 just got over and people have a lottt to say! 

In this repo, we look at the tweets made by people regarding the election. The dataset used is:
[US Election 2020 Tweets](https://www.kaggle.com/manchunhui/us-election-2020-tweets)


The dataset comprises of 1.72 Million Tweets regarding the US Elections. It is collected from October 15, 2020 till November 8, 2020 (as of version 19, the most recent version at the time of this update).
The data is distributed into two CSV files:
1. hashtag_donaldtrump.csv
2. hashtag_joebiden.csv

Tweets were scraped using the snsscrape and Twitter API on #DonaldTrump, #Trump, #JoeBiden, #Biden keywords.

The data folder will be empty but should contain just the two CSVs for the notebooks to work.

We performed the following on the dataset:
    1. Exploratory data analysis
    2. Sentiment analysis of tweet and Classying each state as Democratic or republic on basis of tweets
    3. Using K means to Create word cluster and word cloud , optimizing K means using Elbow method

All notebooks are available in the ./notebooks folder.
