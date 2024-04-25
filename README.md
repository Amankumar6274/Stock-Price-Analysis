# Stock Price Analysis and Correlation Study

## Overview

This project aims to analyze the stock prices of major tech companies, including Amazon, Apple, Google, and Microsoft, over the past few years. The analysis includes examining changes in stock prices over time, exploring correlations between different stocks, and investigating relationships between daily changes in closing prices and stock returns.

## Analysis Tasks

### 1. Analyzing Change in Stock Prices Over Time

- Converting the data type of the "date" feature into datetime.
- Considering different rolling windows (e.g., 10 days, 20 days, 30 days).

### 2. Analyzing Closing Price Change in Apple Stock

#### Daily Stock Return Formula

To calculate daily gain or loss for a stock:
\[ \text{Daily Gain or Loss} = (\text{Closing Price} - \text{Opening Price}) \times \text{Number of Shares} \]

Using `pct_change()`:
- Calculate the percentage change between the current and prior closing prices.
- Resample the data on various time bases: yearly ('Y'), quarterly ('Q'), monthly ('M'), weekly ('W'), daily ('D'), minutes ('3T'), etc.

### 3. Correlation Analysis of Stock Prices

- Perform correlation analysis on closing prices of Amazon, Apple, Google, and Microsoft.
- Plot correlation matrices to identify significant relationships between stock prices.
- Conclusions: Google and Microsoft closing prices are well correlated, while Amazon and Microsoft have a correlation of 0.96.

### 4. Analyzing Daily Changes in Closing Prices and Daily Returns

- Use Pairgrid for in-depth analysis:
  - Plot histograms on the diagonal.
  - Plot scatterplots or KDE plots for other combinations.
- Conclusion: There's a linear relationship between AAPL and AMZN daily changes in closing prices, up to some extent.

## Tools Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
## Results

### Results of Stock Price Analysis:

1. **Change in Stock Prices Over Time:**
   - After analyzing the stock prices over different rolling windows (e.g., 10 days, 20 days, 30 days), we observed fluctuations and trends in the prices of Amazon, Apple, Google, and Microsoft.

2. **Closing Price Change in Apple Stock:**
   - Analyzing the closing price change in Apple stock revealed [specific insights or patterns, if any].

3. **Correlation Analysis of Stock Prices:**
   - The correlation analysis showed strong correlations between the closing prices of Google and Microsoft, while Amazon and Microsoft exhibited a correlation coefficient of 0.96, indicating [interpretation of the correlation].

4. **Daily Changes in Closing Prices and Daily Returns:**
   - Using Pairgrid analysis, we observed [specific relationships or patterns] between daily changes in closing prices and daily returns of the stocks.

### Key Conclusions:

- [Summarize the main findings or insights obtained from the analysis].

## Future Work

### Potential Future Enhancements:

1. **Incorporating Additional Features:**
   - Explore incorporating additional features such as trading volume or news sentiment to enhance the analysis and gain deeper insights into stock behavior.

2. **Advanced Statistical Methods:**
   - Implement more advanced statistical methods for correlation analysis to uncover hidden relationships and dependencies between stocks.

3. **Predictive Modeling:**
   - Develop predictive models using the correlated stock prices for forecasting future price movements, enabling better decision-making in trading and investment strategies.

4. **Visualization Techniques:**
   - Explore advanced visualization techniques to visualize higher-dimensional patterns and relationships in the data beyond 2D and 3D plots.

5. **Expansion to Other Markets:**
   - Extend the analysis to include stocks from other markets or sectors to provide a broader perspective on market trends and correlations.

### Future Research Directions:

- [Identify specific research questions or areas of exploration that could be pursued in future analyses].
- [Discuss potential collaborations or partnerships to further enhance the research].



