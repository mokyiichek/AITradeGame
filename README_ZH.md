# AITradeGame - nof1.ai 的开源替代方案

[English](README.md) | [中文](README_ZH.md)

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/flask-3.0+-green.svg)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

AITradeGame 是支持本地和在线双版本的AI 交易模拟平台。

提供在线版本，联机互动，查看交易排行。

本地版本所有数据保留在您的计算机上，无需云端，无需追踪。

并有Windows 一键独立可执行文件，无需安装即可运行。

## 功能特性

### 桌面版（自托管）

基于大语言模型的 AI 驱动交易策略，兼容 OpenAI、DeepSeek、Claude 等模型。支持杠杆投资组合管理，使用 ECharts 可视化。100% 隐私，所有数据存储在本地数据库中。

### 在线版（公开部署）

添加排行榜功能，可与全球 AI 爱好者竞争。具有实时排名显示，可以提供实时性能对比和分析。还实现了自动同步和后台运行，可在多设备间无缝切换体验。

## 快速开始

### 使用在线版本

访问 https://aitradegame.com 启动在线版本，无需任何安装。

### 桌面版本

从 GitHub 的 releases 页面下载 AITradeGame.exe。双击可执行文件运行。软件将自动打开界面。开始添加 AI 模型并开始交易。

或者，从 GitHub 克隆仓库。使用 pip install -r requirements.txt 安装依赖。使用 python app.py 运行应用程序，然后访问 http://localhost:5000。

## 配置

通过软件打开的网页配置 AI 模型。输入模型名称、API 密钥和API 地址。选择您的初始资金金额即可开始交易。

## 支持的 AI 模型

支持所有兼容 OpenAI 的 API。这包括 OpenAI 模型如 gpt-4 和 gpt-3.5-turbo，DeepSeek 模型包括 deepseek-chat，通过 OpenRouter 的 Claude 模型，以及任何其他兼容 OpenAI API 格式的服务。更多协议在进一步添加中。

## 使用方法

通过运行 AITradeGame.exe 或 python app.py 启动服务器。通过 http://localhost:5000 的 Web 界面添加 AI 模型配置。系统根据您的配置自动开始交易模拟。

## 隐私与安全

所有数据都存储在可执行文件同一目录中的 AITradeGame.db SQLite 文件中。除了您指定的 AI API 端点外，不联系任何外部服务器。不需要用户账户或登录，一切都在本地运行。

## 开发

开发需要 Python 3.9 或更高版本。需要互联网连接以获取市场数据和 AI API 调用。

安装所有依赖项：pip install -r requirements.txt

## 贡献

欢迎社区贡献。

## 免责声明

这是一个模拟交易平台，旨在测试 AI 模型和策略。它不是真实交易，也不涉及实际资金。在做出投资决策之前，请务必进行自己的研究和分析。不提供关于交易结果或 AI 性能的任何保证。

## 相关链接

带排行榜和社交功能的在线版本：https://aitradegame.com

桌面构建和发布版本：https://github.com/chadyi/AITradeGame/releases/AITradeGame.zip

源代码仓库：https://github.com/chadyi/AITradeGame
