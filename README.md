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

## 📊 Sample Output
Unusual VOLUME detected: BTC/USDT
Unusual VOLUME detected: ETH/USDT
Unusual VOLUME detected: XRP/USDT
Unusual VOLUME detected: BCH/USDT
LIQUIDITY TRAP detected: BCH/USDT
Unusual VOLUME detected: LTC/USDT
LIQUIDITY TRAP detected: LTC/USDT
Unusual VOLUME detected: BNB/USDT
Unusual VOLUME detected: ADA/USDT
Unusual VOLUME (MICRO CAP) detected: BAT/USDT
LIQUIDITY TRAP detected: BAT/USDT
Unusual VOLUME detected: ETC/USDT
Unusual VOLUME detected: XLM/USDT

Potential Pump & Dump Candidates:
['BTC/USDT', 'ETH/USDT', 'XRP/USDT', 'BCH/USDT', 'LTC/USDT', 'BNB/USDT', 'ADA/USDT', 'BAT/USDT', 'ETC/USDT', 'XLM/USDT']
