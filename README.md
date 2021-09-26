# Project Overview
The purpose of this analysis was for a client so they can analyze their stock data set at the click of a button. At first, the client wanted to analyze a single stock in the set, but then decided to expand into multiple stocks over multiple years. 

## Results
The original code ran at the following times for each year:
2017: 0.6484375 Seconds
2018: 0.71875 Seconds


# Challenge Overview
The stock analysis worked very well for a few of the stocks, but if it was expanded for the entire stock market, it might take a while to compute. The purpose of this challenge is to refactor the code so that it will run quicker.

## Challenge Results
The refactored code ran at the following times for each year:
2017: 0.6914063 Seconds
2018: 0.6640625 Seconds

# Summary

This code helped develop a simple volume report for multiple stocks on the stock market over a couple years. When working with the original code, the developers decided to refactor the code to help it run faster. This is great because it updates the codes and typically uses less lines, making the code more easily understandable. During the process of refactoring, however, it is easy to lose your place and if you leave the code in the middle of refactoring, one is likely to forget where the changes were made. This makes refactoring code very tedious and time consuming. 

The original code was easy enough to understand. It also ran quickly for the number of stocks it was analyzing. There is no need to refactor the code if you are using a small amount of stocks for the analysis. The new refactored code runs faster and can easily be scaled to process more data. The way the refactored code is written makes it more versatile and easier to change as well, meaning it is less specific so it makes it easier to use for other applications.


