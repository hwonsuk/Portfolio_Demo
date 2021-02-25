# Portfolio Construction and Visualization
As part of my graduate research, I needed a way to quickly construct portfolios and measure their performance in the context of stress events. To do so, I prepared some python modules, which allow for easy portfolio construction, optimization, and visualization. The jupyter notebook includes a quick demonstration. As a work in progress, there are lots of room for improvement and I will continue to add to this project (including an interactive component and additional performance metrics). 

### What I have so far:
The table below includes performance metrics like annualized return, volatility, and maximum drawdown for selected portfolios. If a benchmark is provided, additional metrics like tracking error, and beta are also calculated.
<p align='center'>
<img width="250" alt="Table" src="https://user-images.githubusercontent.com/60523841/109075042-97f5c280-76c6-11eb-9647-a343ade8fe97.png">
</p>

The plots below visualize portfolio performance. The upper left plot shows cumulative returns for portfolios and a benchmark if provided. The upper right plot shows annualized return over volatility for portfolios with markersize corresponding to sharpe ratio. The lower left plot depicts drawdowns with maximum drawdown marked. The lower right includes a heatmap of correlations of returns.
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074863-51a06380-76c6-11eb-8920-63aa9bc723d2.png' width='800'>
</p>

Calendar heatmaps of monthly returns could also be helpful in evaluating and comparing portfolios. Calendar heatmaps for two sample portfolios (Cen. Vol and Per. Vol) are shown below. 
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074862-51a06380-76c6-11eb-8100-97e8332a2e22.png' width='420'>
</p>

The plots below visualize portfolio composition. The plot on the left shows top n weighted assets in a portfolio (Per. Vol), while the plot on the right shows weighted sector makeup.
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074859-5107cd00-76c6-11eb-8671-90f1c4c229c2.png' width='800'>
</p>

It could also be informative to check the performance of top weighted assets. The plot below shows cumulative returns for top n weighted stocks in two sample portfolios (Cen. Vol and Per. Vol). This plot could be improved to reflect allocation size with linewidth.
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074865-51a06380-76c6-11eb-940a-80e5df737ccc.png' width='800'>
</p>

In addition to cumulative returns, it could be helpful to visualize annualized return over volatility for select stocks. Below, n stocks with the highest sharpe ratios are shown for two sample portfolios (Cen. Equal and Per. Equal). 
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074858-5107cd00-76c6-11eb-83ae-945f21787db7.png' width='800'>
</p>

Lastly, mean or median sector metrics like return or volatility could be helpful in evaluating portfolios. The plots below show mean sector return for two sample portfolios (Cen. Equal and Per. Equal).
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/109074861-51a06380-76c6-11eb-9d00-2b05a9c323ba.png' width='800'>
</p>

### Conclusion
My graduate research tested applications of social network analysis in the portfolio construction and allocation process. By having quick ways to visualize and measure the performance of portfolios and their underlying assets, I was able to focus on the theory and practical applications of my work. The portfolio selection process is something I find deeply interesting and hope to work on in the future.
