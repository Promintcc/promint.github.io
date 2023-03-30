---
label: "Correlation"
icon: cpu
order: 1900
---

![](/static/headers/promint-banner.jpg)


## Crypto-Currency Correlation Alerts

In theory, some crypto-currency tokens has lags between them.
Our back-end correlation finds best matches and starts tracking them.

Basically If XXX token rose +%2 in last 5 minutes, we will alert this token with it's correlated pair and
we can expect same move in a short-time period on correlated pair.

Currently we support Binance and Kucoin USDT pairs.

### Example Result

XXX token rose %2 in last 5m. and correlated YYY pair followed same move for next 5 min.

![](/crypto/images/PORTOUSDT_37a14cPORTOUSDT.png) ![](/crypto/images/SANTOSUSDT_c5276dSANTOSUSDT.png)

---