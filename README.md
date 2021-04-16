# Binance Smart Chain token deployment example

This repository aims to showcase how to create and deploy a token in the Binance Smart Chain within the console.

In contracts, you will write the token. There is an example BEP20 token provided with some arbitrary configurations.

First, you will need to install the dependencies with `npm install`. You need your wallet mnemonic written in the secrets.json file. An example is provided in the file named secrets-example.json, which you should rename and update.

## Compiling

You can compile the contracts with `npx hardhat compile`.

## Deploying

Simply run `npx hardhat run --network testnet scripts/deploy.js` to deploy it to the testnet, and `npx hardhat run --network mainnet scripts/deploy.js` to deploy it on the mainnet.
