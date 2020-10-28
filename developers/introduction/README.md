---
description: "\U0001F91D Getting to know the mStable protocol"
---

# Introduction

## Resources

### **Contracts**

All contracts are deployed on Mainnet, Ropsten and Kovan. They are open source and available on the GitHub, or as a node package, as specified in the [mStable-protocol page](../integrating-mstable/).

{% page-ref page="../deployed-addresses.md" %}

### Parsing data

See [mStable-js](../mstable-js.md) for more info on ways to retrieve, parse and prepare data for interacting with the core functions.

### Live apps

| Network | App | Subgraph |
| :--- | :--- | :--- |
| Mainnet | [app.mstable.org/](https://app.mstable.org/) | [mstable/mstable-protocol](https://thegraph.com/explorer/subgraph/mstable/mstable-protocol) |
| Ropsten | [app-dot-mstable-ropsten.appspot.com/](http://app-dot-mstable-ropsten.appspot.com/) | [mstable/mstable-protocol-ropsten](https://thegraph.com/explorer/subgraph/mstable/mstable-protocol-ropsten) |
| Kovan | [app-dot-mstable-kovan.appspot.com/](https://app-dot-mstable-kovan.appspot.com/) | [mstable/mstable-protocol-kovan](https://thegraph.com/explorer/subgraph/mstable/mstable-protocol-kovan) |

## Why mStable?

mStable Assets \(mAssets\) are built to be the solid base layer in DeFi. The first mAsset, mUSD, comprises of USDT, TUSD, DAI and USDC. mAssets can be minted with any of the underlying and used as a trustworthy base layer with which to, for example, collateralise synthetic assets or loans. [Read more about mAssets](https://docs.mstable.org/mstable-assets/massets).

mAssets produce a native yield through the SAVE contract. Yield is derived from AMM swap trades and lending markets. Underlying assets can be redeemed at any time. mStable aims to be a foundational layer for DeFi applications.

### Whats sort of stuff can be built? <a id="bb4f"></a>

Essentially anything that **builds on top** of ****or **extends** the ****mStable protocol, or simply utilises mAssets to their potential. We would also welcome any application utilising the system token MTA.

Some ideas to build on top of mStable:

* A no loss lottery \(e.g. PoolTogether\)
* A derivative using mStable SAVE or mUSD \(e.g. CHAI\)
* A derivative using mAssets as the **settlement** **layer**
* Deriving a yield for any application that accepts DAI, USDT, TUSD or USDC
* Utilising mStable MINT/SWAP as part of an trading bot
* Wrapping MINT/SWAP/REDEEM in something \(e.g. ‘accept anything and produce mUSD’\)
* An interest bearing stablecoin product for custodied stablecoins \(e.g. a CEX\)

Some ideas to **utilise** mAssets or MTA:

* Using mAssets to collateralise synthetic instruments
* An application that uses mUSD as collateral
* An application that uses MTA as collateral
* An index fund using MTA or mStable, where the SAVE product contributes to the yield
