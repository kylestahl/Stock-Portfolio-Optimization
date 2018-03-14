# Stock Portfolio Optimization

This analysis uses the SciPy optimization solver to create the portfolio of stocks which has the least projected variance for a set projected return. This is done using the Markowitz Model or Mean-Variance portfolio theorem. This document will focus on the optimization, but links to learn more specific about the finance and math are within the analysis. 

Two portfolios are created, one assumes you have the ability to short-sell a stock, and the other does not. The portfolios are then compared with the overall market NASDAQ index over 2017 (and a little into 2018). 

**Update**
Added a file with an LSTM neural network to predict stock returns
