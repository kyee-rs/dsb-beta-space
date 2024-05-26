---
description: What are Layered Transfers and their impact on the token's security
---

# Layered Transfers

During our development we’ve encountered an issue of poor scanning time when scanning huge tokens with holders that have a big transaction history. To resolve this we’ve came up with an idea of Layered Transactions.

## Layered Transaction - Concept Description

Layered Transaction is a representation of a tree-like structure which is drawn below:

<figure><img src="../.gitbook/assets/Layers Screenshot Apr 20.png" alt=""><figcaption><p>Layers</p></figcaption></figure>

### Scanning deep into Layers

To scan a layer in our bot we’ve introduced a new command syntax that looks like this (pseudo):

```
<contract address> <wallet address (head of a layer)>
```

By default the head of a layer is a deployer(s).
