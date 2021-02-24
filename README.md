# Portfolio Construction and Visualization

As part of my graduate research, I needed a way to quickly construct portfolios and measure their performance in the context of stress events. To do so, I prepared some python modules, which allow for easy portfolio construction, optimization, and visualization. The jupyter notebook includes a quick demonstration. As a work in progress, there are lots of room for improvement and I will continue to add to this project (including an interactive component and additional performance metrics). 

### What I have so far:
The table below includes performance metrics like annualized return, volatility, and maximum drawdown for selected portfolio(s). If a benchmark is provided, additional metrics like tracking error, and beta are also calculated.
<p align='center'>
<img width="250" alt="Table" src="https://user-images.githubusercontent.com/60523841/109075042-97f5c280-76c6-11eb-9647-a343ade8fe97.png">
</p>

Portfolio performance is visualized below. The upper left plot shows cumulative returns for portfolio(s) and benchmark if provided. The upper right plot shows annualized return over volatility for portfolio(s) with markersize corresponding to sharpe ratio. The lower left plot depicts drawdowns with maximum drawdown marked. The lower right shows a heatmap of correlation(s).
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074863-51a06380-76c6-11eb-8920-63aa9bc723d2.png' width='800'>
</p>

Below is a calendar heatmap of monthly portfolio returns. 
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074862-51a06380-76c6-11eb-8100-97e8332a2e22.png' height='420'>
</p>

N assets in portfolio(s).
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074858-5107cd00-76c6-11eb-83ae-945f21787db7.png'>
</p>

Sector Distribution
<p align='center'>
<img width="810" alt="Sector_Distribution" src="https://user-images.githubusercontent.com/60523841/109074859-5107cd00-76c6-11eb-8671-90f1c4c229c2.png">
</p>

sector metric
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074861-51a06380-76c6-11eb-9d00-2b05a9c323ba.png'>
</p>

top ws
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074865-51a06380-76c6-11eb-940a-80e5df737ccc.png'>
</p>
