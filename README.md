Bluestock Mutual Fund Performance Analytics

The Bluestock Mutual Fund Performance Analytics project is a data analytics and financial analysis project designed to evaluate the performance of 40 mutual fund schemes using historical Net Asset Value (NAV), benchmark indices, Assets Under Management (AUM), and investor transaction data. The project focuses on transforming raw mutual fund data into meaningful financial insights using Python, SQL, and data visualization techniques.

The project begins with collecting and cleaning historical NAV data, benchmark index data, fund details, and transaction records. Missing values, duplicate records, and inconsistent formats are corrected to ensure high-quality data. Daily returns are then calculated for each mutual fund scheme based on changes in NAV over time.

To measure fund performance, several financial metrics are computed, including Compound Annual Growth Rate (CAGR) for 1-year, 3-year, and 5-year periods, Sharpe Ratio for risk-adjusted returns, Sortino Ratio for downside risk evaluation, Alpha and Beta to compare fund performance against market benchmarks, and Maximum Drawdown to identify the largest historical loss experienced by each fund.

A comprehensive Fund Scorecard is developed by combining multiple performance metrics such as long-term returns, Sharpe Ratio, Alpha, expense ratio, and maximum drawdown into a single score ranging from 0 to 100. This score helps rank all mutual funds according to their overall performance and risk profile.

The project also compares the top-performing mutual funds with benchmark indices such as Nifty 50 and Nifty 100 using normalized performance charts. Additionally, Tracking Error is calculated to measure how closely each mutual fund follows its benchmark index.

Interactive and static visualizations are created using Matplotlib and Plotly to display fund performance trends, benchmark comparisons, return distributions, and rankings. The final outputs include a Jupyter Notebook containing the complete analysis, CSV files for the fund scorecard and Alpha-Beta calculations, and benchmark comparison charts.
