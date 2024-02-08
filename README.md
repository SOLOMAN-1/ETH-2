# Initial Next.js/Hardhat Project Setup

This project acts as a foundational template integrating a Next.js front-end with a Hardhat environment for Ethereum development. It features a basic Solidity smart contract and a front-end application built with React, enabling interaction with the Ethereum blockchain via ethers.js.

## Initial Setup Instructions

To get this project up and running on your computer, follow the steps below:

1. Clone the project from GitHub to your local environment:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

2. Change your current working directory to the project folder:

   ```bash
   cd your-repo
   ```

3. Install necessary dependencies for the project:

   ```bash
   npm install
   ```

4. Open two more terminal windows in VS Code to handle different tasks simultaneously.

5. In the second terminal window, initiate a local Ethereum node with Hardhat:

   ```bash
   npx hardhat node
   ```

6. In the third terminal window, proceed to deploy the smart contract to your local network:

   ```bash
   npx hardhat run scripts/deploy.js --network localhost
   ```

7. Back in the first terminal window, start the Next.js front-end:

   ```bash
   npm run dev
   ```

8. Visit [http://localhost:3000/](http://localhost:3000/) in your web browser to view the project.

## Overview of Project Structure

- **`contracts/`**: This directory contains the Solidity smart contracts.
- **`artifacts/`**: This folder holds compiled contract artifacts.
- **`scripts/`**: Here you'll find scripts for deploying contracts.
- **`frontend/`**: Contains the Next.js and React front-end code.
- **`hardhat.config.js`**: The configuration file for Hardhat.
- **`next.config.js`**: Configuration file for Next.js.
- **`package.json`**: Defines project configuration and dependencies.
- **`README.md`**: Provides documentation for the project.

This template is designed to be flexible, allowing you to adapt and expand it for your own Ethereum DApp projects.

## Additional Information

- Before starting, ensure that Node.js and npm are installed on your computer.
- For interacting with Ethereum wallets in the browser, install the MetaMask extension.
