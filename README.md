# B404B Computational Finance Project

## Introduction
This repository contains the work for the "B404B Computational Finance" course. Our project focuses on developing and analyzing an automated trading strategy using historical stock data. The submission date for this project was June 26, 2022.

## Table of Contents
1. [Setup and Import Data](#setup-and-import-data)
2. [Definition of Signals](#definition-of-signals)
3. [Computation of Signals and Stock Positions](#computation-of-signals-and-stock-positions)
4. [Resulting Statistics from the Employed Strategy](#resulting-statistics-from-the-employed-strategy)
5. [Graphs of Strategy](#graphs-of-strategy)
6. [Additional Considerations](#additional-considerations)

## Setup and Import Data
To run the code in this project, you need a Python environment with certain libraries installed. Key libraries include `numpy`, `pandas`, `matplotlib`, `pandas_datareader`, `scipy`, and `seaborn`. You can install these packages using pip:
```bash
pip install numpy pandas matplotlib pandas_datareader scipy seaborn
```

## Data Sources and Import

The project utilizes historical stock data, specifically closing prices and price changes for selected stocks and the S&P 500 index. The data is sourced from Yahoo Finance. The code includes a detailed procedure for downloading and preparing this data for analysis.

## Methodology and Approach

Our approach involves several key steps:

- **Defining Trading Signals**: We establish criteria for buying or selling stocks based on financial data trends.
- **Signal Computation and Stock Positioning**: The signals are computed using historical data, which then dictate our stock positioning.
- **Strategy Implementation**: We apply these signals to historical data to simulate an automated trading strategy.

The first trading signal conists of the *MACD* and an *Ichimoku Cloud*

![Signal 1](/Signal_1.png "MACD and Ichimoku Cloud")

The second trading signal includes the *RSI* and a *flashing indicator*

![Signal 2](/Signal_2.png "RSI and flashing Indicator")

The third trading signal uses a *Trading Breakout* and a *Dynamic Momentum Index*

![Signal 3](/Signal_3.png "Trading Breakout and Dynamic Momentum Index")

## Results and Analysis

The notebook includes a comprehensive analysis of the trading strategy's performance. This includes statistical analysis and various graphs that visualize the strategy's effectiveness over time.

Some of Analysis Results are depicted in the following graphs.

![Jensen's Alpha](/Jensens_Alpha.png "Jensen's Alpha")

![Sharpe ratio](/Sharpe_ratio.png "Sharpe Ratio")

## Additional Considerations

We further discuss additional factors that impact the performance of our trading strategy, including market volatility, transaction costs, and other real-world considerations.

## References and Acknowledgements

This project is a collaborative effort as part of the B404B Computational Finance course. We thank our course instructors and peers for their invaluable input and feedback.
