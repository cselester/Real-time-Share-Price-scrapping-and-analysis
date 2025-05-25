<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>US & INR Stock Price Analysis Tool</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; margin: 2em;">

    <h1>Real-time Share Price scrapping and analysis</h1>

    <p>This Python project fetches <strong>real-time stock prices</strong> for major <strong>US stocks</strong>, converts them to <strong>INR using the USD-INR exchange rate</strong>, and performs <strong>data analysis and visualization</strong>, including anomaly detection and statistical summaries.</p>

    <hr>

    <h2>📌 Features</h2>
    <ul>
        <li>Live stock price scraping from <a href="https://groww.in/" target="_blank">Groww</a></li>
        <li>Fallback to Alpha Vantage API for reliability</li>
        <li>Real-time USD to INR exchange rate fetch using Alpha Vantage</li>
        <li>Data cleaning, transformation, anomaly detection</li>
        <li>Visualizations: bar plots, scatter plots, boxplots</li>
        <li>Export final dataset to Excel</li>
    </ul>

    <hr>

    <h2>🛠️ Requirements</h2>
    <p>Install the required Python packages:</p>
    <pre><code>pip install openpyxl beautifulsoup4 lxml pandas matplotlib seaborn numpy</code></pre>

    <hr>

    <h2>🧾 Setup</h2>
    <ol>
        <li>Register at <a href="https://www.alphavantage.co/support/#api-key" target="_blank">Alpha Vantage</a> to get a free API key.</li>
        <li>Replace <code>API_KEY</code> in the script with your key:</li>
    </ol>
    <pre><code>API_KEY = 'YOUR_API_KEY_HERE'</code></pre>

    <hr>

    <h2>🚀 How to Run</h2>
    <ol>
        <li>Run the Python script using your IDE or Jupyter notebook.</li>
        <li>The script will:
            <ul>
                <li>Scrape or request stock data</li>
                <li>Convert USD prices to INR</li>
                <li>Perform exploratory data analysis</li>
                <li>Export results to <code>us_stock_prices_analysis.xlsx</code></li>
            </ul>
        </li>
    </ol>

    <hr>

    <h2>📊 Visualizations</h2>
    <ul>
        <li><strong>Bar Plot</strong> – INR prices by data source</li>
        <li><strong>Scatter Plot</strong> – Highlights anomalies</li>
        <li><strong>Box Plot</strong> – Log-scaled volume distribution</li>
    </ul>

    <hr>

    <h2>🗂️ Output</h2>
    <p>The saved Excel file includes the following columns:</p>
    <ul>
        <li>Symbol</li>
        <li>Price (USD)</li>
        <li>Price (INR)</li>
        <li>Source (Scraped/API)</li>
        <li>Log Price INR</li>
        <li>Anomaly</li>
        <li>Volume (simulated)</li>
        <li>LogVolume</li>
    </ul>

    <hr>

    <h2>🔒 Notes</h2>
    <ul>
        <li>To avoid API rate limits, the script waits 12 seconds between requests.</li>
        <li>If the currency conversion API fails, a fallback USD-INR rate is used.</li>
        <li>Support for Indian stocks via BSE can be added in the future.</li>
    </ul>

    <hr>

    <h2>📄 License</h2>
    <p>MIT License – you are free to use and adapt this for personal or educational use.</p>

</body>
</html>
