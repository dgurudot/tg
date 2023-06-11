# **Buy Offset**

## Purpose: 

- This setting allows you to adjust the buy price by fixed offset. Buy offset will be added to selected buy price (Could be Ask, Bid or Mark. Default = Ask).

- Trade will be placed initially at Buy price received in signal. If it doesn't get executed within 5 seconds, then retry attempt will buy at buy price (Could be Ask, Bid or Mark. Default = Ask) plus offset (default is 0.05). 

## Example:

- Buy signal $100 with Bid at $99 and Ask at $101. If initial limit order for Buy doesn't get filled at $100, then retry attempt will happen at $101 + 0.05 = $101.05.
