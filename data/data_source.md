# 📊 Data Source

This project uses live cryptocurrency market data from the CoinGecko API.

## 🔗 API Endpoint

https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=100&page=1&price_change_percentage=24h,7d

## 📌 Data Includes:
- Coin Name
- Market Cap
- Price
- Volume
- Circulating Supply
- Price Change (24h, 7d)

## ⚡ Notes:
- Data is fetched dynamically using Power BI Web connector
- The dataset updates based on API refresh
- No static dataset is stored in this repository