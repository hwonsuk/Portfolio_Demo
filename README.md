# Portfolio Construction and Visualization

As part of my graduate research, I needed a way to quickly build and visualize portfolio performance in the context of stress events. To do so, I created Portfolio.py (not included), which allows for easy and flexible portfolio construction, optimization, and visualization. The jupyter notebook shows a quick demonstration of the code. As a work in progress, there are lots of room for improvement and I will continue to add to this project (including an interactive component).

### What I have so far:
The upper left plot shows the cumulative returns for  portfolio(s) and benchmark. The upper right plot is currently empty (possible visualizations are included below). The lower left plot shows drawdowns and the lower right depicts signal-to-noise. 

<p align='center'>
<img src='https://user-images.githubusercontent.com/60523841/105905760-d4af9a80-5ff0-11eb-9688-d0b571daf024.png' width='700'>
</p>

### Possible visualizations for empty plot:
#### Worst/best performing stocks
One option is to include the n worst/best performing stocks in the portfolio by annualized returns.
<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/105905862-f872e080-5ff0-11eb-9c85-b53925157c80.png' width='600'>
</p>

#### Sector distribution
Another is to show the breakdown of sectors in portfolio.

<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/105905893-058fcf80-5ff1-11eb-8962-15832ff26a02.png' width='300'>
</p>

The image below includes an interactive component. When users hover over sectors, additional information like average sector returns can be included.

<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/105906056-3a038b80-5ff1-11eb-9f14-28c0457fe64a.png' width='700'>
</p>

#### Portfolio sharpe ratio
Another visualization for the empty upper right plot is portfolios' sharpe ratios.

<p align='center'>
<img src = 'https://user-images.githubusercontent.com/60523841/105906139-4d165b80-5ff1-11eb-8006-d05a15a80241.png' width='300'>
</p>
