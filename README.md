# 📊 Stock Portfolio Analyzer

## Overview

The **Stock Portfolio Analyzer** is a Python tool that connects to the **Trading 212 API** to fetch and analyze your portfolio. It then uses **Yahoo Finance** data to evaluate each stock's **intrinsic value**, **analyst target price**, and **sector comparison**. The tool identifies the most undervalued stocks in your portfolio, providing you with valuable insights to help inform your investment decisions.

## Key Features

- **Portfolio Analysis**: Automatically fetches your Trading 212 portfolio and retrieves real-time data from Yahoo Finance.
- **Undervalued Stocks**: Identifies the most undervalued stocks based on intrinsic value calculations and analyst targets.
- **Visual Overview**: Includes visualizations that compare **current price** vs **target price** and the **price-to-intrinsic value ratio** for the entire portfolio.
- **Top 10 Undervalued Stocks**: Displays a table of the top 10 stocks in your portfolio with the highest **upside potential**.

## Challenges Faced

Working with the **Trading 212 API** was a learning experience. It was my first time handling API keys, and I faced some issues with **incorrect tickers** not matching the expected format. I also had to clean and map several tickers manually to ensure accuracy, especially for stocks with different regional suffixes or mergers (e.g., Facebook to Meta, Oaktree Acquisition to Hims & Hers Health).

## Visualizations

The tool generates the following charts:
1. **Current Price vs Analyst Target Price**: A bar chart that shows the current market price of each stock compared to its analyst target price.
2. **Price to Intrinsic Value Ratio**: A bar chart that visualizes how each stock’s current price compares to its calculated intrinsic value, with a red line indicating fair value (ratio = 1).

These charts give an **overview of your entire portfolio**, highlighting the relative valuation of each stock. 

## Table of Recommendations

Along with the visualizations, the tool presents a **table** of the **top 10 undervalued stocks**, ranked by their **upside potential** (calculated as the difference between current price and target price). This table helps you quickly spot opportunities for investment.

## Potential Improvements

- **Integration with Other Brokerages**: Currently, the tool only supports Trading 212. Future improvements could include adding integrations with other brokerage APIs (e.g., Robinhood, E*TRADE) to support a wider range of users.
- **More Detailed Portfolio Analysis**: The current analysis focuses on individual stocks. There’s potential to expand this to include more comprehensive portfolio analysis, such as **diversification metrics**, **risk analysis**, and **performance tracking** over time.


