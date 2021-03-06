# Portfolio Manager
<b>Current and history prices of assets in portfolio, visualization of assets distribution, rebalancing, trendlines and assets correlation</b><br><br>
**Rendered notebook:**<br>
https://nbviewer.org/github/Teshimoz/portfolio_manager/blob/94fe8866d3d11b06d81382ee3dbcbd35387f4f14/portfolio_manager.ipynb
<br>
<br>
**Project description:**
<br>
In this project we will observe one porfolio, it's asset's current values and changes during last year. Important to mention that it's passive invested portfolio. <br>Will make a calculations for rebalancing, will visualize current state and last year prices vs target proportion. <br>Also will make some extrapolations, keeping in mind all the limitations of this approach in stock market predictions.<br>
As a result will see how much to buy/sell to keep the portfolio balanced and maybe will know when to do it.

Project contains:
* Web scraping for current assets prices
* Rebalancing calculations
* Visualization of current assets value distribution vs target portfolio proportion
* Web scraping for history prices
* Visualizations of portfolio values distribution over last year, absolute and normalized
* Extrapolation of history data (for general possible trend)
* Checking the correlation matrix of portfolio

Used: BeautifulSoup, pandas, matplotlib+seaborn, bidi for text encoding, sklearn for LinearRegression.
