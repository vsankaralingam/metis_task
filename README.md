# ScaffoldETH-MetisDemo

Using Scaffold-ETH 2 to spin up a dApp on Metis Layer 2.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [License](#license)

## Introduction

This project demonstrates how to develop decentralized applications (dApps) on the Metis Layer 2 blockchain using the Scaffold-ETH 2 framework. It guides users in setting up a local Ethereum network, deploying smart contracts, and configuring apps for Metis testnet or mainnet.

## Features

- Deploy dApps on Metis L2
- Scaffold-ETH 2 framework integration
- Smart contract deployment & verification
- Frontend and backend configuration
- Vercel deployment support

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vmmunoza/ScaffoldETH-MetisDemo.git
    cd ScaffoldETH-MetisDemo
    ```

2. Install dependencies:
    ```bash
    yarn install
    ```

3. Run the local Ethereum environment:
    ```bash
    yarn chain
    ```

4. Deploy contracts:
    ```bash
    yarn deploy
    ```

## Usage

- Start the frontend:
    ```bash
    yarn start
    ```
- Visit `http://localhost:3000` to interact with the dApp.

## Configuration

- Edit `.env` for environment variables like RPC URLs for testnets or mainnets.
- Smart contracts can be modified in the `/contracts` directory.

## Dependencies

- [Scaffold-ETH 2](https://github.com/scaffold-eth/scaffold-eth-2)
- Node.js & Yarn
- Solidity

## Examples

- Deploy to Metis testnet using:
    ```bash
    yarn deploy --network metisTestnet
    ```

## Troubleshooting

- Ensure you have the correct environment variables set in `.env`.
- Check RPC URL configurations and Metis network details for errors.


## License

This project is licensed under the MIT License.


Deployed contract : [link](https://explorer.metis.io/address/0xe7845d23bEE42d4bC7eC8F1673174942045De41B/contract/1088/code)

Dapp homepage 
![Screenshot from 2024-09-17 11-10-04](https://github.com/user-attachments/assets/6f4150b8-cdd5-44b0-a184-431e79eeff5e)
 Interactation
 ![Screenshot from 2024-09-16 23-12-52](https://github.com/user-attachments/assets/9adec206-8bd7-471d-a8b5-96adf62dd38a)


