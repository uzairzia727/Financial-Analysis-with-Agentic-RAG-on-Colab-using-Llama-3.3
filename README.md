# Financial-Analysis-with-Agentic-RAG-on-Colab-using-Llama-3.3
A sophisticated Agentic RAG system for financial analysis that runs entirely on Google Colab without GPU requirements!
# 🏦 Financial Analysis Agentic RAG System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Groq](https://img.shields.io/badge/Groq-API-green.svg)](https://groq.com/)
[![Colab](https://img.shields.io/badge/Google-Colab-orange.svg)](https://colab.research.google.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A sophisticated Agentic Retrieval-Augmented Generation (RAG) system for financial analysis, built to run on Google Colab without GPU requirements.

## 🚀 Features

- **Agentic RAG Architecture**: Intelligent retrieval and generation pipeline
- **Real-time Financial Data**: Stock prices, company info, market indices
- **Multi-source Integration**: Yahoo Finance, financial news, company filings
- **Cloud Vector Database**: ChromaDB for efficient document retrieval
- **Free LLM Integration**: Groq API with Llama 3.2 90B model
- **Google Colab Optimized**: No GPU required, minimal dependencies

## 📊 Capabilities

1. **Stock Analysis**: P/E ratios, financial metrics, performance trends
2. **Market Insights**: Sector analysis, comparative analysis
3. **Investment Guidance**: Risk assessment, portfolio suggestions
4. **Technical Analysis**: Chart patterns, indicators, trends
5. **Company Fundamentals**: Financial statements, ratios, growth metrics

## 🛠️ Quick Start

```python
# Clone and run in Google Colab
!git clone https://github.com/yourusername/financial-agentic-rag.git
%cd financial-agentic-rag

# Install dependencies
!pip install -r requirements.txt

# Run the system
from financial_rag import FinancialRAGSystem
rag = FinancialRAGSystem()
rag.query("Analyze Apple stock for long-term investment")
