Big Data CS649 Project

Analysis of historical Trend, Price Prediction and predicting influence of tweets over various cryptocurrencies

Members:
1. Kavya Onkarappa Sunanda Lnu (RedID: 825893660)
2. Sachin Kumar (RedID: 823431551)

Abstract:
	Cryptocurrecy being one of the trending topic nowadays, we wanted to see the history of different crypto coins. Build a ML model to predict a Crypto currency price and 
also to see how social media like twitter had it's impact on cryptocurrency price.



Objective :
	1. Analysing the trend of crypto currency for the last few years. Plotting different garphs to see how volume, price etc of different crypto coins changed over time.
	2. Cryptocurrency price Prediction using Deep learning. (ML model used - LSTM, Keras and tensorflow.)
	3. Analysis of social media on the crypto prize. Sentiments using few keywords in the tweets and relate with the currency price. Positive, negative or neutral emotions.
	4. Our main focus would be on Twitter and Bitcoin.


Datasets :

	1. Cryptocurrency dataset: https://www.kaggle.com/kaushiksuresh147/top-10-cryptocurrencies-historical-dataset
		a. Contains nearly 11 Cryptocurrency coin information
		b. Start date is different for different coins but end date is 25 April, 2021. Most of the coins have atleast 5 year data.


	2. Tweets dataset : https://www.kaggle.com/alaix14/bitcoin-tweets-20160101-to-20190329
		a. Contains all the bitcoin tweets
		b. date range is from 2016-Jan-01 to 2019-March-29


Special Library/Packages installed :
	TextBlob
		pip install -U textblob
		https://textblob.readthedocs.io/en/dev/install.html
	Language detector and translator
		pip install google_trans_new
		https://github.com/lushan88a/google_trans_new
	Keras and tensorflow were used to develop LSTM model
		pip install keras
		pip install tensorflow

Chalenges :
	Not able to install few packages on windows like whatthelang
	Language Prediction https://github.com/indix/whatthelang
	pip install -r requirements.txt
	pip install whatthelang
	Google translator stopped translating the tweets after certain time with below error.
	Error - "Our systems have detected unusual traffic from your computer network"

What we learnt:
	1. First and foremost thing, both us didn't have any idea about cryptocurrency. We got learn about those through this project.
	2. Could explore and learn to plot different type of impressive graphs.
	3. Learnt how to train and test accuracy of a Machine learning model
	4. Learnt how to handle large datasets.
	5. Various methods and properties in Pandas.
	6. Sentiment analysis through text and many more.