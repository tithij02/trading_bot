# Trading Bot – Binance Futures Testnet

## Setup
1. Clone repo
2. Install dependencies:
   pip install -r requirements.txt

3. Add .env file with API keys

## Run

Market Order:
python cli.py --symbol BTCUSDT --side BUY --type MARKET --quantity 0.001

Limit Order:
python cli.py --symbol BTCUSDT --side SELL --type LIMIT --quantity 0.001 --price 60000

## Features
- Market & Limit Orders
- BUY / SELL support
- Input validation
- Logging to file
- Error handling

## Assumptions
- Using Binance Futures Testnet
- Only USDT-M pairs supported