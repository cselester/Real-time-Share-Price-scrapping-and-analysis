# 📊 Real-time Share Price scrapping and Analysis

This project fetches real-time stock prices for selected **US stocks**, converts them to **INR** using live exchange rates, and performs **data analysis and visualization**. It includes **data scraping**, **API fallback**, **cleaning**, **exploratory data analysis (EDA)**, **anomaly detection**, and exports results to Excel.

---

## 🚀 Features

- ✅ Live stock price scraping from [Groww](https://groww.in/)
- 🔁 Fallback to Alpha Vantage API if scraping fails
- 💱 Real-time USD to INR exchange rate (via Alpha Vantage API)
- 🧼 Data cleaning and preprocessing
- 📈 Exploratory Data Analysis (EDA) & anomaly detection
- 📊 Visualizations using Matplotlib & Seaborn
- 📁 Export results to `us_stock_prices_analysis.xlsx`

---

## 🛠️ Installation

Install all required dependencies:

```bash
pip install openpyxl beautifulsoup4 lxml pandas matplotlib seaborn numpy
