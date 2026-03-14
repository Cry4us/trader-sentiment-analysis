Trader Behavior Analysis Using Market Sentiment
Project Overview

This project analyzes how cryptocurrency trader behavior and profitability relate to overall market sentiment using the Fear & Greed Index. By combining historical trading data with market sentiment indicators, the goal is to identify patterns in trader activity, profitability, and market behavior. The analysis explores whether market sentiment influences trading decisions and outcomes.

Dataset Description

Two datasets were used in this analysis:

**1. Trader Historical Data**
Contains detailed records of cryptocurrency trades, including:

* Trader account
* Coin traded
* Execution price
* Trade size (tokens and USD)
* Trade side (Buy/Sell)
* Closed profit and loss (PnL)
* Fees
* Timestamp of trade

**2. Fear & Greed Index**
Provides daily market sentiment classification based on market conditions.
Sentiment categories include:

* Fear
* Neutral
* Greed
* Extreme Greed

The datasets were merged using the trade date to align each trade with the corresponding market sentiment.

## Methodology

The analysis was conducted using the following steps:

1. **Data Cleaning**

   * Removed duplicate records.
   * Converted timestamps into datetime format.
   * Extracted trade dates for dataset merging.

2. **Dataset Integration**

   * Merged trading data with the sentiment dataset using the trade date.

3. **Feature Exploration**

   * Analyzed trading volume, profit distribution, and trader activity.
   * Calculated metrics such as trader win rates and coin profitability.

4. **Exploratory Data Analysis**

   * Visualized sentiment distribution across trades.
   * Examined profit distribution and trade size relationships.
   * Investigated how profitability changes under different sentiment conditions.

5. **Result Export**

   * Generated charts and aggregated tables to summarize findings.

## Key Insights

**Market Sentiment Trends**

* A large proportion of trades occurred during **Greed and Extreme Greed** market conditions.
* Trading activity tends to increase when market sentiment is positive.

**Profitability Patterns**

* Profit distribution shows high variability, indicating both large gains and losses.
* Larger trades often correspond to larger profit or loss swings.

**Coin-Level Insights**

* Certain coins dominate overall trading volume and cumulative profitability.
* Profitability is not evenly distributed across all traded assets.

**Trader Behavior**

* A small subset of traders executes a significant portion of total trades.
* Win rates vary significantly between traders, suggesting differences in strategy and risk tolerance.

## Strategy Recommendations

**1. Sentiment-Aware Trading**

* Traders should monitor market sentiment indicators when making trading decisions.
* Extremely positive sentiment may indicate overheated markets and higher volatility.

**2. Risk Management**

* Large position sizes should be managed carefully due to increased exposure to price fluctuations.
* Implement stop-loss strategies to limit downside risk.

**3. Diversification**

* Avoid concentrating trades on a single coin.
* Diversification across assets can reduce exposure to sudden market shifts.

**4. Behavioral Awareness**

* Traders should avoid herd behavior during extreme sentiment phases.
* Independent strategy evaluation can lead to more consistent trading outcomes.

## Conclusion

This analysis demonstrates that market sentiment plays an important role in influencing trading activity and behavior. By integrating sentiment indicators with trading data, traders and analysts can gain deeper insights into market dynamics and develop more informed trading strategies.
