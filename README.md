
# Telegram AStocksBot [![send our bot message](https://img.shields.io/badge/the-bot-brightgreen.svg?style=flat)](https://t.me/AStocksBot)


[AStocksBot](https://t.me/AStocksBot) is a new telegram bot he's been created with python and running on AzureVM and has **a lot** of stock commands   
hare is some exemples

link : https://t.me/AStocksBot


## change command  
### the change command will allow **you** to get the price, the range, and even more! about **any** stock
### when the price target that you have defined is been achieved, you will be noticed!


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

### to stop this command

```
/stop
```



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
19:53 [you]: /market_status

19:53 [AStocksBot]: normal


"""
```


```
/market_status
```





## crypto command
### this command will show you the top crypto coins
```python
                                                 date 18/07/2021








"""                
20:03 [you]: /crypto

20:03 [AStocksBot]: BTC-USD, ETH-USD, USDT-USD, BNB-USD, ADA-USD, XRP-USD, USDC-USD, HEX-USD, DOGE-USD, DOT1-USD,


"""
```


```
/crypto
```



# active command
### this command will show you the top 10 (or any amount that you will choose) of stocks with the must big change.

```python
                                                 date 19/07/2021








"""                
20:14 [you]: /active

20:14 [AStocksBot]: hare is top 10
  AMC (9.6%)
  AAPL (0.08%)
  SPCE (1.0%)
  NIO (3.16%)
  WISH (4.7%)
  NOK (-2.06%)
  DIDI (3.88%)
  BAC (-0.04%)
  CLOV (-2.3%)
  AMD (-0.04%)



20:14 [you]: /active 3

20:14 [AStocksBot]: 
  AMC (10.74%)
  AAPL (0.2%)
  SPCE (-0.54%)


"""
```
```
/active <NumberOfStocks : max is 50>
```



#info command
### info command can help you get info like: phone number,city,country about the compeny of the stock
```python
                                                 date 20/07/2021








"""                
20:36 [you]: /info cgib

20:36 [AStocksBot]: invalid symbol

20:37 [you]: /info bigc


20:37 [AStocksBot]: BigCommerce Holdings, Inc. (https://www.bigcommerce.com)
   BigCommerce Holdings, Inc. operates a software-as-a-service platform for small businesses, mid-markets, and large enterprises in the United States. The company's platform        provides various services for launching and scaling ecommerce operation, including store design, catalog management, hosting, checkout, order management, reporting, and pre-    integrations. As of December 31, 2020, it served approximately 60,000 online stores across industries in approximately 155 countries. BigCommerce Holdings, Inc. was founded      in 2009 and is headquartered in Austin, Texas.

20:37 [AStockBot]: MORE INFO
  city: Austin
  country: United States
  phone: 512 865 4500
  address 1: 11305 Four Points Drive
  sector: Technology
  zip: 78726
  market: us_market

"""
```




#news command
### this command will show you the last news in this month   
### and also can transalte the news using the google translate

without translate

![image](https://user-images.githubusercontent.com/78441039/125805048-2e4dde8e-64f1-439a-8b92-4df77c132b86.png)
![image](https://user-images.githubusercontent.com/78441039/125805522-967b37cb-952d-4418-8bd8-3616e2b2c420.png)

and even more

with translate

![video](videos/news.webm)

##if you have any Questions ask me but please see ![this file](faq.md) first 

