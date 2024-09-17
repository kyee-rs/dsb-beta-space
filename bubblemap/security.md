---
description: >-
  Our platform provides essential security metrics to help users evaluate the
  safety and integrity of tokens. These metrics allow users to identify
  potential vulnerabilities or suspicious activities.
---

# Security

**LP Burned**

This metric indicates the percentage of the liquidity pool (LP) tokens that have been permanently burned. LP tokens represent a share of the liquidity provided to decentralized exchanges for trading. When these tokens are burned, it means that the liquidity cannot be removed by any party, including the deployer or project owners. A high percentage of burned LP tokens ensures that liquidity is locked, preventing the possibility of a rug pull, where liquidity is drained, leaving traders with worthless tokens they cannot sell.

**Total Sniped**

This metric represents the percentage of the total token supply that has been sniped. Sniping typically involves bots quickly purchasing a large amount of tokens during or right after the token launch, often at a low price. This can give the sniper control over a significant portion of the supply, enabling them to manipulate prices or execute sudden sell-offs, which can destabilize the token’s price. A high sniped percentage is a red flag for potential market manipulation.

**Mint Authority**

This indicates whether the token contract has the ability to mint new tokens. If mint authority is enabled, the token creators have the power to generate additional tokens, potentially diluting the existing supply. Disabling mint authority ensures that no new tokens can be created, protecting the supply from being inflated without notice, which is crucial for maintaining token value and preventing supply manipulation.

**Freeze Authority**

This checks whether the token contract has the ability to freeze wallets. When freeze authority is enabled, the token creators can prevent certain wallets from transacting, which could be used to manipulate market participation or punish specific holders. For maximum transparency and fairness, this authority should generally be disabled to ensure that no wallet is unjustly restricted from trading.

**Mutable Metadata**

This metric indicates whether the token’s metadata can still be changed after deployment. Mutable metadata gives the token creators the ability to alter important information about the token, such as its name, symbol, or other key attributes. Disabling mutable metadata is a sign of good practice, as it prevents unauthorized or unexpected changes to the token’s properties, ensuring greater security and trustworthiness.



These security checks give users a clear understanding of the token’s underlying safety mechanisms and any potential risks associated with the token’s contract. Analyzing these metrics can help users make informed decisions before engaging with a token.
