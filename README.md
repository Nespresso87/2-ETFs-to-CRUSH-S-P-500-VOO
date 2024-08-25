Introduction
In-depth analysis of a portfolio strategy that combines two prominent Exchange Traded Funds (ETFs): the Vanguard High Dividend Yield ETF (VYM) and the Vanguard Growth ETF (VUG). The strategy allocates 50% of the portfolio to each ETF, with the goal of achieving a balance between growth and income. This post compares the performance of this strategy against the S&P 500, tracked by the SPDR S&P 500 ETF Trust (SPY), from 2015 to 2025.

Portfolio Composition
The portfolio under analysis is constructed as follows:

50% in VYM (Vanguard High Dividend Yield ETF): This ETF focuses on companies with high dividend yields, providing a steady income stream.
50% in VUG (Vanguard Growth ETF): This ETF targets companies with strong growth potential, emphasizing capital appreciation.
Performance Analysis
Cumulative Returns vs. Benchmark
Two cumulative return graphs are presented—one with standard scaling and another with logarithmic scaling—to provide a comprehensive view of the strategy's performance compared to the benchmark.

Yellow Line (SPY): Represents the cumulative return of the S&P 500.
Blue Line (Strategy): Represents the cumulative return of the portfolio strategy (50% VYM, 50% VUG).
The strategy has consistently outperformed the S&P 500, especially from 2020 onwards. The log-scaled graph confirms that this outperformance is robust across different periods, accounting for exponential growth differences.

Key Performance Metrics
The table on the right side of the graphs provides key performance metrics that offer deeper insights into the strategy’s risk and return profile compared to the S&P 500.

CAGR (Compound Annual Growth Rate): The strategy's CAGR is 9.17%, higher than SPY's 7.39%, indicating stronger growth over the period.
Sharpe Ratio: The strategy’s Sharpe Ratio of 0.78 is better than SPY's 0.67, reflecting superior risk-adjusted returns.
Volatility (ann.): The strategy exhibits slightly higher annualized volatility at 18.61% versus 17.7% for SPY, suggesting marginally higher risk.
Max Drawdown: The strategy experienced a maximum drawdown of -32.61%, which is less severe than SPY's -34.1%, demonstrating better downside protection.
Volatility Matched Returns
The volatility-matched returns graph adjusts for the differences in risk between the strategy and SPY. Even when volatility is normalized, the strategy continues to outperform SPY, reinforcing the robustness of the portfolio's performance.

End-of-Year (EOY) Returns vs. Benchmark
This bar chart compares the yearly returns of the strategy and SPY from 2015 to 2025. The strategy consistently outperforms SPY in several years, particularly in 2021, where it delivers significant excess returns.

Distribution of Monthly Returns
The histogram shows the distribution of monthly returns for the strategy versus SPY. The strategy has a wider distribution, implying a greater range of monthly gains and losses, but it also has a higher central tendency, indicating better overall performance.

Additional Performance Metrics
Here are some additional metrics that further illustrate the strategy's performance:

Sortino Ratio: The strategy has a higher Sortino ratio, indicating better downside risk management.
Max Consecutive Wins and Losses: The strategy exhibits slightly fewer consecutive wins and losses compared to SPY, indicating similar streak patterns.
Calmar Ratio: The strategy’s Calmar ratio is higher than SPY's, suggesting a better return-to-risk profile concerning maximum drawdowns.
Kelly Criterion: The strategy's higher Kelly Criterion implies a more aggressive stance could be taken to maximize returns.
Conclusion
The 50/50 portfolio strategy combining VYM and VUG has demonstrated consistent outperformance against the S&P 500 over the past decade. With a higher CAGR, better Sharpe and Sortino ratios, and slightly higher volatility, this strategy offers an appealing blend of growth and income. While it carries marginally higher risk, the strategy’s superior return profile and drawdown resilience make it a compelling option for long-term investors seeking balanced exposure to both dividend yield and growth.

How to Use This Repository
This repository contains the code used to create the portfolio strategy and generate the performance metrics. You can modify the allocations or ETFs to tailor the analysis to your specific needs. The code leverages the yfinance library for fetching historical data and pandas for data manipulation.

Running the Analysis
Install the required libraries:
Copy code
pip install yfinance pandas matplotlib
Modify the portfolio allocation (if needed) in the tickers dictionary:
python
Copy code
tickers = {
    'VYM': 0.5,  # Vanguard High Dividend Yield ETF
    'VUG': 0.5   # Vanguard Growth ETF
}
Run the analysis using the provided script to generate the performance comparison charts and metrics.
