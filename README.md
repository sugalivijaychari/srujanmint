# srujanmint
A marketplace for all Digital creators

## Problem this project solves
Every artist isn't much benefitted for their effort, energy and time. If they could benefit from their artworks, then it could motivate them a lot. Due to the highly volatile nature of cryptocurrency prices and the high risk that exist in trading, NFTs trading could be a 100% returns expectation investment. We have provided an NFT marketplace for the NFT traders, creators and collectors with royalties in the picture.

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
Integrate Auction contract with NFT Marketplace and build a complete dApp using React.js and Web3.js

## Acknowledgements
Thanks to HackOdisha and DevFolio for giving opportunity to build this project on Ethereum
