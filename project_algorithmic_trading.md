## Algorithmic Trading for Gold and Gold Miner ETFs

Note: project is in progress!

### Project Overview
The goal of this algorithmic trading experiment is to predict (or provide strong signals for) buying and selling points in the UGL stock based on gold miner ETFs. My dad and I worked on this project together; he pinpointed the relationship between the ETFs, while I built the algorithm from scratch and streamlined the predicting process using Python. So far, our algorithm does a better job showing signals for buying points than selling points.

### Results

Comparing 3 different strategies over a period of 13 years:
- Buy and Hold (139.04% gain)
- Momentum Investing with Reference to Gold Miner ETF (705.71% gain)
- Momentum Investing with 50-Day SMA and 200-Day SMA (267.68% gain)

<img src="images/Total Assets Owned Over Time v2.png?raw=true"/>

To identify the highest-gaining buy and sell signal values for the indicator my dad and I theorized, I plotted a 3D visual:
<img src="images/Strategy Involving GDX buy and sell thresholds.png?raw=true"/>

Stay tuned for more concrete results!
