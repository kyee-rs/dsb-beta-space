---
description: Reading the error, understanding the cause, looking for the proper support.
---

# Errors

Sometimes your requests may fail for various reasons and most of the time bot tries to give you some information about why it failed. This page will show you a breakdown of such responses.

<figure><img src="../../.gitbook/assets/Screenshot 2024-05-11 at 23.22.37.png" alt="" width="563"><figcaption><p>Example Error Response</p></figcaption></figure>

The error response always starts with a "Warning (⚠️)" sign followed by a default message and a reason below. The top part doesn't interest us much, so let's proceed with the reason.

### Possible errors and how to deal with them

Here I will write down most of the possible errors and reasons why they occurred. If your error isn't present here, feel free to contact [@devkyee](https://t.me/devkyee) in Telegram.

<table><thead><tr><th width="249">Error Message</th><th>Cause</th><th>Possible solution</th></tr></thead><tbody><tr><td>An error occurred while processing the request (RPC). Please try again later.</td><td>The RPC provider has failed to return some crucial information. This could be a minor outage from their part, or an old token with huge history that hits the limit.</td><td>Retry again later, if it doesn't succeed - token hits the limit.</td></tr><tr><td>No SOL liquidity pool found</td><td>Currently the bot supports only TOKEN-SOL Liquidity pairs on Raydium, Orca, Pump.fun. If for some reason token doesn't have a SOL pool, the request will fail.</td><td>Retry again later (maybe the Dev will create a SOL pool in a few minutes). If no, unfortunately, we do not scan those tokens.</td></tr><tr><td>Invalid public key input</td><td>Could be an invalid public key for a token (check on solscan) or a bug.</td><td>Verify the address on SolScan. If exists contact the support.</td></tr><tr><td>Scan is taking too long to process</td><td>Scan took more than 5 minutes to process.</td><td>Retry later, if the issue persists do not retry.</td></tr><tr><td>Metadata for this token does not exist. Check the mint address.</td><td>Either the token does not have metadata (name, symbol, etc.) or is not a token but an address.</td><td>Verify the address on SolScan. If exists contact the support.</td></tr><tr><td>Token basic information fetch failed. Reason: No associated token address found for creator</td><td>Possible Bug on our side.</td><td>Shouldn't occur most of the times but if you see this error, contact <a href="https://t.me/devkyee">@devkyee</a> in Telegram.</td></tr><tr><td>Token basic information fetch failed. Reason: LP Mint includes a malicious program id...</td><td>The error is self-explanatory. Liquidity mint includes transactions with a forbidden Program ID which floods the transaction list and forces us to scan a lot of useless transactions (the ones that do not affect balance).</td><td>Do not retry, token is forbidden to scan on our platform.</td></tr><tr><td>Could not process wallet activity for this token</td><td>SHOULD NOT OCCUR ON THE LATEST VERSION</td><td>Contact the support if occurred.</td></tr><tr><td>RPC Timed out while fetching initial liquidity transaction. Please retry.</td><td>RPC Timed Out.</td><td>Retry in a few minutes.</td></tr><tr><td>Non-base58 character</td><td>Same as "Invalid Public Key"</td><td>Same as "Invalid Public Key"</td></tr><tr><td>relation "..." does not exist</td><td>BUG</td><td>Report to the support.</td></tr></tbody></table>

## Any errors that are not present there should be reported to the support ❗
