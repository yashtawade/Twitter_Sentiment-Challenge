# Twitter_Sentiment-Challenge

The code in this repo is for the Twitter Sentiment Analysis challenge for the video 'Learn Python for Data Science #2' by @Sirajology (Siraj Raval) on YouTube. Although not an official submission (I was late to discover these awesome challenges), this is my attempt at it. We use the tweepy library to access the Twitter API and extract tweets from Twitter and the TextBlob library to perform Sentiment Analysis on each extracted tweet. Using TextBlob we'll be able to measure the polarity of each tweet depending on the topic we choose.

# Dependencies

* [numpy](http://www.numpy.org/)
* [tweepy](http://www.tweepy.org/)
* [textblob](https://textblob.readthedocs.io/en/dev/)

Install the missing dependencies using pip
~~~~
pip install numpy tweepy textblob
~~~~

# Using the project

After installing the dependencies, run the script in terminal 

~~~~
python Tweet_Sentiment_Analysis.py
~~~~

Before running the script, do change the following query features 
* keywords - List of keywords to be searched in the tweet keywords 
* hashtag - Hashtag related to the topic                            
* since = "yyyy-mm-dd"
* until = "yyyy-mm-dd"

# Credits

The boilerplate code for this challenge was provided by [Siraj Raval] (https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A).

