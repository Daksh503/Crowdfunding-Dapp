# Crowdfunding Platform

Welcome to the Crowdfunding Platform! This decentralized application (DApp) leverages blockchain technology to create a secure, transparent, and efficient crowdfunding ecosystem. This project enables creators to raise funds for their projects while ensuring that backers' contributions are safely managed and transparently utilized.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Smart Contract Details](#smart-contract-details)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Introduction

The Crowdfunding Platform is a decentralized crowdfunding solution that allows project creators to raise funds from backers without relying on a centralized authority. By using blockchain technology, we ensure that all transactions are transparent, secure, and immutable.

## Features

- **Decentralization**: Eliminates the need for a central authority, reducing the risk of fraud and manipulation.
- **Transparency**: All transactions and fund movements are recorded on the blockchain and can be easily verified.
- **Security**: Utilizes smart contracts to handle funds, ensuring that contributions are securely managed.
- **Automated Refunds**: If a project does not reach its funding goal, the smart contract automatically refunds the backers.
- **Accessibility**: Anyone with an internet connection can create or back a project.

## Technologies Used

### Frontend
- **Next.js**: 12.1.0
- **React.js**: 17.0.2
- **React DOM**: 17.0.2
- **Styled Components**: 5.3.3
- **Material-UI (MUI)**: 
  - **@mui/material**: 5.4.3
  - **@mui/icons-material**: 5.4.2
- **Emotion**: 
  - **@emotion/react**: 11.8.1
  - **@emotion/styled**: 11.8.1
- **React Loader Spinner**: 6.0.0-0
- **React Toastify**: 8.2.0

### Backend
- **Solidity**: For writing smart contracts.
- **Polygon**: Blockchain platform used for deploying the smart contracts.
- **Hardhat**: Development environment for Ethereum.
  - **@nomiclabs/hardhat-ethers**: 2.0.5
  - **@nomiclabs/hardhat-waffle**: 2.0.2
  - **ethereum-waffle**: 3.4.0
  - **ethers**: 5.5.4
- **IPFS**: For storing files.
  - **ipfs-http-client**: 56.0.1
- **Dotenv**: For managing environment variables.
  - **dotenv**: 16.0.0

### Development Tools
- **ESLint**: For linting.
  - **eslint**: 8.9.0
  - **eslint-config-next**: 12.1.0
- **Chai**: For assertions in tests.
  - **chai**: 4.3.6

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Daksh503/Crowdfunding-Dapp.git
    cd Crowdfunding-Dapp
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Start the development server**:
    ```bash
    npm run dev
    ```

4. **Deploy the smart contracts**:
    - Open a new terminal window.
    - Navigate to the `contracts` directory.
    - Run the following commands:
    ```bash
    npx hardhat compile
    npx hardhat run scripts/deploy.js --network matic
    ```

## Usage

1. **Create a new project**:
    - Navigate to the "Create Project" section.
    - Fill in the required details such as project name, description, funding goal, and deadline.
    - Submit the form to deploy your project on the blockchain.

2. **Back a project**:
    - Browse through the listed projects.
    - Select a project to view its details.
    - Enter the amount you wish to contribute and confirm the transaction.

3. **Monitor project progress**:
    - View the project details to see the amount raised and the remaining time.

## Smart Contract Details

The core smart contract of this platform includes the following functionality:

- **Create Project**: Allows users to create new crowdfunding projects with specified goals and deadlines.
- **Contribute**: Enables users to back projects by contributing Ether.
- **Withdraw Funds**: Allows project creators to withdraw funds if the funding goal is reached.
- **Refund**: Automatically refunds backers if the project fails to meet its goal by the deadline.

## Contributing

We welcome contributions to improve this project! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push them to your branch.
4. Submit a pull request with a detailed description of your changes.

## Acknowledgements

- Special thanks to the Ethereum and Polygon communities for their excellent documentation and support.
- Thanks to all contributors for their efforts in making this project better.


## Live Demo

Check out the live demo of the Crowdfunding Platform [here](https://web3-fundraiser-youtube.vercel.app/).
