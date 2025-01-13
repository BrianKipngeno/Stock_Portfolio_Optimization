# Stock_Portfolio_Optimization

Stock market portfolio optimization is a systematic approach to selecting the best combination of stocks to maximize returns while minimizing risk. This project utilizes historical performance data and financial metrics to create an efficient portfolio based on Modern Portfolio Theory (MPT). The aim is to strike an optimal balance between risk and reward for long-term investment success.

# 📁 Project Overview

This project involves:

   - Analyzing price trends to uncover market patterns.
   - Calculating expected returns and volatilities for individual stocks.
   - Determining correlations between stocks to explore diversification opportunities.
   - Constructing an efficient portfolio using MPT to identify the best risk-reward tradeoff.
   - Evaluating portfolios using the Sharpe ratio to identify optimal allocations for long-term investment goals.
# Research Problem

**Objective:**

To develop a portfolio optimization strategy using stock market data.

**Dataset:**

Stock Market Data :  https://bit.ly/stock_data

# Key Steps

1. Identifying trends in stock prices using technical indicators like moving averages.
   
2. Calculating financial metrics such as volatility, risk, and expected returns.
 
3. Assessing correlations between stocks for diversification.
   
4. Constructing a portfolio that maximizes the Sharpe ratio, providing the best risk-adjusted returns.


# 📊 Key Findings

1. **Stock Price Trends:**

    - Stocks analyzed: HDFCBANK, INFY, RELIANCE, TCS.
    - RELIANCE and TCS exhibit strong upward trends, while INFY and HDFCBANK show more stability.
      
2. **Volatility and returns**
   
    - RELIANCE has the highest expected return (29.73%) but moderate risk (21.47%).
    - INFY and TCS offer competitive returns with moderate volatility.
    - HDFCBANK has the lowest return (1.37%) and moderate risk.

3. **Correlations**
   
    - INFY and TCS show high correlation, indicating similar price movements.

    - RELIANCE and HDFCBANK have moderate to low correlations with others, suggesting diversification benefits.

4. **Portfolio Analysis**
   
    - Compared the risk and expected returns of the mutual fund portfolio to high-growth companies.

    - Visualized trade-offs between risk and reward for different stock groups.

5. **Efficient Portfolio Construction:**

    - Random portfolios were generated to evaluate risk and return profiles.

    - The portfolio with the maximum Sharpe ratio was identified as the optimal choice.

# 🔧 Technologies Used

**Python**: Data analysis and visualization.

**Libraries**:

- pandas and numpy for data manipulation.
- matplotlib and seaborn for static visualizations.
- plotly for interactive visualizations.

# 📈 Features and Insights
1. **Price Trends Visualization**
   - Moving averages (50-day, 200-day) were computed to highlight long-term and short-term trends.
   - Graphs reveal consistent growth patterns in RELIANCE and TCS.
2. **Risk-Return Metrics**
   - **Expected Return**: The annualized mean of daily returns.
   - **Volatility:** The annualized standard deviation of daily returns.
   - These metrics form the foundation for portfolio optimization.
3. **Diversification Analysis**
   - A correlation heatmap highlights relationships between stocks.
   - Low correlations between some stocks indicate potential for risk reduction through diversification.
4. **Sharpe Ratio Optimization**
   - The Sharpe ratio evaluates risk-adjusted returns, helping select the most efficient portfolio.


# 🚀 Expected results

1. A portfolio with optimal weights for each stock to achieve the maximum Sharpe ratio.
2. Clear recommendations for constructing a diversified portfolio with balanced risk and return.
3. Insights into market behaviors and strategies for long-term investment success.

# 📂 Conclussion
This project demonstrates the power of financial data analysis and optimization techniques in crafting investment strategies. 

By leveraging historical data and statistical methods, we aim to empower investors to make informed, data-driven decisions that align with their financial goals.

# 🛠️ Future Improvements

1. Expand the analysis to include more stocks or other asset classes.
2. Explore alternative optimization techniques such as Black-Litterman or Monte Carlo simulations.
3. Incorporate live data feeds for real-time portfolio adjustments.

# 📬 Contact
For questions or collaboration opportunities, feel free to reach out:

Author: Brian Kipngeno

Email: briankosgey@gmail.com
