# TwitterSentimentalAnalysis

Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion or attitude of a speaker.

# Installation:

## Tweepy: tweepy is the python client for the official Twitter API.
Install it using following pip command:

pip install tweepy

## TextBlob: textblob is the python library for processing textual data.
Install it using following pip command:

pip install textblob

Also, we need to install some NLTK corpora using following command:

python -m textblob.download_corpora
(Corpora is nothing but a large and structured set of texts.)

## Authentication

https://apps.twitter.com/
1.Open this link and click the button: ‘Create New App’
2.Fill the application details. You can leave the callback url field empty.
3. Once the app is created, you will be redirected to the app page.
4. Open the ‘Keys and Access Tokens’ tab.
5.Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’.
