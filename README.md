# Optiver: Trading at the Close

Link To The Kaggle Dataset: <a href="https://www.kaggle.com/competitions/optiver-trading-at-the-close/data">Optiver Dataset</a>

# Problem Statement

Stock exchanges are fast-paced, high-stakes environments where every second counts. The intensity escalates as the trading day approaches its end, peaking in the critical final ten minutes. These moments, often characterised by heightened volatility and rapid price fluctuations, play a pivotal role in shaping the global economic narrative for the day. Each trading day on the Nasdaq Stock Exchange concludes with the Nasdaq Closing Cross auction. This process establishes the official closing prices for securities listed on the exchange. These closing prices serve as key indicators for investors, analysts and other market participants in evaluating the performance of individual securities and the market as a whole. Within this complex financial landscape operates Optiver, a leading global electronic market maker. Fueled by technological innovation, Optiver trades a vast array of financial instruments, such as derivatives, cash equities, ETFs, bonds, and foreign currencies, offering competitive, two-sided prices for thousands of these instruments on major exchanges worldwide.

In the last ten minutes of the Nasdaq exchange trading session, market makers like Optiver merge traditional order book data with auction book data. This ability to consolidate information from both sources is critical for providing the best prices to all market participants. The challenge is to develop a model capable of predicting the closing price movements for hundreds of Nasdaq listed stocks using data from the order book and the closing auction of the stock. Information from the auction can be used to adjust prices, assess supply and demand dynamics, and identify trading opportunities.

Successful modelling can contribute to the consolidation of signals from the auction and order book, leading to improved market efficiency and accessibility, particularly during the intense final ten minutes of trading. 

# The Metric: MAE
The mean absolute error (MAE) is defined mathematically as 

<img src="https://github.com/UKVeteran/Optiver-Trading-at-the-Close/assets/39216339/7825c248-271e-4c73-aaf2-245630967142" width="800" height="400">

and can be visualized 

<p align="center">
<img src="https://github.com/UKVeteran/Optiver-Trading-at-the-Close/assets/39216339/129e9167-7c70-428c-a341-ff2c4561163b" width="400" height="300"></p>
