# Extracting Stock Data using Web Scraping and API
This project focuses on utilizing Python to extract stock market data using various techniques, including the yfinance API and web scraping. The objective is to analyze and visualize the stock data for Tesla and GameStop, examining the relationship between stock prices and revenue, as well as the impact of external factors such as investor actions.
## Project Components
The project consists of the following key components:
1. Extracting Stock Data using yfinance API: Python's yfinance library is used to extract historical stock data for Tesla and GameStop. This provides essential information such as the opening and closing prices, volume, and date for each trading day.
2. Web Scraping Tesla Revenue Data: Web scraping techniques are employed to extract revenue data for Tesla from a specific source, such as a financial website. The revenue data is cleaned and transformed into a structured format for analysis.
3. Web Scraping GameStop Revenue Data: Similar to Tesla, web scraping techniques are used to extract revenue data for GameStop. This data is also cleaned and prepared for analysis.
4. Plotting Tesla Stock Graph: The extracted Tesla stock data is visualized using Python's Plotly library. A graph is created to display the historical share prices of Tesla over a specific period, providing insights into the stock's price fluctuations.
5. Plotting GameStop Stock Graph: The extracted GameStop stock data is plotted using Plotly. A graph is generated to illustrate the historical share prices of GameStop, enabling the comparison of its price dynamics with Tesla.
## Understanding the Stock Market Dynamics
The project highlights the complexity of determining stock prices, which depend on various factors, including a company's profitability, growth of profits, and market dynamics. An important consideration is the relationship between a company's profit and its stock price. Typically, increasing profits are associated with rising stock prices, making the stock an attractive investment. Conversely, if investors anticipate a decrease in stock prices, they may engage in short selling to profit from falling stock values.<br />
<br />Short selling involves borrowing stocks, selling them, and then repurchasing them at a lower price to return them to the lender. This strategy allows investors to make profits in declining markets. However, short sellers face the risk of incurring losses if the stock price increases unexpectedly.
<br /><br />The example of Tesla demonstrates the potential challenges faced by short sellers. Several years ago, Tesla was heavily targeted by short sellers. However, as the company became profitable and its profits continued to grow, the stock price started to rise. This upward trend was driven by the company's strong performance and indicated the need for short sellers to exit their positions by selling the stock. It is worth noting that short-term stock price increases may occur due to factors unrelated to a company's fundamental performance, making them less sustainable.
<br /><br />Another notable case is GameStop, a video and computer-game retailer that was experiencing financial difficulties. Individual investors on the Reddit online community, known as WallStreetBets, began buying shares of GameStop, causing a surge in demand. As a result, GameStop's stock price soared, leading to substantial losses for hedge funds that had previously sold the stock short. In this scenario, hedge funds are advised to hold onto their short positions, expecting the eventual decline of GameStop's share price.
## Repository Structure
The repository contains the following files:<br />
* `stock_market_data_scraper.ipynb`  : A Jupyter Notebook containing the complete code for the project.
* `Tesla.html`  : An html file containing Tesla gragh.
* `GameStop.html`  : An html file containing GameStop gragh.
* `Tesla.jpg`  : An image file containing Tesla gragh.
* `Gamestop.jpg`  : An image file containing Gamestop gragh.
## Usage Instructions
To use this project, follow these steps:<br />
1. Clone the repository to your local machine or download the ZIP file.
2. Install the necessary Python libraries
3. Open `stock_market_data_scraper.ipynb` in a Python IDE or Jupyter Notebook environment.
4. Execute the code to perform the data extraction, web scraping, and plotting processes.
## Conclusion
This stock market web scraping project demonstrates the power of Python in extracting and analyzing financial data. By utilizing the yfinance API and web scraping techniques, the project provides valuable insights into the dynamics of stock prices and revenue trends. The created graphs facilitate a better understanding of the relationship between stock prices, company profitability, and external factors such as investor actions.
