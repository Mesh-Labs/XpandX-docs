# Oracle

XpandX's concentrated liquidity pool serves as an oracle, providing external developers and platforms with access to liquidity data and historical prices. This offers a new option within the DeFi ecosystem, alongside traditional oracles that rely on off-chain data. The price and data provided by XpandX's oracle are determined by real buyers and sellers in the market.

The historical data is stored as a series of observations, with the pool continuously updating the latest observation as new blocks are confirmed. The transaction fees paid by users determine how far back in time the historical data can be accessed.

By storing the price and historical data in the pool's smart contract, the risk of errors and the integration cost associated with oracles are significantly reduced. Additionally, it becomes more challenging for any attempts at manipulating the oracle's price.

When making an "observe" call, the caller specifies an array indicating the desired time intervals in seconds ago to retrieve observations from. It's important to note that each specified time must be more recent or as old as the oldest stored observation.

{% hint style="info" %}
The XpandX Protocol is currently under development, and we are working on providing an Oracle for external use in the near future.
{% endhint %}
