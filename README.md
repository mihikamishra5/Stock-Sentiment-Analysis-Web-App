# Stock-Sentiment-Analysis-Web-App

 simple yet powerful web application that helps analyze public sentiment on Reddit related to any stock ticker and visualize recent stock data using Yahoo Finance. Built using Flask, VADER (NLTK), Reddit API, and yFinance.

🚀 Project Overview

This tool allows you to:

🧠 Analyze public sentiment for any stock based on Reddit posts.
💬 Understand whether a stock is trending bullish, bearish, or neutral.
📊 Visualize recent historical stock prices (past 30 days).
🌐 Use via a simple web interface (Flask frontend).
Perfect for retail traders, data science learners, and anyone interested in sentiment-based stock insights.

# 🛠️ Setup Instructions

## 1. Clone the Repo
git clone https://github.com/your-username/stock-sentiment-analyzer.git
cd stock-sentiment-analyzer
## 2. Create and Activate a Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
## 3. Install Dependencies
pip install -r requirements.txt
## 4. Set Up Reddit API Credentials
Create a file named .env inside the src/ directory:

REDDIT_CLIENT_ID=your_client_id
REDDIT_CLIENT_SECRET=your_client_secret
REDDIT_USER_AGENT=your_user_agent
To get these credentials, create a Reddit app here: https://www.reddit.com/prefs/apps

# ▶️ How to Run

## A. Use CLI Tool (Terminal)
python stock_sentiment.py
Enter a stock symbol (like AAPL or TSLA)
The script will display Reddit sentiment and print recent relevant posts
## B. Launch the Web App
cd src
python app.py
