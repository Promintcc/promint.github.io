---
label: "FOMO Alerts"
icon: pulse
order: 1900
---

![](/static/headers/promint-banner.jpg)

## FOMO Bot Features

FOMO Bot is currently one of the best bot for NFT traders in the space.
We catch the latest and fastest NFT sales on marketplaces
(OpenSea, Blur, X2Y2, Looksrare, and more.) and creates live charts based on custom data.

These charts are order book, instant floor, scatter-plot sales and sales by timeframe.
Timeframes can differ based on collection creation date, new collections has 5 minutes timeframe.

While our backend software updates the data of all trending collections every 30 seconds this bot generates alerts for collections with more than 10 NFT sales in the last 5 minutes.

Based on sales volume or/and volume in ETH, this bot pings related roles on the Discord channels.

FOMO Alerts channels can be customized.
- New Collection Alerts Channel
- High Volume Alerts Channel
- Extreme Volume Alerts Channel

### FOMO Charts
- Current and Previous Listings Orderbook Chart
- Last 50 Sales Scatter-plot Chart
- Sales Floor Chart
- Sales Count Chart

### FOMO Metrics
- Unique Wallets
- BlueChip Holders
- Unique Sales
- NDCP Score (Next Degen Collection Probabilty Score)

### FOMO Indicators
- Buying / Selling Pressure
- Sell Wall
- FOMO Level

---

## Role Ping Mechanism

NEW FOMO, HIGH FOMO, EXTREME FOMO and EXTREME SELL

We are processing whole data to create meaningful pings, Increasing or Decreasing Sales, Increasing or Decreasing BlueChip Index, Increasing or Decreasing listings etc.

For example EXTREME SELL ping is based on current indicators that current listings are increasing, last 5 minutes sales are decreasing and decreasing NDCP score. Combining these datas will trigger this role.

For decreasing noise we ping each collection once for 30 minutes.

---

## Social Scoring Mechanism

FOMO Bot is not just a sales alerting bot, we are fetching social data real-time for new collections and determining it's RISK and Hype scores.

### RISK Score
Based on social allegations about rug, copy-mint or drainer we are providing early potential risk alert.

### Sentiment Score
Based on social engagement we are providing Sentiment score that project got a lot of positive feedback from current NFT traders.

---

## Data Tracking & RSI
We are storing each alerts stats and creating useful metrics like Low/High Floor, XXX amount times alerted in the last 24 Hour. Based on these stats we suggest RSI Stop Loss price and if you don't exit trade we show In Loss metric.

---

## Sell Wall Indicator

This indicator processing complex data for each alerts, and determining collection specific value. These values are "Thick" and "Thin", and can vary based on collection latest data including, current sales, current listings, previous listings, and expected next 5 minutes sales and next 5 minutes listings. This algorithm contouniosly evolving based on previous alerts.

---

## Current Pressure Indicator

This indicator is processing Current Listings, Previous Listings, Current Sales, Last Sales, Current Floor and, Previous Floor. 
This lagging indicator provides direction of floor price of collection. 

### Pressure Levels
Extreme Buy, Strong Buy, Buy, Neutral Buy, Neutral Sell, Sell, Extreme Sell

This values does not provides "buy" or "sell" signals, it can be vary on other indicator values.
That's mean, you may get "Extreme Buy" alert top of price of floor.
By combining these indicating values, you may sell your item at the top of floor price or you can accumulate while indicator shows Neutral Sell.

---

## NDCP Score

This score calculated by checking most HIGH ROI wallets at background for each alert. We are checking over 2000+ wallets to determine this score.

We're going to add more wallets over time, currently there is no limit for this score but we may limit to 1000 maximum.

This score will update every 15 minutes for each collection.

---

[!button text="Buy Standalone 0.75Ξ/Year" icon="star-fill"](https://twitter.com/promintcc)

---

## Example Alerts
![](/nft/images/newfomo.jpg) ![](/nft/images/extremefomo.jpg)