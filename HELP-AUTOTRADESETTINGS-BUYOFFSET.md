# Buy Offset

## Purpose: 

### This setting allows you to adjust the buy price by fixed offset. Buy offset will be added to selected buy price (Bid or Ask or Mark).


Trade will be placed initally at Buy price received in signal. 
If it doesn't get executed within 5 seconds, then retry attempt will buy at buy price (could be Ask, Bid or Mark depending on setting) plus offset (default is 0.05). 
Similarly, if sell signal is received then trade will be placed at sell price (could be Ask, Bid or Mark depending on setting) received in signal.

Example:
Buy signal $100 with Bid at $99 and Ask at $101. If initial limit order for Buy doesn't get filled at $100, then retry attempt will happen at $101 + 0.05 = $101.05.
Sell signal $200 with Bid at $199 and Ask at $201. If initial limit order for Sell doesn't get filled at $200, then retry attempt will happen at $199 - 0.05 = $198.95
