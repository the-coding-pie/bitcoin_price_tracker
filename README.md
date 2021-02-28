## Bitcoin Price Notification script

A simple script made using python. 

## What It Can Do?

- Tracks the bitcoin price for every _ minutes and stores it in a list.
- When the list gets filled, it will send the data to your telegram app.
- If the bitcoin price falls below a certain `threshold` value, then it will send an immediate telegram message.

**Modifications**:

Changed CoinMarketCap API endpoint to 'quote' and limited the request to only the market symbol you are interested in.
 - Select cryptocurrency symbol (can also be used for other cryptocurrencies such as ETH)
 - Convert quote to different FIAT currency (ie. EUR instaad of hardcoded USD)

## To Make It Work...

To make this script work, you will need the following:

- <a href="https://pro.coinmarketcap.com/" target="_blank">coinmarketcap.com</a> api token
- A [telegram bot](https://core.telegram.org/bots#6-botfather) and it's `token`.
- Your telegram account's `chat_id`
- And Python3!

## For tutorial on how to make this from scratch, visit my blog --> [thecodingpie.com](https://thecodingpie.com)
