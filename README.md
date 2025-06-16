# 📈 Real-Time Stock Market Insights with Sentiment Analysis

This project offers a **real-time stock monitoring dashboard** that combines **market sentiment analysis** (from tweets/news) with **live stock prices** to provide actionable insights. It leverages **FinBERT**, Yahoo Finance API, and **Streamlit** to deliver a simple yet powerful data science application.

---

## 🚀 Features

- 📊 **Live Stock Price Tracking** using `yfinance`
- 🧠 **Sentiment Analysis** on financial text using FinBERT (BERT-based model fine-tuned for finance)
- 🌐 Designed to plug into Twitter and News APIs (extensible)
- 📉 Interactive Streamlit dashboard with charts and NLP insights

---

![Dashboard Preview](./screenshot.png)

Live market analysis platform with sentiment integration powered by:
- Alpha Vantage API
- NewsAPI
- Dash/Plotly

## Features
- Real-time stock price tracking
- Dual sentiment analysis (TextBlob + VADER)
- News feed integration
- Interactive OHLC charts
- Auto-refreshing data

## Installation
```bash
git clone https://github.com/yourusername/stock-insights.git
cd stock-insights
pip install -r requirements.txt
```

## Configuration
1. Get API keys:
   - [Alpha Vantage](https://www.alphavantage.co/support/#api-key)
   - [NewsAPI](https://newsapi.org/register)
2. Create `.env` file:
```ini
ALPHA_VANTAGE_API_KEY=your_key_here
NEWS_API_KEY=your_newsapi_key
```

## Usage
```powershell
# Windows
$env:ALPHA_VANTAGE_API_KEY="your_key"; $env:NEWS_API_KEY="your_news_key"; python app.py
```
Access dashboard at: http://localhost:8050

## Dashboard Preview
![Dashboard Interface](./screenshot.png)

## Contributing
1. Fork the repository
2. Create feature branch
3. Submit PR with detailed description

## License
MIT

## 📌 License

MIT License. Feel free to use and adapt for personal or professional purposes.

---

## 👨‍💻 Author

**Abhishek Totre**  
Connect on [LinkedIn](https://www.linkedin.com/in/abhishektotre981/) | GitHub: [Abhishektotre](https://github.com/abhishektotre)
