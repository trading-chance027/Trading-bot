# Trading Bot

A fully automated trading bot designed to trade stock options using a combination of technical indicators and strategy filters. The bot integrates with Interactive Brokers (IBKR) and is built with Python.

## Purpose
This trading bot is designed to assist with **stock options trading** using specific algorithms. It makes decisions based on technical analysis and predefined filters such as RSI, MACD, ATR, and volume-based strategies. The bot aims to automate and optimize your trading strategy.

## Features
- **Options Trading:** Trades **calls** and **puts** based on your strategy.
- **Risk Management:** Includes risk filters to minimize drawdowns and manage exposure.
- **Volume Filters:** Allows for additional trading criteria based on stock volume.
- **Paper Trading:** Test your strategies in a simulated environment without risking real capital.
- **Real Trading:** Option to go live with real capital once the bot is fully tested.

## Setup and Installation

### Prerequisites
- **Python 3.8+**
- **Interactive Brokers (IBKR) Account** for live or paper trading
- **IBKR API setup** (Use `ib_insync` library)
- Install dependencies with:
```bash
pip install -r requirements.txt
