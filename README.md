# AITradeGame - Open Source AI Trading Simulator

[English](README.md) | [中文](README_ZH.md)

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/flask-3.0+-green.svg)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

AITradeGame is an AI trading simulator that supports both local and online versions.

Provides an online version with interactive features and leaderboards.

Local version stores all data on your computer, no cloud storage, no tracking.

Includes a Windows one-click standalone executable that runs without installation.

## Features

### Desktop Version (Local)

AI-driven trading strategies based on large language models, compatible with OpenAI, DeepSeek, Claude, and other models. Leveraged portfolio management with ECharts visualizations. 100% privacy with all data stored in local database.

### Online Version (Public)

Leaderboard functionality to compete with AI enthusiasts worldwide. Real-time rankings display providing performance comparisons and analysis. Auto-sync and background operation enabling seamless multi-device experience.

## Quick Start

### Try Online Version

Launch the online version at https://aitradegame.com without any installation.

### Desktop Version

Download AITradeGame.exe from GitHub releases. Double-click the executable to run. The interface will open automatically. Start adding AI models and begin trading.

Alternatively, clone the repository from GitHub. Install dependencies with pip install -r requirements.txt. Run the application with python app.py and visit http://localhost:5000.

## Configuration

Configure AI models through the web interface opened by the software. Enter model name, API key, and API address. Choose your initial capital amount to start trading.

## Supported AI Models

Supports all OpenAI-compatible APIs. This includes OpenAI models like gpt-4 and gpt-3.5-turbo, DeepSeek models including deepseek-chat, Claude models through OpenRouter, and any other services compatible with OpenAI API format. More protocols are being added.

## Usage

Start the server by running AITradeGame.exe or python app.py. Add AI model configuration through the web interface at http://localhost:5000. The system automatically begins trading simulation based on your configuration.

## Privacy and Security

All data is stored in the AITradeGame.db SQLite file in the same directory as the executable. No external servers are contacted except your specified AI API endpoints. No user accounts or login required - everything runs locally.

## Development

Development requires Python 3.9 or later. Internet connection is needed for market data and AI API calls.

Install all dependencies with: pip install -r requirements.txt

## Contributing

Community contributions are welcome.

## Disclaimer

This is a simulated trading platform for testing AI models and strategies. It is not real trading and no actual money is involved. Always conduct your own research and analysis before making investment decisions. No warranties are provided regarding trading outcomes or AI performance.

## Links

Online version with leaderboard and social features: https://aitradegame.com

Desktop builds and releases: https://github.com/chadyi/AITradeGame/releases/AITradeGame.zip

Source code repository: https://github.com/chadyi/AITradeGame
