# **ETH/Stables Treasury Management Proposal**


# INTRODUCTION

## OBJECTIVE

The K9 Finance DAO Treasury is holding funds that could be used for yield farming.

The K9 Finance DAO Treasury is holding funds in ETH and stablecoins that is currently unused. This proposal details how a portion of the treasury could be staked on leading DeFi protocols to earn passive yield, helping grow our reserves and strengthen the DAO, long into the futures.

This proposal outlines a conservative approach to generating yield on the treasury's assets, focusing on battle-tested DeFi protocols, and low-risk investment strategies that do not involve locking up treasury funds for any duration of time, keeping them accessible for DAO operations as needed.



## BENEFITS TO K9 FINANCE COMMUNITY

This proposal benefits the entire K9 Finance DAO and all KNINE holders by providing yield on the assets held by the K9 Finance DAO treasury ([*DeBank: **k9safe.eth***](https://debank.com/profile/0xda4df6e2121edab7c33ed7fe0f109350939eda84)). Earning yield on treasury assets helps grow our operational reserves, extendss our runway, and ensures the long-term budget for DAO operations over time.


# PROPOSAL DETAILS

## WHAT

Proposed Treasury Strategy

1. Use 130 ETH held by treasury to earn passive yield from Ethereum validators through Liquid Staking Derivatives (LSDs), like Lido staked ETH (`wstETH`).
   
2. Use $300k of stablecoins held by treasury earn passive yield through lending on Aave and through MakerDAO's DAI savings rate.

To diversify our investment, the proposed strategy will split the treasury asset investments. The starting allocation will be as follows:

### Ethereum LSDs
- 33% **`wstETH`** - [(Wrapped) Lido staked Ether](https://lido.fi/)
- 33% **`rETH`** - [Rocket Pool staked Ether](https://rocketpool.net/)
- 33% **`sfrxETH`** - [Staked FRAX Ether](https://frax.finance/)


### Stablecoins
- 33% **USDT** - [Tether USD](https://tether.to/) - lending in [Aave](https://aave.com/)
- 33% **USDC** - [USD Coin](https://www.centre.io/usdc) - lending in [Aave](https://aave.com/)
- 33% **DAI** - [DAI](https://makerdao.com/) - DAI Savings Rate (DSR) through MakerDAO's [Spark Protocol](https://app.spark.fi/savings)


> Asset allocation may be periodically adjusted based on performance and rebalancing needs, within the approved DeFi protocols. Performance monitoring and initiation of such minor adjustments will be managed by [Shima](https://twitter.com/MRShimamoto). 


### Expected Returns
- **ETH**: 2.5-3.5% APR
- **Stablecoins**: 4-12% APR

You can view current and historic returns for the respective assets on the following links:

#### Current Markets

- [Lido Staking](https://stake.lido.fi/) - currently: 3.0% APR
- [Rocketpool Staking](https://stake.rocketpool.net/) - currently: 2.55% APR
- [FRAX ETH Staking](https://app.frax.finance/frxeth/stake) - currently: 3.09% APR

- [Aave USDT Market](https://app.aave.com/reserve-overview/?underlyingAsset=0xdac17f958d2ee523a2206206994597c13d831ec7&marketName=proto_mainnet_v3) - currently: 4.48% APY
  
- [Aave USDC Market](https://app.aave.com/reserve-overview/?underlyingAsset=0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48&marketName=proto_mainnet_v3) - currently: 5.70% APY

- [Spark DAI DSR](https://app.spark.fi/savings) - currently: 10.0% APY

#### Historical Data
**Dune Analytics:**
- [Dune: Lido Staking APR](https://dune.com/queries/1288160/2264095)
- [Dune: FRAX ETH Staking APR](https://dune.com/queries/2359577/3865413)
- [Dune: Rocketpool Staking APR](https://dune.com/queries/2359581/3865444)
- [Dune: Aave V3 Supply Rates](https://dune.com/queries/1935541/3192840)
- [Dune: DAI DSR Balance & Rate](https://dune.com/queries/2721037/4529604)



**WHO**

All KNINE holders are impacted by this proposal, as any increase in treasury earnings strengthens the K9 Finance DAO as a whole.

**WHERE**

This proposal would require the k9safe.eth multisig to perform transactions on Uniswap, Curve, Aave, Spark.fi, and any other relevant tier 1 swaps/lending markets that support the above assets.

ETH from the treasury will be swapped into Liquid Staked Derivatives (LSDs). The respective LSD tokens will stay in the treasury wallet.

Stablecoins from the treasury will be rebalanced to contain 33% USDC, 33% USDT, and 33% DAI. USDC and USDT will get deposited into Aave as a lender and DAI will be deposited in Spark to earn DSR yield. aUSDT, aUSDC, and DAI lending receipts (withdrawal permission) will be held by the treasury wallet.

Investment will initially be balanced in equal portions across the 3 LSDs and 3 stablecoins. 

≈ 43.3 ETH per LSD (Lido, Rocket Pool, Frax)

≈ $100k each USDC and USDT in Aave and $100K DAI in Spark

There are always risks in performing transactions but the management council has deep technical experience and will only be interacting with approved/vetted tier 1 providers as mentioned above.

**WHEN**

This proposal should pass as soon as possible, which would be the next Roundtable meeting around May 10th-13. Implementation can happen within a week of approval.

**HOW**

The K9 Finance DAO treasury wallet will swap ETH and stables DEXes like Uniswap and CUrve. ETH will be swapped directly into LDS equivalents. Stablecoins will be deposited into the aforementioned lending protocols. All assets and control will remain under the DAO multi-sig at all times.

Asset allocations may be periodically adjusted based on performance and rebalancing needs. This allows for optimizing returns and maintaining a healthy treasury strategy without requiring a DAO vote for all changes. 

Shima from the management council will oversee this investment initiative. He will be responsible for performance monitoring and any required strategy adjustments that remain in-line with this proposal's DeFi strategies. For risk management purposes, funds can be withdrawn from DeFi protocols, back into the treasury multi-sig at any time. Outside of rebalancing and withdrawal, no other fund movement or investment strategies will be performed without DAO approval through later proposals.

The community will be able to monitor this spending via the blockchain and looking at the DAO's treasury wallet: [*Debank: **k9dao.eth***](https://debank.com/profile/0xda4df6e2121edab7c33ed7fe0f109350939eda84). 


**IMPACT ASSESSMENT**

The expected return is 
- ETH: 2.5-3.5% APR
- Stablecoins: 4-12% APR

This will be monitored by Shima, who is being suggested as the DAO member who will provide ongoing management and reporting on the performance of all treasury investment strategies. Reporting will occur monthly and be reviewed by the Roundtable of Dogs.
