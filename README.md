# Forecasting-MercadoLibre-with-Net-Prophet

## Overview

In this project, I look for patterns in hourly Google search traffic of MercadoLibre, mine the search traffic data for seasonality, relate the search traffic to stock price patterns  and create a time series model with Prophet for future insight.  

## Results
### What pattern did I find?
Google search traffic increase during the month that MercadoLibre released its financial results. 
I also found that search trends are highest at hour 0 and 23 for every day of the week.

### Did I find anything when searching traffic data for seasonality?
Search traffic decreased, then increased, then decreased from weeks 40 through 52 (the winter holiday period). It was a net decrease.

### Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?
There is a week negative correlation between lagged search trends and stock volatility. There is an insignificant positive correlation between lagged search traffic and the stock price returns.

### How's the near-term forecast for the popularity of MercadoLibre?
By using prophet to create a time series model, a slight dip in hourly searches is forcasted in the short-term, from around 90 to 85 searches/ hour.

## Summary
I was able all questions without any problems. I also had other questions answered including:

### What time of day exhibits the greatest popularity?
Answer: 00.00.00

### Which day of week gets the most search traffic?
Answer: Tuesday

### What's the lowest point for search traffic in the calendar year?
Answer: October
