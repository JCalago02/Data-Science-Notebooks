
# Data-Science-Notebooks

Unified repository for all data science/data intensive visualization/analysis projects conducted

## Table of Contents

1. [Bitcoin Bollinger Band Analysis](#bitcoin-bollinger-band-analysis)
2. [Bitcoin Linear Regression Exploration](#bitcoin-linear-regression-exploration)
3. [Yahoo Finance Basics](#yahoo-finance-basics)


## Bitcoin Bollinger Band Analysis

### File: Bitcoin Bollinger Band Analysis.ipynb

#### Purpose:

The purpose of this notebook was to analyze the performance of the Bollinger Band trading indicator with respect to 20 day PNL in the Bitcoin market. The Bollinger Band technical analysis indicator was constructed onopen source bitcoin pricing data, and using this data, the notebook answers the question "how does the effectiveness of the Bollinger Band indicators vary with different levels of price volatility". 

#### Results:

After producing the relevant plots within the notebook, it can be seen that there seems to be some correlation between the Bollinger Band indicator and price swings, as the prediction of the Bollinger Band had a visible effect on the relative frequencies of the 3 types of price swing conditions (up, down, and sidways). However, very litte interaction was seen between the Bollinger Band indicator and future bitcoin prices. Future analysis into different technical analysis indicators would be needed to compare the effectiveness of the Bollinger Band in tandem with more directional indicators.

## Bitcoin Linear Regression Exploration

### File: Bitcoin Linear Regression Exploration.ipynb

#### Purpose:

In this notebook, I attempted to build a predictive model for Bitcoin 20 day PnL using various technical analysis indicators. The indicators used were Bollinger Bands, the MACD, and the Volume Oscillator, and were manually constructed from an open source bitcoin pricing dataset.

#### Results:

After testing various models with both L1 and L2 normalization, a test $R^2$ of 0.223 was acheived. Because of the z-score normalization, we were able to discern that volatility measures such as the Bollinger Band width brought more predictive power to our model, but due to the low test $R^2$, findings are most likely not indicative of real market mechanics. Future analysis into different combinations of model features would be the best course of action in an effort to increase test $R^2$.

## Yahoo Finance Basics

### File: Yahoo Finance Basics.ipynb

##### Purpose:

This notebook showcased some initial queries to the Yahoo finance API, construction of various portfolios from this data, and some basic analysis using the Sharpe Ratio.

##### Results:

No inquiry was done here, this notebook should mainly be used as a reference point for future inquiry projects that need to use the Yahoo finance API.