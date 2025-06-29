# Cryptocurrency Volume Analysis

Analyzes which days of the week have the highest trading volumes across cryptocurrency assets using the Binance API.

## Features

- Fetches top 50 crypto assets by volume
- Historical kline data retrieval
- Volume normalization to prevent large assets from skewing results
- Weekday trading pattern analysis
- Correlation and volatility analysis

## Setup

1. Install requirements: `pip install -r requirements.txt`
2. Create `config.py` with your Binance API keys:

```python
BINANCE_API_KEY = "your_key"
BINANCE_API_SECRET = "your_secret"
```

3. Run the notebook: `jupyter notebook volumn_analysis.ipynb`

## Key Results

- Which day has highest average volume
- Weekday vs weekend trading patterns
- Individual crypto volume patterns
- Raw vs normalized volume comparison
