# NFT Minting DApp

This is a simple NFT (Non-Fungible Token) Minting DApp (Decentralized Application) that allows users to create and mint their own unique NFTs on the blockchain. NFTs have gained popularity for their ability to represent ownership and provenance of digital assets.

The DApp provides a user-friendly interface where users can connect their wallets and mint NFTs using predefined or custom metadata. It leverages the power of blockchain technology, ensuring the immutability and traceability of each minted NFT.

## Features

- **User Authentication**: Users can connect their wallets (such as MetaMask) to the DApp to authenticate and interact with the blockchain.
- **NFT Minting**: Users can mint their own NFTs by providing the necessary metadata, including name, description, image, and any other relevant attributes.
- **Metadata Management**: The DApp allows users to manage the metadata associated with their minted NFTs. They can update the metadata, such as changing the name, description, or image.
- **Blockchain Integration**: The DApp integrates with a blockchain network (e.g., Ethereum) to store the NFTs and their associated metadata on the blockchain, ensuring transparency and security.
- **NFT Gallery**: Users can view a gallery of all the NFTs they have minted, including their metadata and ownership details.
- **Marketplace Integration** (optional): If desired, the DApp can integrate with a marketplace where users can buy, sell, or trade their minted NFTs with other users.

## Prerequisites

Before running the DApp, make sure you have the following:

- A compatible web browser (Chrome, Firefox, Brave, etc.).
- A cryptocurrency wallet (e.g., MetaMask) installed and configured with the desired blockchain network (e.g., Ethereum).
- Setting up Zeeve RPC endpoints

## Installation

To install and run the NFT Minting DApp locally, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/nft-minting-dapp.git
   ```

3. Create .env file

```shell
ZEEVE_HTTP_URL= enter your http url here
PRIVATE_KEY= enter your private key from your wallet
```
2. Run the following commands in the Terminal:

```shell
npm i
cd my-nft-dapp
npm i
cd ..
npx hardhat run scripts/deploy.js --network polygon_mumbai
```
4. Add abi and deployed smart contract address.
5. Run the following commands:
```shell
cd my-nft-dapp
npm run dev
```
