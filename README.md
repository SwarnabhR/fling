# Flink - Decentralized Dating App

**Flink** is a decentralized dating app built on the **Polygon blockchain (Polygon POS)**, drawing inspiration from popular apps like Bumble and Hinge. Flink focuses on privacy, user ownership of data, and blockchain-powered features such as virtual currency and NFT-backed achievements. The app includes AI-powered matchmaking, smart contracts for real-world meetups, and Anon Aadhar for secure identity verification.

## Features

- **AI-Powered Matchmaking**: Uses advanced AI algorithms to analyze user behavior and preferences for more accurate match suggestions.
  
- **Privacy-Focused**: Built with privacy by design, users maintain full control over their data, with decentralized identity (DID) and encryption to ensure security.
  
- **Anon Aadhar Integration**: Prevents fake profiles through KYC and identity verification using Anon Aadhar, a blockchain-based identity management system.
  
- **Virtual Currency**: Users earn **Fling Coins** through engagement, which can be redeemed for **Solana ($SOL)** cryptocurrency.
  
- **NFT-Backed Achievements**: Users can unlock and collect NFTs for certain in-app milestones, making them unique collectibles tied to their profile.
  
- **Smart Contracts for Real-World Meetups**: Flink uses smart contracts to facilitate secure, trustless interactions between users, such as payments for shared events or booking date venues.
  
- **Self-Destructing Messages**: Users can send private, time-limited messages that automatically delete after a set duration.
  
- **Geo-Fencing for Location-Based Matches**: Helps users connect with others in their vicinity using secure and privacy-preserving location technologies.
  
- **Gamified User Challenges**: Earn rewards for completing challenges, contributing to the community, or achieving personal milestones within the app.
  
- **Crowdsourced Matchmaking**: Leveraging community-driven matchmaking, users can help suggest potential matches for others.

## Tech Stack

- **Frontend**: 
  - React.js (Next.js for Server-Side Rendering)
  - Plain CSS for styling
  - Web3.js or Ethers.js for interacting with the blockchain

- **Backend**:
  - Node.js
  - Express.js for API
  - MongoDB for user data and non-blockchain storage
  - Smart contracts deployed on the **Polygon POS** blockchain

- **Blockchain**:
  - **Polygon POS** for decentralized infrastructure
  - **Solidity** for smart contract development
 
## Installation and Setup

### Prerequisites

- **Node.js**: Make sure you have Node.js installed. You can download it from [here](https://nodejs.org/).
- **Metamask**: Install the Metamask extension for your browser and set up a Polygon network connection.
- **Polygon Wallet**: Create a wallet on the Polygon network and obtain some test MATIC for gas fees.
- **Truffle or Hardhat**: Choose one for contract deployment and testing (Hardhat recommended for modern setups).

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/SwarnabhR/flink.git
   cd flink
2. **Install dependencies**

   Once inside the project directory, install all the necessary dependencies by running:

   ```bash
   npm install
This command will install all the packages listed in the `package.json` file, ensuring all the necessary dependencies are available for the project to run.

3. **Start the development server**

   After installing the dependencies, start the development server to run the application locally. Use the following command:

   ```bash
   npm start
This will launch the app on `http://localhost:3000`. Open the browser and navigate to this URL to interact with the app.

If there are any issues with launching the app or with the browser, make sure to check the console or terminal for any error messages.

## 4. Running Tests

Testing is crucial for ensuring the stability and functionality of your app. Here’s how to run tests for this project:

- **Run unit tests**:

  ```bash
  npm test
