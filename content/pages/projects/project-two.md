---
type: ProjectLayout
title: Yahoo Finance Stock Analytics Dashboard
colors: colors-a
date: '2025-03-20'
client: ''
description: ''
media:
  type: VideoBlock
  title: Title of the video
  url: ''
  elementId: ''
  autoplay: false
  loop: false
  muted: false
  controls: true
  aspectRatio: '16:9'
featuredImage:
  type: ImageBlock
  url: /images/twitter-yahoo-finance-python.jpg
  altText: ''
  caption: ''
  elementId: ''
---
The **Stock Analytics Dashboard** is a comprehensive tool built using Streamlit, designed to provide users with a wide range of stock market analysis capabilities. From fundamental and technical analysis to portfolio simulation and optimization, this dashboard is a one-stop solution for investors and traders looking to make data-driven decisions.

## [Demo Video](https://youtu.be/qGxx_UxXFOo?si=-ytF-qxe0LXk18zL)

[Medium Post](https://medium.com/@phanm48/data-to-dollars-an-enthusiasts-journey-into-data-driven-finance-4cec9251d000)

## Features

### Fundamental & Technical Analysis

*   **Key Financial Indicators:** View essential metrics such as P/E Ratio, EPS, P/B Ratio, Debt-to-Equity Ratio, and Return on Equity (ROE).
*   **Estimated Stock Price:** Calculate the estimated stock price based on EPS and P/E Ratio.
*   **Stock Price with Moving Averages:** Visualize stock prices with 20-day and 50-day Simple Moving Averages (SMA).
*   **RSI Indicator:** Analyze the Relative Strength Index (RSI) to gauge momentum.
*   **Dividend History:** Explore dividend payouts over time with interactive visualizations.

![](/images/demo%201.png)![](/images/demo%202.png)

### Portfolio Simulation (Equal Weighted Method)

*   **Portfolio Performance:** Track the cumulative returns of a portfolio with equal-weighted assets.
*   **Correlation Heatmap:** Visualize the correlation between assets in the portfolio.
*   **Portfolio Metrics:** Calculate key metrics such as average annual return, Sharpe Ratio, Treynor Ratio, and Information Ratio.
*   **Comparison to S\&P 500:** Benchmark your portfolio's performance against the S\&P 500.

![](/images/demo%203.png)![](/images/demo%204.png) 

### LSTM Prediction (Demo)

*   **Stock Price Prediction:** Use Long Short-Term Memory (LSTM) neural networks to predict future stock prices.
*   **Model Customization:** Adjust model parameters such as look-back period, epochs, batch size, and LSTM layers.
*   **Performance Metrics:** Evaluate the model's performance using R² Score, MAPE, and Accuracy Rate.

![](/images/demo%205.png)

### Portfolio Optimization

*   **Optimal Asset Allocation:** Maximize the Sharpe ratio to find the best risk-adjusted portfolio.
*   **Risk-Free Rate Adjustment:** Set a custom risk-free rate for optimization.
*   **Portfolio Setup:** Input your budget and number of shares to calculate initial portfolio weights.
*   **Optimization Results:** View optimized portfolio weights, expected annual return, annual volatility, and Sharpe ratio.
*   **Visualizations:** Explore portfolio allocation through bar charts and pie charts.

![](/images/demo%206.png) ![](/images/demo%207.png)![](/images/demo%208.png)

## 📖 Usage

**Select Analysis Type:**\
Choose from **Fundamental & Technical Analysis, Portfolio Simulation, LSTM Prediction,** or **Portfolio Optimization** in the sidebar.

**Input Stock Ticker(s):**

*   For individual stock analysis, enter the stock ticker (e.g., `AAPL`).
*   For portfolio analysis, enter multiple tickers separated by commas (e.g., `AAPL,MSFT,GOOGL`).

**Customize Parameters:**Adjust model parameters, time periods, and other settings as needed.

**View Results:** Explore the **interactive visualizations** and **metrics** provided by the dashboard.

***

## Dependencies

The Stock Analytics Dashboard relies on the following Python libraries:

*   [**Streamlit**](https://streamlit.io/)**:** For building the web app interface.
*   [**yfinance**](https://pypi.org/project/yfinance/)**:** For fetching stock market data.
*   [**NumPy**](https://numpy.org/)**:** For numerical computations.
*   [**Pandas**](https://pandas.pydata.org/)**:** For data manipulation and analysis.
*   [**Plotly**](https://plotly.com/python/)**:** For interactive visualizations.
*   [**scikit-learn**](https://scikit-learn.org/)**:** For data scaling and performance metrics.
*   [**TensorFlow/Keras**](https://www.tensorflow.org/)**:** For LSTM-based stock price prediction.
*   [**SciPy**](https://scipy.org/)**:** For portfolio optimization.

***

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1️⃣ **Fork** the repository.\
2️⃣ **Create** a new branch for your feature or bug fix.\
3️⃣ **Commit** your changes.\
4️⃣ **Submit** a **pull request**.

***

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

***

## Acknowledgments

*   [**Streamlit**](https://streamlit.io/)**:** For making it easy to build and share data apps.
*   [**yfinance**](https://pypi.org/project/yfinance/)**:** For providing easy access to stock market data.
*   [**Plotly**](https://plotly.com/python/)**:** For creating beautiful and interactive visualizations.

***

## Contact

For any questions or feedback, feel free to reach out:

📧 **Email:** <mphan1@babson.edu>

***

Happy Analyzing! 📈
