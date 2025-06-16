# 📈 Real-Time Stock Market Insights with Sentiment Analysis

This project offers a **real-time stock monitoring dashboard** that combines **market sentiment analysis** (from tweets/news) with **live stock prices** to provide actionable insights. It leverages **FinBERT**, Yahoo Finance API, and **Streamlit** to deliver a simple yet powerful data science application.

---

## 🚀 Features

- 📊 **Live Stock Price Tracking** using `yfinance`
- 🧠 **Sentiment Analysis** on financial text using FinBERT (BERT-based model fine-tuned for finance)
- 🌐 Designed to plug into Twitter and News APIs (extensible)
- 📉 Interactive Streamlit dashboard with charts and NLP insights

---

## 🔧 Tech Stack

| Component         | Tool/Library                     |
|------------------|----------------------------------|
| Dashboard         | [Streamlit](https://streamlit.io) |
| Sentiment Model   | [FinBERT (HuggingFace)](https://huggingface.co/ProsusAI/finbert) |
| Data Source       | [Yahoo Finance](https://finance.yahoo.com) via `yfinance` |
| Language          | Python 3.8+                      |

---

## 🗂️ Project Structure

```
real_time_stock_sentiment/
├── app/                   # Streamlit dashboard
├── config/                # API keys, config files
├── data/                  # Tweet/news data (if applicable)
├── models/                # FinBERT model cache
├── notebooks/             # Jupyter notebooks for testing
├── src/                   # Core logic for data fetching & sentiment
├── utils/                 # Helper functions
├── tests/                 # Unit tests
├── .env                   # Environment variables
├── requirements.txt       # Python dependencies
├── run.py                 # Entry point
└── README.md              # Project documentation
```

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/real_time_stock_sentiment.git
cd real_time_stock_sentiment
pip install -r requirements.txt
```

**Add your API keys** to the `.env` file:
```
TWITTER_BEARER_TOKEN=your_token_here
NEWS_API_KEY=your_token_here
```

---

## ▶️ Run the Dashboard

```bash
python run.py
```

Then go to: [http://localhost:8501](http://localhost:8501)

---

## 🧪 Sample Output

```
News: "Tesla shares rise after strong Q1 earnings report."
→ Sentiment: POSITIVE (0.91)
```

Live price chart will display below.

---

## 🧱 Future Enhancements

- Integrate real Twitter/X and News API
- Add forecasting using LSTM or Prophet
- Alert system based on price + sentiment shift
- Cloud deployment on AWS or Streamlit Cloud

---

## 📌 License

MIT License. Feel free to use and adapt for personal or professional purposes.

---

## 👨‍💻 Author

**Abhishek Totre**  
Connect on [LinkedIn](https://www.linkedin.com/in/abhishektotre981/) | GitHub: [yourusername](https://github.com/abhishektotre)
