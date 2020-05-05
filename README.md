# Bitcoin Price Prediction
 forecast of bitcoin prices


Bitcoin is the longest running and most well-known cryptocurrency, first released as open source in 2009 by the anonymous Satoshi Nakamoto. Bitcoin serves as a decentralized medium of digital exchange, with transactions verified and recorded in a public distributed ledger (the blockchain) without the need for a trusted record keeping authority or central intermediary. The dataset includes historical bitcoin market data at 1-min intervals for select bitcoin exchanges where trading takes place.


Variable Names:
1.	Timestamp: Start time of time window (60s window), in Unix time
2.	Open: Open price at start time window
3.	High: High price within time window
4.	Low: Low price within time window
5.	Close: Close price at end of time window
6.	Volume_(BTC): Amount of BTC transacted in time window
7.	Volume_(Currency): Amount of Currency transacted in time window
8.	Weighted_Price: volume-weighted average price (VWAP)
We would be using time series forecasting methods to predict the price of Bitcoin for future dates.
