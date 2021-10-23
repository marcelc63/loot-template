# Solidity Contract Template based on SuperSea [https://nonfungible.tools](https://nonfungible.tools)

Source: [https://etherscan.io/address/0x24E047001f0Ac15f72689D3F5cD0B0f52b1abdF9](https://etherscan.io/address/0x24E047001f0Ac15f72689D3F5cD0B0f52b1abdF9)

SuperSea contract showcases how you can use NFT for memberships and contract for subscription.
Access to member-only features are protected behind a paywall that is unlocked through this contract.
The subscription logic allows you to collect payment and give access to users.
The NFT membership allows you to grant lifetime access to NFT holders.

This contract represents a very real use case where you can now provide authentication,
memberships, and subscriptions through the blockchain.
I see this as a common practice as web3 obtain even wider adoption.

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
