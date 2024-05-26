---
description: A brief overview of a successful scan report
---

# Successful Scan Reports

After you've received a reply from DSB you might get a little confused of seeing all the information. We should break the successful scan report into pieces and have a detailed look on the each one.

On this screenshot you might see a few key-points that should draw your attention but let's start from the top.

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-12 at 00.33.47.png" alt="" width="375"><figcaption><p>Successful Scan Report</p></figcaption></figure>

1. Ticker - Short code for each token, usually a shortened name ($DSB, $SC, $BTC)
2. <mark style="color:red;">Mintable status</mark> - **This should always be a "No"**. Otherwise a big  🚩red flag.
3. Additional labels - entry shows any additional information about the token. Usually is not considered a safety concern unless the "⚠️" emoji is present.

***

4. Pool - The liquidity pool DEX platform (Raydium, Orca, PumpFun)&#x20;
5. <mark style="color:red;">LP Status</mark> - What % of a LP token supply was burned. Usually 100% is required and considered a good practice. If the LP Status is <100%, the Dev can withdraw the liquidity and "liquidate" the token's price to 0$.
6. Liquidity - Current liquidity value of a token (USD).
7. <mark style="color:red;">Supply Airdropped</mark> - % of supply of a token that was airdropped from the Dev to other wallets. The lower value is the better.&#x20;

***

7. Market Capitalisation (MC) - Current MC of a token. `(total supply - burned supply) * price`
8. Age - Time surpassed from the launch of a token (First mint transaction).
9. <mark style="color:red;">Top 10 Holders</mark> - Specifies the % share of 10 biggest wallets. This value should not usually exceed 40%.
10. Initial MC, LIQ - Initial values that were given on token's release to Raydium, Orca, PumpFun.

***

11. Socials, Charts, Snipers - This category could be grouped into one entry. Contains useful links for a user.
12. CA - Contract Address of a scanned token

***

13. Wallet Activity

Let's have a closer look on this one. The wallet activity section consist out of few informational blocks.

1. "X wallets holding Y%" - This block contains information about indexed wallets. X is the indexed wallets amount and Y is % of total supply. X is always limited to 20.
2. 👷🏻 XYZ2 - This emoji specifies developers' wallets. (Could be >1 if first mint was performed to multiple wallets)
3. XYZ2 (Wallet) - Shows a wallet that was involved in developers' transactions of a token.
4. (2) - Amount of "[Next Layer](../../vocabulary/layered-transfers.md)" transactions.
5. B: 0.0 SOL / S: 0.1 SOL - Total swapped value of every wallet.
6. 🔻 - Specifies that a wallet has sold more than it bought.

***

14. Layers - Total amount of layered transfers.

***

15. Swaps - Total swapped Solana amount (Buys and Sells).
