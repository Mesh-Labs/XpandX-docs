# Fees

### Swap Fees[​](https://docs.uniswap.org/concepts/protocol/fees#swap-fees) <a href="#swap-fees" id="swap-fees"></a>

When you make a swap, the fees associated with that swap are distributed proportionally among all the liquidity within the specified price range at the time of the swap. It's important to note that if the spot price moves outside of a position's range, the liquidity within that range becomes inactive and does not generate any fees. However, if the spot price moves back into the position's range, the liquidity becomes active again and starts generating fees once more.

Swap fees are collected separately from the pool. If you want to collect your fees, you will need to manually redeem them at the appropriate time.\


### Fee Tiers

We have the ability to create multiple pools for the same token pair, each with different fee levels. Initially, there are four fee tiers available: 0.01%, 0.05%, 0.25%, and 1%.

Having multiple fee tiers allows us to cater to the diverse needs of different trading pairs. It also encourages the market to naturally find the most suitable liquidity distribution strategy on its own. This flexibility benefits both liquidity providers and traders.

It's reasonable to expect that different types of token pairs will gravitate towards specific fee levels based on their unique characteristics and the interplay between supply and demand from liquidity providers and traders. Stablecoins, which have low volatility, are likely to be more commonly found in pools with the lowest fee tier. This is because LPs find it less risky to hold stablecoins, and most traders expect their transactions to be executed at a 1:1 ratio. On the other hand, assets that are less frequently traded may lean towards higher fee tiers, as liquidity providers take on greater risks in holding such highly volatile assets.

### Protocol Fees

In order to ensure a sustainable project treasury for the long-term development of the project, a portion of the swap fees from each transaction on XpandX (by default, 5%) will be allocated as the protocol fee. The 20% of protocol fee will be distributed to the XpandX tokenholders.&#x20;

&#x20;
