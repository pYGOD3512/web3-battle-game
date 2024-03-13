# NFT Multiplayer Card-Style Game Smart Contract

A Multiplayer NFT Card-Style Game smart contract. This game's  smart contract allows users to battle other players in real-time, create their game characters, and perform smart wallet pairing.

## Setup

To set up the smart contract, follow these steps:

1. Clone the repository to your local machine:

    ```
    git clone <repository-url>
    ```

2. Install all dependencies listed in the `package.json` file:

    ```
    npm install
    ```

   Ensure that there are no errors during the installation process.

3. Compile the smart contract to make it ready for deployment:

    ```
    npm run build
    ```

4. Deploy the compiled smart contract to the desired blockchain network:

    ```
    npm run deploy
    ```

   Within a few seconds, you will receive a deployment link from Third Web in your terminal.

## Usage

5. **Install MetaMask Extension:**
   
   If you haven't already, install the MetaMask extension for your browser. You can download it [here](https://metamask.io/).

6. **Create MetaMask Account:**

   After installing MetaMask, create an account. On the top left corner, click on "Show Networks" and enable "Show Testnets". Choose the Sepolia testnet (or any other testnet of your choice).

7. **Get Free Test Ethers:**

   Click [here](https://www.alchemy.com/faucets/ethereum-sepolia) to access the Sepolia faucet and get some free test ethers for deployment. Copy your address from MetaMask and paste it on the Sepolia faucet to receive test ethers.

8. **Provide Metadata URI:**

   Navigate to the project root and open `Metadata.js` found in the `Metadata` folder. Copy the address and paste it into the URI section on the deployment page.

9. **Deploy Smart Contract:**

   Select the Sepolia network (or your chosen network) and click "Deploy". MetaMask will open automatically, where you'll need to confirm one transaction and approve the contract.

10. **Interact with Smart Contract:**

   Once deployed, Third Web provides a user interface to interact with your smart contract. You can now enjoy playing the NFT Multiplayer Card-Style Game!

## Technologies Used

- **Solidity**: The smart contract language used to implement the game logic.
- **Hardhat**: A development environment for compiling, testing, and deploying smart contracts.
- **TypeScript**: A statically typed superset of JavaScript used for writing Hardhat scripts and tests.
- **Third Web**: A platform for deploying and interacting with smart contracts.


## Game Smart Contract Features

- Battle other players in real-time.
- Create your game characters.
- Perform smart wallet pairing for secure transactions.
