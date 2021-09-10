## Algorithmic Trading for Gold and Gold Miner ETFs

Note: project is in progress!

### Project Overview
The goal of this algorithmic trading experiment is to predict (or provide strong signals for) buying and selling points in the UGL stock based on gold miner ETFs. My father and I worked on this project together; he pinpointed the relationship between the ETFs, while I built the algorithm from scratch and streamlined the predicting process using Python. So far, our algorithm does a better job showing signals for low (buying) points than high (selling) points.

### Results

Comparing 3 different strategies:
- Buy and Hold
- Momentum Investing with Reference to Gold Miner ETF
- Momentum Investing with 50-Day SMA and 200-Day SMA
<img src="images/Total Assets Owned Over Time v2.png?raw=true"/>

To identify the highest-gaining buy and sell signal values for the indicator my dad and I theorized, I plotted a 3D visual:
<img src="images/Strategy Involving GDX buy and sell thresholds.png?raw=true"/>

Stay tuned for more concrete results!
