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
```

## Power BI dashboard
Page 1 : Stock Price Comparison
![Screenshot 2025-06-10 213951](https://github.com/user-attachments/assets/eae56eea-c469-4022-99f2-c6dfccdbfaa9)


Page 2 : Volume Analysis & Insights
![Screenshot 2025-06-10 213958](https://github.com/user-attachments/assets/df5e1df0-5226-4f15-9bd9-30af60b63fd7)
