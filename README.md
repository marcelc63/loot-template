# Solidity Contract Template based on Loot [@lootproject](https://twitter.com/lootproject) [https://lootproject.com](https://lootproject.com)

Source: [https://etherscan.io/address/0xff9c1b15b16263c61d017ee9f65c50e4ae0113d7](https://etherscan.io/address/0xff9c1b15b16263c61d017ee9f65c50e4ae0113d7)

Loot is a NFT that took the NFT world by storm. It redefines what an NFT could be.
A characteristic of a loot NFT is all data is contained on chain. No IPFS or external hosting used.
They did this in a very gas efficient way for the minter as most computation is offloaded to the read function.
Loot has become a prime example on how to create on-chain NFTs.

This contract showcase how you will want to structure your contract to create an on-chain NFT,
the key is to not construct the metadata during minting, but offload everything to a read function.
Although deployment might be costly, it makes minting gas efficient.

Curated by [@marcelc63](https://twitter.com/marcelc63) - [marcelchristianis.com](https://marcelchristianis.com)
Each functions have been annotated based on my own research.

Feel free to use and modify as you see appropriate

# Using the Template

Please do the followings

1. Modify any code that's labeled with TODO
2. Change the baseURI in deploy.js, run.js, and test.js
3. Make sure to create your own .env and modify hardhat.config.js accordingly with your deployment URL and accounts private key.
4. Remove the comments and annotation

# Included in the Template

1. Contract that CoolCatsNFT used
2. Complete commentary on core functions
3. Deployment Script
4. Testing Script

# Commands to use

```
// To test

npx hardhat run scripts/run.js
npx hardhat test

// To deploy to Rinkeby testnet

npx hardhart run scripts/deploy.js --network rinkeby
```
