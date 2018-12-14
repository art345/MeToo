# The #MeToo movement and its propagation on Twitter : a Temporal, Gender Based and Sentimental Analysis

# Abstract

The #MeToo movement is a global movement against sexual abuse. It spread virally in October 2017 as a hashtag used on social media in order to show the widespread phenomenon of sexual harassment, particularly in the workplace. The idea is to fearlessly talk about any sexual abuse one might experience and to rebel against the culture of staying silent after going through such traumatising experiences. A lot of celebrities participated in this movement by highlighting their stories on social media, including renowned actress, personalities, and politics, but also persons from simple backgrounds. As a team we are motivated to understand the movement because of its intensity and controverse. It is a challenge to put aside our personal opinion as individuals and consider only the data around this thematic to arrive to an interesting yet objective datastory. 

# Research Questions

From most factual and clean to more interpreting and subjective data handling: 

- Temporal Analysis: 
{presented in 1-DataExploration.ipynb}
How did it start, how did it spread in time ? Can we clearly identify the origin of the movement ? Are there key moments ? Can we correlate activity peaks with public events (accused star, public affairs, etc.) ? 

- Sentimental Analysis: 
{presented in 2-SentimentalAnalysis.ipynb, results extracted into features_per_tweet.csv}
How did the public opinion react ? Which were the main hot topics discussed ? (sentiment analysis, natural language processing, lexical fields)

- Gender Analysis:
{presented n 3-GenderAnalysis.ipynb, results extracted into genderData.csv}
What was the role of men within this movement ? Can we associate #metoo movement with a gender debate ?

Open-ended data interpretation question: 

- Group effect, cathartic experience, collecting together, showing the example... How did technology and social media give women a voice and a sense of bravery in calling out ? Did it spun out of control ? Is there a danger of witch-hunt effect ? Could a similar movement have happened without social media ?

# Datasets

[metootweets.csv](https://data.world/rdeeds/350k-metoo-tweets), raw CSV database, Ryan Deed.

Which has the following features:
- name of twitter user
- number of followers
- written content of tweet
- creation date

Period : between October 2017 and February 2018.
Number of Tweets: 350 000 tweets. 


# Internal milestones till milestone 3

Achieved for Milestone 2 : 
Temporal data exploration
Sentimental data extraction using LIWC
Gender data extraction using genderperform

1. Sentimental Analysis Exploration 

2. Bivariate Gender-based and Sentimental Analysis 

3. Bivariate Temporal and Sentimental Analysis

4. Bivariate Temporal and Gender-based Analysis

5. Data Story construction and presentation



# TA Questions

What are the best tools for data story creations? If we want to have for example:
- interactive timelines
- interactive graphs  

How to take away warnings when loading our data? 



