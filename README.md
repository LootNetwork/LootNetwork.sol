# LootNetwork.sol

LOOT is a deflationary and ultra-sound currency designed for participants of the Metaverse, for applications such as NFT sales and as a medium of exchange. It is built on the Cronos Chain by Crypto.com. Integrated within the contract, is a unique mechanism that burns 1% of every transaction.

**LOOT's Unique Burn Mechanism:**

Other deflationary tokens that burn a portion of each transaction have been deployed before. Examples of such tokens are BOMB and Stratera, built on the Ethereum blockchain. The practical limitation of their burn mechanisms, is that the tokens were not compatible with modern swap platforms such as Uniswap. The solution to this limitation, required users to first exchange the original tokens with a "wrapped" version before proceeding to swap them. This solution may have circumvented incompatibility with swap providers, but posed a significant inconvenience to the average user.

The burn mechanism for LOOT is unique in the fact that it is compatible with swap providers, without needing to be "wrapped" before swap. This is accomplished by detecting whether the address that is invoking any transfer functions, is a contract, or a normal address. By determining if the address in question contains any code, the token contract can dynamically enable or disable the burn mechanism.

🔗 **Links:**

Website: lootnetwork.ca

Discord: discord.gg/LootNetwork

Twitter: twitter.com/LootNetwork_

Medium: medium.com/@Loot_Network
