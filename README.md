# Dissertation-Repo

#   ABOUT PROJECT   #
 The dynamicity of the stock market makes it very much challenging to predict. If available, an accurate price prediction 
 can be a complete game-changer for investors. Although there have been many methods to make predictions, the combination 
 of time series and machine learning applications has made an extraordinary impact by giving out the most accurate outcomes. 
 As the closing price of a stock reflects all the intraday events of a stock, it is subjected to be predicted in this research 
 work. Stock price historical data is used to experiment with different machine learning models like Random Forest, K-nearest 
 neighbour (KNN), Decision Tree etc., executing on different time intervals to predict the current day’s closing 
 price (if the market is not closed already). The extracted features: Open, Close, High, Low prices and the volume of the stock 
 along with other important features are taken into account to check the redundancy and correlation between them and the stock 
 price. Stock markets are driven by volatile factors such as microblogs, social media and news that makes it hard to predict 
 stock market index based on merely the historical data. Information extracted from Twitter can be utilized for sentiment analysis
 to find the correlation between the tweets’ weight and the stock. Standard strategic indicator - Root Mean Square Error (RMSE) 
 is used to evaluate the model. The model with minimum RMSE values qualifies to be giving the most accurate predictions.

#   PREREQUISITES   # 
 1) Run python install -r requirements.txt to install required libraries
 2) Generate AlphaVantage API using below steps: 
    #a) Go to link: https://www.alphavantage.co/ on browser and click on ‘GET YOUR FREE API KEY TODAY’. 
    #b) Fill the details and click on ‘GET FREE API KEY’. 
    #c) Free API Key will be generated. Use this key in the code in place of 'api_key' variable.

 3) Generate Twitter API using below steps: 
    #a) Go to link: https://developer.twitter.com/apps on browser. 
    #b) Click on ‘Create an app’. 
    #c) Fill the details and create the app. 
    #d) Once the app is rceated, go to tab: ‘keys and access token’, and copy the required keys to use in the below code.

#   TECHNICAL LIMITATIONS   #
 1) The AlphaVantage API can only be called 5 times a minute and 500 API calls each day. 
 2) The twitter API – TWEEPY’s API.SEARCH can scrape only 18,000 tweets per a 15 minute window from past 7-days only.

#   CODE EXECUTION ADVISE   #
 1) Due to the technical limitations, it is advisable to execute the code only once in a minute.
 2) Execute the code using Jupyter Notebook to avoid graph popups.
 3) AlphaVantage API sometimes through some standard runtime error, which cannot be eliminated.please re-execute the code in such case.

#   CODE REFERENCES #
 Below mentioned links motivated and helped in building this model.
####https://techrando.com/2020/01/04/time-series-forecasting-using-a-seasonal-arima-model/
####https://techrando.com/2020/01/12/pulling-financial-time-series-data-into-python-some-free-options/
####https://github.com/Derrick-Sherrill/DerrickSherrill.com/blob/master/stocks.py
####https://stackoverflow.com/questions/47735793/using-tkinter-to-create-drop-down-menu
####https://pythonspot.com/tk-dropdown-example/
####https://levelup.gitconnected.com/moving-averages-stocks-and-python-ceec1db504d9
####https://plotly.com/python/candlestick-charts/
####https://www.alphavantage.co/documentation/#intraday-extended
####https://algotrading101.com/learn/alpha-vantage-guide/
####https://pythonrepo.com/repo/RomelTorres-alpha_vantage-python-finance
####https://blog.quantinsti.com/gold-price-prediction-using-machine-learning-python/
####https://www.kite.com/python/answers/how-to-replace-values-in-a-pandas-dataframe-that-satisfy-a-condition-in-python
####https://stackoverflow.com/questions/48417867/access-to-numbers-in-classification-report-sklearn
####https://www.geeksforgeeks.org/twitter-sentiment-analysis-using-python/
####https://developer.twitter.com/en/portal/projects/1413001100173656068/apps/21348712/keys
####https://pypi.org/project/yfinance/
####https://www.kite.com/python/answers/how-to-truncate-a-string-in-python
####https://stackoverflow.com/questions/63107594/how-to-deal-with-multi-level-column-names-downloaded-with-yfinance/63107801#63107801
####https://stackoverflow.com/questions/59693969/historical-intraday-data-of-currencies-through-alpha-vantage-api-python
####https://www.codegrepper.com/code-examples/python/get+yesterday%27s+date+datetime+python
####https://www.datacamp.com/community/tutorials/decision-tree-classification-python
####https://stackoverflow.com/questions/35268817/unique-combinations-of-values-in-selected-columns-in-pandas-data-frame-and-count
####https://stackoverflow.com/questions/52541982/pandas-transpose-one-column
####https://www.datacamp.com/community/tutorials/decision-tree-classification-python
####https://machinelearningmastery.com/machine-learning-in-python-step-by-step/
####https://stackoverflow.com/questions/13411544/delete-a-column-from-a-pandas-dataframe
####https://stackoverflow.com/questions/15891038/change-column-type-in-pandas
####https://stackoverflow.com/questions/41925157/logisticregression-unknown-label-type-continuous-using-sklearn-in-python
####https://www.kite.com/python/answers/how-to-drop-the-index-column-of-a-pandas-dataframe-in-python
####https://pythontic.com/pandas/dataframe-plotting/bar%20chart
####https://www.geeksforgeeks.org/how-to-get-column-names-in-pandas-dataframe/
####https://www.datacamp.com/community/tutorials/random-forests-classifier-python
####https://www.datacamp.com/community/tutorials/essentials-linear-regression-python
####https://www.analyticsvidhya.com/blog/2018/10/predicting-stock-price-machine-learningnd-deep-learning-techniques-python/
####https://stackoverflow.com/questions/20095673/shift-column-in-pandas-dataframe-up-by-one
