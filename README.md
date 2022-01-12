# Breakout-Strategy

In this project, we'll be implementing a breakout strategy. 

And we will be using Apple Stock as the example. 

Alpha Research Process: 
Observe & Research -----> Form Hypothesis -----> Validate Hypothesis -----> Code Expression -----> Evaluate In-sample -----> Evaluate Out-of-sample 


In this Project, we will be doing the first three part of the Alpha Research Process. 

## Compute High & Low in a Window 
We usually use price high and low as some kind of indicator in a breakout strategy. 

## Compute Long and Short Signals 
We will use the price high low to generate short and long signal in our portfolio

## Filter Signals 
However, we want to do some filtering, if we have short a stock, we don't want its position keep showing as shorting. Vice Versa 

## Lookahead Close Prices 
After we have filtered out trading signals, we need to determine how many days to short and long a stock, we can use look ahead closing price to help 
determine the short and long time. 

## Compute the Signal Return 
We will use the price return to help generate the signal return. 

## Test for significance 
Finally we will be testing the trading signal's normality and determine the performance of the trading signal. 

## Test for Outlier and KS-Test 
If the trading signal is not normal, we need to find the outlier stock that is causing the skewness in expected return, so the actual strategy will 
perform normally in real world. 
