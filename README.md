# Python-Data-Analysis-Projects
This repo contains a list of various data analysis projects carried out in python

<!DOCTYPE html>
<html>
<head>

</head>
<body>
  <h1>1. Yahoo Finance Company Performance Analysis</h1>

  <h2>Data Collection</h2>
  <p>Started by importing the necessary libraries in Python to perform the analysis, such as Pandas, NumPy, matplotlib, and yfinance. You then used the "yfinance" library to retrieve the historical price data for the past 12 months for each of the companies from Yahoo Finance. The time range was between June 2022 to June 2023</p>

  <h2>Price Analysis</h2>
  <p>After obtaining the historical price data, I focused on the closing prices of the stocks. Closing prices are commonly used to analyze the performance of stocks over time. I extracted the closing prices for Apple, Microsoft, Netflix, Google, Amazon, and Meta for the past 12 months.</p>

Findings:
- Google had the lowest price action overall while Netflix exhibited the highest price action

![Price movement](https://github.com/martinkilombe/Python-Data-Analysis-Projects/blob/main/Yahoo%20Finance%20Company%20Performance/12%20month%20price%20movement.png)  

  <h2>Price Comparison</h2>
  <p>With the closing prices for the last 12 months available, I proceeded to compare the performance of the companies based on their stock prices. This analysis allowed you to observe the relative changes in prices among the companies over the specified time frame (June 2022 to June 2023).</p>

![Price movement](https://github.com/martinkilombe/Python-Data-Analysis-Projects/blob/main/Yahoo%20Finance%20Company%20Performance/Price%20comparison.png)  

  <h2>Moving Averages (M10 and M20)</h2>
  <p>Moving averages are widely used in technical analysis to identify trends and smooth out price fluctuations. Calculated the moving averages M10 and M20 for each respective company. The M10 represents the average price over the past 10 days, while the M20 represents the average price over the past 20 days. By calculating these moving averages, I aimed to identify potential trends in the stock prices of the companies.</p>
Findings:

- The output shows the Netflix output. When the MA10 crosses above the MA20, it is considered a bullish signal indicating that the stock price will continue to rise. Conversely, when the MA10 crosses below the MA20, it is a bearish signal that the stock price will continue falling as shown below.

![Moving average](https://github.com/martinkilombe/Python-Data-Analysis-Projects/blob/main/Yahoo%20Finance%20Company%20Performance/NFLX%20Moving%20average.png) 


  <h2>Volatility Analysis</h2>
  <p>Volatility is a measure of the variability or dispersion of a stock's price over a specific period. You calculated the volatility of each company using a suitable method, such as the standard deviation or the average true range (ATR). Volatility analysis helps in understanding the level of risk associated with a particular stock and provides insights into potential price fluctuations. Plotted the calculated volatilities for the various companies on a chart. This chart allowed you to compare the volatility levels among Apple, Microsoft, Netflix, Google, Amazon, and Meta. By examining the volatility plots, you could identify stocks with higher or lower levels of risk and make informed decisions based on your risk tolerance and investment objectives.</p>

![Volatility](https://github.com/martinkilombe/Python-Data-Analysis-Projects/blob/main/Yahoo%20Finance%20Company%20Performance/Volatility.png) 
  <h2>Correlation Analysis</h2>
  <p>Finally, calculated the correlation between Apple and Microsoft. Correlation measures the statistical relationship between two variables, in this case, the stock prices of Apple and Microsoft. The correlation coefficient ranges from -1 to 1, where -1 represents a strong negative correlation, 0 represents no correlation, and 1 represents a strong positive correlation. By calculating the correlation between Apple and Microsoft, you aimed to understand the degree to which the stock prices of these two companies move together.</p>

Findings:
- There is a strong linear relationship between the stock prices of Apple and Microsoft, which means that when the stock price of Apple increases, the stock price of Microsoft also tends to increase. It is a sign of a strong correlation or similarity between the two companies, which can be due to factors such as industry trends, market conditions, or common business partners or customers. For investors, this positive correlation may indicate an opportunity to diversify their portfolio by investing in both companies, as both stocks may offer similar potential returns and risks.

![Correlation](https://github.com/martinkilombe/Python-Data-Analysis-Projects/blob/main/Yahoo%20Finance%20Company%20Performance/correlation.png) 
  
  <h2>Overall:</h2>
  <p>This analysis allowed you to assess the performance of Apple, Microsoft, Netflix, Google, Amazon, and Meta over the past 12 months based on their stock prices. By calculating moving averages, plotting charts, calculating volatilities, and determining correlations, you gained insights into the trends, risks, and relationships among these companies, enabling you to make more informed investment decisions.</p>

  So this is how you can perform stock market analysis using Python.
   <p><a href="https://github.com/martinkilombe/Python-Data-Analysis-Projects/blob/main/Yahoo%20Finance%20Company%20Performance/Yahoo%20Finance%20Stock%20Market%20Performance%20Analysis.ipynb">Link to Python code</a></p>
</body>
</html>

