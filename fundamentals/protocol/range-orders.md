# Range Orders

By creating a liquidity position and setting a specific price range relative to the spot price, liquidity providers (LPs) can offer liquidity with a single-sided asset. This allows them to simulate limit orders commonly seen in traditional orderbook markets or centralized exchanges (CEX). The main difference is that a limit order has a predetermined buy or sell price and may be executed in the future, while a single-sided liquidity position order in the concentrated liquidity protocol comes with a price range.

When the spot price enters the predetermined range of a liquidity position, continuous token swapping occurs within that position. If the price fully surpasses the price range, all original assets are exchanged for the target assets, which can then be withdrawn by the LP to close the order. This order mode is known as "range orders."

In this case, liquidity providers, not swappers, act as makers and earn fees when a range order is executed. By strategically creating liquidity positions, LPs can take advantage of market dips and rallies like professional traders, while also earning transaction fees.

### &#x20;<a href="#possibilities-of-range-orders" id="possibilities-of-range-orders"></a>

