# Web3 Deployment Manager

This package facilitates the deployment of smart contracts to various Ethereum networks, simplifying the process of managing and interacting with contracts during development and production stages.

## Features

- Easy smart contract deployment
- Network management for different Ethereum environments

## Usage

Ensure you have a .env file with your Ethereum node URL and private key.

```javascript
const { deployContract } = require('web3-deployment-manager');

const contractABI = [...];
const contractByteCode = '0x...';

deployContract(contractABI, contractByteCode);
