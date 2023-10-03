# NOTICE this BOT is no longer running!
# NOTICE this BOT is no longer running!
# NOTICE this BOT is no longer running!
# NOTICE this is an old readme file for a bot i used to run!

# Telegram AStocksBot [![Send Our Bot Message](https://img.shields.io/badge/the-bot-brightgreen.svg?style=flat)](https://t.me/AStocksBot)

[AStocksBot](https://t.me/AStocksBot) is a new Telegram bot. It's created using Python and runs on AzureVM, offering a wide range of stock-related commands. Here are some examples:

Link: [https://t.me/AStocksBot](https://t.me/AStocksBot)

## Change Command
### The 'change' command enables you to fetch price, range, and more details about any stock. You'll even receive notifications when your defined price target is achieved.

```python
Date: 15/07/2021

11:23 AM - You: /change bigc 5

11:23 AM - AStocksBot: I'll notify you when BigC's stock price changes by $5.

3:37 PM - AStocksBot: BigC's price has changed! Here's the updated information:
  - Current Price: $62.01
  - Change: +$2.82 (4.56%)
  - Range: ...
  
3:38 PM - You: /stop

3:38 PM - AStocksBot: I'll stop notifying you about BigC's stock price changes by $5.
```

```python
/change <Symbol> <Price>
```

**The default price is $0.1.**

### To stop this command:

```
/stop
```

## Get Command
### The 'get' command provides an easy way to retrieve price, range, change, and more details about a stock.

```python
Date: 16/07/2021

6:23 PM - You: /get BIGS

6:23 PM - AStocksBot: This is not a valid symbol.

6:24 PM - You: /get BIGC

6:24 PM - AStocksBot: Here's BigC's price information:
  - Current Price: $54.09
  - Change: -$8.72 (-16.12%)
  - Range: ...
  
6:25 PM - You: /get bigc

6:25 PM - AStocksBot: Here's BigC's price information:
  - Current Price: $54.09
  - Change: -$8.72 (-16.12%)
  - Range: ...
```

```python
/get <Symbol>
```

## Market Status Command
### The 'market_status' command informs you about the current market status.

```python
Date: 17/07/2021

7:53 PM - You: /market_status

7:53 PM - AStocksBot: Normal
```

```python
/market_status
```

## Crypto Command
### The 'crypto' command displays the top crypto coins.

```python
Date: 18/07/2021

8:03 PM - You: /crypto

8:03 PM - AStocksBot: Crypto coins: BTC-USD, ETH-USD, USDT-USD, BNB-USD, ADA-USD, XRP-USD, USDC-USD, HEX-USD, DOGE-USD, DOT1-USD.
```

```python
/crypto
```

# Active Command
### The 'active' command shows the top 10 (or a specified number, up to 50) stocks with the most significant changes.

```python
Date: 19/07/2021

8:14 PM - You: /active

8:14 PM - AStocksBot: Here are the top 10 stocks with their changes:
  - AMC (9.6%)
  - AAPL (0.08%)
  - SPCE (1.0%)
  - NIO (3.16%)
  - WISH (4.7%)
  - NOK (-2.06%)
  - DIDI (3.88%)
  - BAC (-0.04%)
  - CLOV (-2.3%)
  - AMD (-0.04%)

8:14 PM - You: /active 3

8:14 PM - AStocksBot: The top 3 stocks with their changes are:
  - AMC (10.74%)
  - AAPL (0.2%)
  - SPCE (-0.54%)
```

```python
/active <NumberOfStocks: Max is 50>
```

# Info Command
### The 'info' command provides information about a company associated with a stock symbol, including phone number, city, country, and more.

```python
Date: 20/07/2021

8:36 PM - You: /info cgib

8:36 PM - AStocksBot: Invalid symbol.

8:37 PM - You: /info bigc

8:37 PM - AStocksBot: Information about BigCommerce Holdings, Inc. (Website: [https://www.bigcommerce.com](https://www.bigcommerce.com)):
   - BigCommerce Holdings, Inc. operates a software-as-a-service platform for small businesses, mid-markets, and large enterprises in the United States. The company's platform provides various services for launching and scaling e-commerce operations, including store design, catalog management, hosting, checkout, order management, reporting, and pre-integrations. As of December 31, 2020, it served approximately 60,000 online stores across industries in approximately 155 countries. BigCommerce Holdings, Inc. was founded in 2009 and is headquartered in Austin, Texas.

8:37 PM - AStocksBot: Additional Information:
   - City: Austin
   - Country: United States
   - Phone: +1 512-865-4500
   - Address 1: 11305 Four Points Drive
   - Sector: Technology
   - Zip: 78726
   - Market: US Market
```

# News Command
### The 'news' command displays the latest news for the current month and can also translate the news using Google Translate.

- How it looks **without** translation:

![image](https://user-images.githubusercontent.com/78441039/126384721-47d70e64-39ff-40ab-a2d4-0fe5ad170b49.png)

And with translation:

![image](https://user-images.githubusercontent.com/78441039/126384392-5e7bfa7d-2570-44bf-b0ff-25a7aae2cfa2.png)

## If you have any questions, feel free to ask. Be sure to check out [this file](faq.md) for answers to common questions.
