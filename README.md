# Guided-Capstone
Capstone project for SpringBoard DataScience career track

As we know the stock market attracts alot of people and intrigues the greatest minds to make it big. 
In this project I have tried to replicate how professional financial analysts approach valuation of companies through fundamental analysis. Fundamental analysis (FA) is a method of measuring a security's intrinsic value by examining related economic and financial factors. Fundamental analysts study anything that can affect the security's value, from macroeconomic factors such as the state of the economy and industry conditions to microeconomic factors like the effectiveness of the company's management.

The end goal is to arrive at a number that an investor can compare with a security's current price in order to see whether the security is undervalued or overvalued, according to investopedia.

This projects goal is to beat the average market passive income of 7% and later go beyond that while minimizing the risk.
My approach is to first automate the information gathering process which is very time consuming and includes at least 500 companies(with S&P500 as the bench mark). Then we clean our data and get clean financial values and put them in our model. 
The next step is running the data into our trained model to predict the next Quarterly and Yearly result.

Another algorithm then uses NLP to go through the company's MD&A and check for positive and negative signs and adds weights accordingly to our model's prediction(s).

Basically this Model tells me what to buy on a scale of 0 to 10, 10 being a strong buy and 0 being a strong sell.

* I also plan to mix this with my Technical analysis software signals which tells me when to buy the strong sell from this model.

