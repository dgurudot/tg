# **ReEntry Offset**

## Purpose: 

- This setting allows you to adjust the offset from Ask price (at time of Buy) or Bid (at time of Sell). 
- Trade will be placed initially at Buy price received in signal. 
- If it doesn't get executed within 5 seconds, then retry attempt will buy at Ask plus offset (default is 0.05). 
- Similarly, if sell signal is received then trade will be placed at sell price received in signal but if that doesn't get executed then retry attempt will be at Bid minus offset (default is 0.05).

## Example:

- Buy signal $100 with Bid at $99 and Ask at $101. If initial limit order for Buy doesn't get filled at $100, then retry attempt will happen at $101 + 0.05 = $101.05.

- Sell signal $200 with Bid at $199 and Ask at $201. If initial limit order for Sell doesn't get filled at $200, then retry attempt will happen at $199 - 0.05 = $198.95


