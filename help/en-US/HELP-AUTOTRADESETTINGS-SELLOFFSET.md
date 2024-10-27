# **Sell Offset**

## Purpose: 

- This setting allows you to adjust the sell price by fixed offset. 
- Sell offset will be subtracted from selected sell price (Could be Ask, Bid or Mark. Default = Bid).

- Trade will be placed initially at Sell price received in signal. 
- If it doesn't get executed within 5 seconds, then retry attempt will sell at sell price (Could be Ask, Bid or Mark. Default = Bid) minus offset (default is 0.05). 

## Example:

- Sell signal $200 with Bid at $199 and Ask at $201. 
- If initial limit order for Sell doesn't get filled at $200, then retry attempt will happen at $199 - 0.05 = $198.95
