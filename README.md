# Notafckingthing - NFT Minting Website

Welcome to the Notafckingthing NFT minting website! This project pokes fun at the impermanence of metadata associated with first-generation NFT contracts. It is integrated with the Solana blockchain and uses Metaplex's candy machine for minting unique tokens.

## Project Overview

- **Website:** [https://notafckingthing.com/](https://notafckingthing.com/)
- **GitHub Repository:** [https://github.com/J-geleta/NFT](https://github.com/J-geleta/NFT)
- **Blockchain:** Solana
- **Minting Mechanism:** Metaplex's candy machine

## Features

- Minting of NFTs with 7 potential traits of varying rarity.
- Integration with the Solana blockchain.
- Randomized minting process to ensure uniqueness of each token.

## Technical Details

### Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Blockchain:** Solana
- **Smart Contract:** Metaplex's Candy Machine

### Setup Instructions

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/J-geleta/NFT.git
    ```

2. Navigate to the project directory:
    ```bash
    cd NFT
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Configure environment variables in a `.env` file:
    ```bash
    REACT_APP_SOLANA_NETWORK=mainnet-beta
    REACT_APP_CANDY_MACHINE_ID=<Your Candy Machine ID>
    REACT_APP_TREASURY_ADDRESS=<Your Treasury Address>
    ```

5. Start the development server:
    ```bash
    npm start
    ```

### Minting Process

The minting process is designed to be random, ensuring each token has a unique combination of traits. There are 7 potential traits, each with varying rarity levels. The randomness is managed by the smart contract on the Solana blockchain integrated with Metaplex's candy machine.

