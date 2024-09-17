---
description: >-
  Nodes represent individual cryptocurrency wallets capable of holding and
  transferring tokens. Each node’s size and connections offer insights into
  token distribution and movement within the network.
---

# Nodes

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p>Nodes</p></figcaption></figure>

A node refers to a wallet in the cryptocurrency ecosystem that is capable of holding, receiving, and transferring tokens. The size of a node is proportional to the amount of cryptocurrency it holds—the larger the node, the more supply that wallet is controlling.

Nodes that have not yet been fully identified, are marked with a white dot in the middle. These unknown nodes can still participate in transactions and could be part of significant token movements, but their origin or intent may be unclear. Only premium users can extend those nodes and dig deeper inside the node/cluster activity.

Nodes are not isolated; they can transfer tokens to other wallets, forming transaction paths that sometimes give rise to clusters—groups of interconnected wallets that may represent coordinated actions, such as a deployer distributing tokens across multiple wallets to obscure holdings.

In this visualization, understanding node sizes and connections helps to assess how token supply is distributed across the network and whether there are concentrated areas of control. When large nodes cluster together, it may indicate centralized control over a significant portion of the token supply, a potential red flag for market manipulation or price control.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption><p>Deployer node</p></figcaption></figure>

The deployer node, labeled with the letter **D** inside the node, represents the wallet that initially deployed the token on the blockchain. Once deployed, other wallets can interact with the token, but the deployer itself is not necessarily responsible for distributing the tokens to other wallets. However, analyzing the deployer’s activity can still provide insights into the token’s origin and any subsequent connections formed with other wallets.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>Sniper node</p></figcaption></figure>

Sniper nodes, labeled with the letter **S**, represent wallets that are included in a [Jito bundle](https://jito-labs.gitbook.io/mev/searcher-resources/bundles)—a mechanism often controlled by the deployer wallet. In this context, sniper nodes are suspicious because they indicate that the deployer might have bundled together several crucial actions such as token creation, liquidity provision, and snipes (large buy orders) within a single transaction bundle.

By bundling these actions, the deployer ensures that no other participants can interact with the market or purchase tokens in between these operations, giving them an unfair advantage. The sniper nodes are used to quickly buy up large portions of the token supply before the market has a chance to respond. This allows the deployer (or someone controlling the sniper nodes) to control a significant amount of the supply, potentially manipulating prices or dumping tokens at a later time.

This kind of behavior is highly suspicious, as it centralizes control over the token’s supply, undermining market fairness and creating the potential for price manipulation or rug pulls.
