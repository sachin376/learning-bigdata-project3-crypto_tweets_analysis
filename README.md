## Big Data Project

Analysis of cryptocurrencies historical trend, Price Prediction and analysis the influence of tweets over various cryptocurrencies

## Abstract / Brief Description:
	Cryptocurrecy being one of the trending topic nowadays, we wanted to see the history of different crypto coins. Build a ML model to predict a Crypto currency price and also to see how social media like twitter had it's impact on cryptocurrency price.


## Goals/Objective :
	1. Analysing the trend of crypto currency for the last few years. Plotting different garphs to see how volume, price etc of different crypto coins changed over time.
	2. Cryptocurrency price Prediction using Deep learning. (ML model used - LSTM, Keras and tensorflow.)
	3. Analysis of social media on the crypto price. Sentiments using keywords in the tweets and relate that with the currency price. Sentiments - Positive, negative or neutral emotions.
	4. Seeing the project scope and timelines, our main focus is on Twitter and Bitcoin.


## Datasets :
	1. Cryptocurrency dataset: https://www.kaggle.com/kaushiksuresh147/top-10-cryptocurrencies-historical-dataset
		a. Contains nearly 11 Cryptocurrency coin information
		b. Start date is different for different coins but end date is 25 April, 2021. Most of the coins have atleast 5 year data.

	2. Tweets dataset : https://www.kaggle.com/alaix14/bitcoin-tweets-20160101-to-20190329
		a. Contains all the bitcoin tweets
		b. Date range is from 2016-Jan-01 to 2019-March-29

## Special instructions to run the project :
    1. There are two notebooks of our project. Please run in order.
        - 'Part1_Cryptocurrencies.ipynb'
        - 'Part2_Cryptocurrencies_tweet_sentiments.ipynb'

    2. Special Library/Packages installed :
        TextBlob
            pip install -U textblob
            https://textblob.readthedocs.io/en/dev/install.html
        Language detector and translator
            pip install google_trans_new
            https://github.com/lushan88a/google_trans_new
        Keras and tensorflow is used to develop LSTM model
            pip install keras
            pip install tensorflow
        Plotly package - to plot 3D graph, pie chart
            pip install plotly
        Download english stopwords used in tweet analysis, this might take little time
            import nltk
            from nltk.corpus import stopwords
            nltk.download('stopwords')
        
    3. Configurations :
            Configurations parameters are given on the top of the notebooks with description. 


## Challenges / Know issues with the project :
	1. Not able to install few packages on windows to translate the tweets to English language like whatthelang. 
        Language Prediction - https://github.com/indix/whatthelang
    2. Original Google translator package was giving error so have to installed a new package - https://github.com/lushan88a/google_trans_new
	3. Google translator stopped translating the tweets after certain time with below error.
	    Error - "Our systems have detected unusual traffic from your computer network"

## What we learnt:
	1. First and foremost thing, both us didn't have any idea about cryptocurrency. We got learn about those through this project.
	2. Could explore and learn to plot different type of impressive graphs.
	3. Learnt how to train and test accuracy of a Machine learning model.
	4. Learnt how to handle large datasets.
	5. Various methods and properties in Pandas.
	6. Sentiment analysis through text.
    7. Troubleshooting and finding the bottlenecks in the program.
    8. Learning refactoring code and have better performance.


## Conclusion:
    1. We got better analysis of various cryptocurrencies.
    2. According to model prediction, looks like model is near to accurate.
    3. Sentiment analysis done successfully


## Futrue scope :
    1. We can extend this work to explore stock prices.
    2. We can also extend the impact of social media other than twitter
    3. Improve ML model to avoid overfiting.
    4. We can try other ML models.