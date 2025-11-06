# Stock-Market-Analysis

Problem Statement:

The goal was to perform stock market analysis for Microsoft (MSFT) by evaluating various financial metrics, including stock price trends, moving averages, earnings, and overall financial health. The analysis aimed to provide a deeper understanding of the stock's performance, evaluate its financial stability, and visualize key financial indicators over time to inform investment decisions.

What I Did:

1. Stock Price Analysis:

Historical Stock Price Analysis: Used the yfinance library to fetch Microsoft's stock data over the past 6 months, including the stock’s adjusted closing price.

Visualization: Plotted the stock's adjusted closing price over time to identify trends and fluctuations.

2. Resampling and Moving Averages:

Resampled Data: Resampled the 1-minute stock data to 10-minute intervals to smooth the time series data.

Moving Averages: Calculated 20-period and 50-period moving averages (MAs) to identify trends and potential buying or selling signals.

3. Financial Metrics:

Stock Fundamentals: Retrieved key stock fundamentals, such as the Price-to-Book ratio, Price-to-Earnings (P/E) ratio, and Market Cap using the yfinance API.

Revenue Analysis: Used bar charts to visualize MSFT’s total revenue and operating income over the last few years.

4. Financial Statement Analysis:

Retrieved detailed financial data, including key financial statements such as EBIT, EBITDA, Net Income, Free Cash Flow, and other financial metrics over the past few years.

Financial Visualization: Created bar charts for revenue and EBIT to visualize performance across multiple quarters.

Tools Used:

yfinance: A Python library used to fetch stock data (e.g., historical prices, financial metrics) for Microsoft and other stocks.

Pandas: Used for data manipulation, such as resampling stock data, calculating moving averages, and analyzing financial statements.

Matplotlib & Seaborn: Used for visualizing the data through various charts, such as line graphs for stock price trends and bar charts for revenue and financial metrics.

Jupyter Notebook: Used for data analysis, visualization, and code execution.

Recommendations:

1. Stock Price Trends:

The stock’s price shows a strong upward trend based on the recent data. If the moving averages continue to diverge positively, it could indicate a strong buy signal.

The fluctuations suggest that investors should monitor for dips in stock prices and potential opportunities for entry during price pullbacks.

2. Investment Strategy:

Short-Term: For short-term traders, the moving averages and resampled data provide insights into possible entry points, especially if there’s a positive cross-over between shorter and longer-term moving averages.

Long-Term: Investors holding for the long term should focus on Microsoft's strong fundamentals, as indicated by its stable P/E ratio and increasing market cap. The company’s steady revenue and net income growth support long-term growth potential.

3. Financial Health:

Microsoft's financial data shows strong free cash flow and profitability. Investors should consider the company's ability to generate consistent earnings and manage operational costs. The growth in EBITDA and EBIT suggests that Microsoft is operating efficiently, which should be attractive to long-term investors.

4. Diversification:

Given the strong performance of Microsoft's stock, it could be a good candidate for inclusion in a diversified portfolio. However, investors should be cautious about market fluctuations and ensure they are not overexposed to any one asset.

Conclusion:

Microsoft’s stock presents an attractive opportunity for both short-term traders and long-term investors. Regular monitoring of key financial ratios and stock price trends will help optimize investment decisions.
