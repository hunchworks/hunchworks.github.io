---
layout: post
title: "Market Neutral Statistical Arbitrage"
date: 2015-05-07 15:21:22 +0530
comments: true
categories: [Kalman Filtering, Statistical Arbitrage]
---

The figure shows the profit/loss on a Rs.10,00,000 investment for the period March 1, 2014 to May 6, 2015 - a period of about 14 months (281 trading days) - using a (modified) Kalman Filter based market neutral statistical arbitrage strategy on stocks listed on the National Stock Exchange (NSE), India. These returns are not compounded - that is, the profits gained are not fed back into the strategy - the investment is a constant Rs.10,00,000.

{% img /images/statarbreturns.png %}

During the same period, the CNX NIFTY index went from 6526 to 8090 - a gain of about 24%. Assuming a return of 8.5% on a risk-free fixed deposit during the period, the sharpe ratio of the strategy turns out to be ~2.9, with an annual return of ~140+%.

Note however, that all's not rosy during the period. The maximum drawdown during the period was ~28% - which means at some point, the strategy lost around Rs.2,80,000 from a previous peak. 

And of course, as always, past returns are not an indication of future returns!
