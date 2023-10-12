# Decentralized Token Swapping Application

## Overview

The Decentralized Token Swapping Application is a smart contract-based platform built on blockchain technology that allows users to seamlessly connect and swap crypto tokens for other assets in a decentralized and trustless manner. This project is designed to provide a secure, efficient, and transparent solution for the exchange of digital assets.

## Features

- **Token Swapping**: Users can swap one cryptocurrency for another, or for other digital assets (e.g., NFTs), directly within the application.

- **Decentralization**: The platform operates on a decentralized network, ensuring that users have full control over their assets and transactions without relying on intermediaries.

- **Smart Contracts**: Smart contracts govern the swapping process, enabling automatic, trustless, and secure exchanges between parties.

- **Supported Tokens**: The application supports a wide range of cryptocurrencies, including major tokens such as Ethereum (ETH), as well as various ERC-20 and ERC-721 tokens.

- **User-Friendly Interface**: The user interface is designed to be intuitive and easy to use, allowing both novice and experienced users to navigate the platform seamlessly.

- **Security**: The smart contracts are developed with security best practices to protect users from potential vulnerabilities.

## How It Works

1. **Connect Wallet**: Users must connect their cryptocurrency wallet to the application. This ensures that they have control over their assets during the swapping process.

2. **Select Tokens**: Users select the crypto tokens they wish to swap and specify the desired amount.

3. **Initiate Swap**: After specifying the details of the swap, users can initiate the swap, which triggers the smart contract to execute the exchange.

4. **Confirmation**: Once the smart contract confirms the transaction, the exchanged assets are transferred to the respective parties.

## Getting Started

To run the Decentralized Token Swapping Application locally for testing and development purposes, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/japjoh/jsmart.git
   cd jsmart
  npm install

Once installed, let's run Hardhat's testing network:

npx hardhat node

Then, on a new terminal, go to the repository's root folder and run this to deploy your contract:

npx hardhat run scripts/deploy.js --network localhost
Finally, we can run the frontend with:

cd frontend
npm install
npm start

Open http://localhost:3000/ to see your Dapp. You will need to have Coinbase Wallet or Metamask installed and listening to localhost 8545.

enjoy the work - JJ

