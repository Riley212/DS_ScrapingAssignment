# DS_ScrapingAssignment
Introduction to Data Science, Assignment 1
################################################################
## Homework: Scraping Assignment
## February 23rd, 2015
## Readme file: Collecting and Analyzing Twitter data
## Author: Riley Sullivan
################################################################

1. Set my directory
2. Install R packages I will use

#####################################
### CREATING YOUR OWN OAUTH TOKEN 
#####################################

Step 1: go to apps.twitter.com and sign in
Step 2: click on "Create New App"
Step 3: fill name, description, and website (it can be anything, even google.com)
Step 4: Agree to user conditions
Step 5: copy consumer key and consumer secret and paste below
Step 6: run the code to create my own oauth token
Step 7: save oauth token for use in future sessions with twitteR or streamR

#############################################
### DOWNLOADING RECENT TWEETS FROM A USER 
#############################################

1. my list of the 10 media sources is: ABC, AP, CNN, Fox News, MSNBC, New York Times, NPR, USA Today, Wall Street Journal, and Washington Post.
2. capture the most recent tweets of all 10 media sources. I capture 600 per twitter page for a total of 6,000.
3. use the function written by Pablo Barbera to store the JSON data
4. download tweets from 10 media sources
5. it's stored and I can read it with the 'parseTweets' function in the streamR package

###############################################
### SENTIMENT ANALYSIS						
###############################################

1. Load tweets I will use from all media sources
2. load lexicon of positive and negative words (from Neal Caren)
3. run the function to clean the text and clean the text using a function to classify
individual tweets while aggregating over many tweets.
4. apply the classifier function to classify the tweets and get the results of positive,
negative and neutral tweets.
