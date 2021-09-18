# Meme Bajaar

## Problem this project solves
These are the tough times and a smile is all that matters. Meme culture is trending these days. Memers are doing a tremendous job. This is a crazy marketplace where memers get benefitted and followers show them love by collecting and trading memes. With this, creators get motivated and bring us more content.

## Pre-requisite Softwares
Truffle v5.3.14 (core: 5.3.14)
Solidity - 0.8.6 (solc-js)
Node v14.17.2
Web3.js v1.4.0

## Project Setup
### Install Node modules
> npm install
### Run Ethereum Development Network
> ganache-cli
### Compile Smart Contracts
> truffle compile
### Deploy Smart Contracts in Local Blockchain Network
> truffle migrate
### Test Smart Contract functionalities
> truffle test

## Challenges we ran into
We have built this on top of Ethereum Blockchain where we used standard ERC721 Non Fungible Tokens. We built two smart contracts, ERC721 and NFT Marketplace. We faced challenges integrating both contracts. When we were calling ERC721 functions within NFT Marketplace functions, we were unable to fetch the function invoker addresses by msg.sender. Later we have gone through solidity docs and resolved this by using Tx.origin.

## Future Developments
Build a complete dApp using React.js

## Acknowledgements
Thanks to EthOdyssey and DevFolio for giving opportunity to build this project on Ethereum
