# marobot
Trading Bot for Crypto Currencies

1. Setting Goal and Strategy:
- Trading Strategy > Momentum Trading
- Objectives > primarily learning but slight profits are highly welcome 
- Which crypto currencies > defined by volatility (acc to strategy)
- Timeframe > defined by API fee
- Frequencies (Requests) > see latter
- Risk tolerance > high af

2. Choice of Development Environment:
- Python

3. Cryptocurrency Exchange and Data Extraction:
- Collection of data and prices from various cryptocurrency exchanges
- Selection of a cryptocurrency exchange
- Use of APIs to obtain real-time market data and historical price data

4. Bot Programming:
- Development of the trading bot in accordance with the strategy
- Implementation of logic for identifying trade signals, placing orders with consideration of risk management

5. Backtesting:
- Testing the strategy on historical data to assess performance and profitability

6. Demo Account:
- Use of a demo account to test the bot under real market conditions without risking real money

7. Live Trading:
- If satisfied with the results of backtesting and demo trading, live implementation
- Monitoring and ensuring risk management during live trading

1. Strategy 

Trend Following Strategy: A bot can aim to identify trends based on price movements and trade in the direction of the trend. When the bot recognises an uptrend developing, it could buy, and when a downtrend is forming, it could sell
- based on which frequency?

Arbitrage Strategy: Arbitrage bots look for price differences between different exchanges or trading pairs. They buy on the exchange where the price is lower and sell on the exchange where the price is higher to profit from the price difference
- not feasible

Pairs Trading: In this strategy, two correlated assets are compared, and the bot trades when their prices diverge. The bot buys one asset and sells the other when the price difference reaches a certain threshold
- do correlations exists in cryptocurrencies? doubtful

Momentum Strategy: A bot implementing a momentum strategy trades based on short-term price movements. For example, it may buy when an asset has risen significantly in a short period, hoping to profit from further upside potential
- frequency? and may profits of short term buying and selling result in profits? order fees have to be considered

Scalping Strategy: Scalping bots aim to make small profits from quick, short-term price movements. They open and close positions rapidly, attempting to profit from small price fluctuations
- same as the latter strategy

Reversion to the Mean: This strategy is based on the assumption that the price of an asset tends to revert to an average value. The bot buys when the price is below average and sells when the price is above average
- how to define that mean? on which period? crypto market may be too volatile for that approach

Sentiment Analysis: A bot can be programmed to trade based on news, social media, or sentiment indicators. When positive news about an asset emerges, the bot may buy, and it may sell on negative news
- have to be evaluated if feasible as API fees for X and Reddit increased heavily

Automated DCA Strategy: A Dollar-Cost Averaging (DCA) bot regularly buys a fixed amount of an asset, regardless of the current price. This is a long-term strategy aimed at reducing volatility
- boring strategy
