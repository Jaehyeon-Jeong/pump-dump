# 🧪 Pump & Dump Detector for Crypto Tokens

This project detects potential pump and dump schemes in real-time using:
- Binance US market data via `ccxt`
- Market cap classifications from CoinGecko
- Price/volume anomaly detection with statistical thresholds
- Liquidity trap detection via order book analysis

## 🔍 Features
- Real-time price & volume spike detection
- Micro-cap filtering for manipulation risk
- Order book depth analysis (bid/ask liquidity)
- Output list of flagged tokens

