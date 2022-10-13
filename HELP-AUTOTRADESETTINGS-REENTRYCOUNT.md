# **ReEntry Count**

## Purpose: 

- This setting allows you to adjust the number of times we would retry limit order with offset before finally placing market order.

## Example:

- If your retry count is 1, then signal will first try to fill the order at price received in signal. 
- If it doesn't get filled, then there will be only 1 retry (based on retry count setting and can be changed) and it will use the Ask plus offset for Buy or Bid minus offset for Sell signal. 
- Once the retry attempts are exhausted, then market order will be placed.
