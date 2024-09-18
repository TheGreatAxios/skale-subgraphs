# Instant Subgraphs

[Goldsky's Instant Subgraphs](https://docs.goldsky.com/subgraphs/guides/create-a-no-code-subgraph)

Simple JSON config file to index a contract with an ABI.

In this example I've taken a reduced version of a fully compatible ERC-20 ABI to reduce the amount of events to index. Then, I've created a config file to index two contracts:
1. [FlocLoyaltyToken](https://lanky-ill-funny-testnet.explorer.testnet.skalenodes.com/address/0xD8FBac5c966ac9Bfb006564D2603cF03532A0991) in Nebula Testnet
2. [Compass](https://elated-tan-skat.explorer.mainnet.skalenodes.com/address/0x31E0B85Eff93fc3cb5423cd3E23868F5B18fF0bB) in Europa Mainnet

You can deploy a subgraph from scratch and start indexing these contracts simply running:  `goldsky subgraph deploy skale-tokens/1.0.0 --from-abi config.json`
