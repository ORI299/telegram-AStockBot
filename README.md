
# telegram AStocksBot [![send our bot message](https://img.shields.io/badge/the-bot-brightgreen.svg?style=flat)](https://t.me/AStocksBot)


[ASstocksBot](https://t.me/AStocksBot) is a new telegram bot he created with python and running on azure and has **a lot** of stock commands   
hare is some exemples


## change command  
### the change command will allow **you** to get the price, the range, and even more! about **any** stock
### **every** time that the stock price will go up by a price that you have choosed!


```python
                                                 date 15/07/2021





"""                
11:23 [you]: /change bigc 5

11:23 [AStocksBot]: i will notified you when bigc's stock price will change by 5$

15:37 [AStocksBot]: bigc's price has changed! hare is the price: 
  price now: 62.01
  change 2.82$ (%4.56+)
  range ...

15:38 [you]: /stop

15:38 [AStocksBot]: i will stop notified you when bigc's stock price will change by 5$
"""
```
```
/change <Symbol> <Price>
```


**by default price is 0.1**



## get command
### easy command to get the price,range,change and even more!

 
```python
                                                 date 16/07/2021





"""                
18:23 [you]: /get BIGS

18:23 [AStocksBot]: this is not a vaid symbol!

18:24 [you]: /get BIGC

18:24 [AStocksBot]: hare is bigc's price: 
  price now: 54.09
  change 8.72$ (%16.12-)
  range ...



18:25 [you]: /get bigc

18:25 [AStocksBot]: hare is bigc's price: 
  price now: 54.09
  change 8.72$ (%16.12-)
  range ...

"""
```
```
/get <Symbol>
```


## market_status command
### this command will tell you the market status of this 
```python
                                                 date 17/07/2021








"""                
11:23 [you]: /market_status

11:23 [AStocksBot]: normal


"""
```


```
/market_status
```

