# The Validation System

Once our PowerChain mainnet is live at the end of Q4 2020, everyone will be able to download and install a on Linux dedicated software that functions as a gateway for your own Nordic Energy node! Once launched, the user needs to define parameters that will design his unique staking set up:

1. Amount of NET tokens to stake.
2. Which sidechain the user would like to join.

The minimum amount of tokens that you need to own to stake for a given network is decided by the sidechain owner, and defaults to 1000 NET.

Depending on the security level and the strategic interpretation of the dApp or business owner this number can change. The initial use cases from Nordic Energy will use 1000 NET for the Energy Use case, and 10.000 NET for the banking use case due to higher security constraints.

The issuer can also create and maintain a whitelist of allowed validators, limit the total number of active validators, and more. This approach provides great flexibility in deploying public, consortium or fully private sidechains.

**Validator Selection**

Each voting period, all participating validators in the sidechain sign a block with their private key. In return for the processing power provided, the transaction costs incurred during a notarization window \(time between anchoring of sidechains to the mainnet\) are distributed to the nodes based on the NET tokens they staked.

**Double payout for large staking amounts — “Trust Nodes”**

The distribution favors large Nordic Energy \(NET\) token deposits, as the likelihood of signing erroneous blocks as an attack vector is lower given the higher value at stake. Nordic Energy sidechains therefore double the relative payout if more than 50.000 NET have been staked. We then call them “Trust Nodes”, indicating that they will lose a lot of tokens should they misuse the trust the network gives to them.

This is accordingly illustrated by the following image at a sidechain assuming transaction costs of 1.000 NET per hour, which comes down to 10.000 transactions at a NET price of 0.1$:

IMAGE



For the initial testing phase, everyone can become a Trust Node, it is however possible that in the future the Nordic Energy foundation will limit the amount of users that can become Trust Nodes.

**Please note:** NET tokens can be staked only once, meaning that if you stake for sidechain x you cannot stake for sidechain y — however, you can pull out your token from sidechain x and join the sidechain y network or split them on various sidechains. To attract more stakers, sidechain creators can also offer a rent, a monthly payment of NET tokens for the nodes.

