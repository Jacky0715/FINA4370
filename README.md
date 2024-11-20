# FINA4370

This strategy is based on Black Scholes Model. 

We found that the Implied Volatility of some stocks will rise sharply before earnings reports release. 
We conducted some time series model and found that there are some seasonality based on the quarter earnings reports
To expliot this IV surges, We have 2 strategies, one is long calendar spread, one is short calendar spread.

For the long calendar spread, we open a long calendar position 20 trading days before earnings date, and close the position 1 tradings days before the earnings date. 
For the short calendar spread, we open a close calendar position 1 trading day before earnings date, then close the position close after 10 tradings days.

