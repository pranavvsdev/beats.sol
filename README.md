# Deploying ERC20 Contract to Avalanche Local Subnet

This repository contains a simple ERC20 contract named "Beats" along with instructions on how to deploy it to the Avalanche local subnet using Remix with MetaMask on an Ubuntu system.

## Prerequisites

- [Ubuntu](https://ubuntu.com/) operating system
- [Remix](https://remix.ethereum.org/) - Ethereum IDE
- [MetaMask](https://metamask.io/) - Ethereum wallet extension for your browser
## Description

The "Beats" ERC20 contract allows users to create, transfer, and redeem tokens on the Avalanche blockchain. It also introduces a unique feature of redeemable items, adding an extra layer of functionality to the standard ERC20 implementation.

 ## Getting Started
 
 ### Executing the code

- Clone the Repository: Begin by cloning this repository to your local machine.

- Install Dependencies: No additional dependencies are required for this project.

- Open Remix: Access Remix in your web browser. It serves as your development environment.

- Import the Contract: In Remix, import your ERC20 contract file (e.g., ERC20.sol).

- Compile the Contract: In the "Solidity Compiler" tab, compile your contract and ensure there are no errors.

- Configure MetaMask for Avalanche Local Subnet: Set up MetaMask to connect to the Avalanche C-Chain on the local subnet.

- Deploy the Contract: In the "Deploy & Run Transactions" tab, deploy your ERC20 contract using MetaMask and Remix.

- Interact with the Contract: After deployment, interact with the contract using functions like mint, burn, and the custom redeem function.
 
 In order to download the avalanche CLI and export it to your path, you can refer to the docs below to do the necessary steps.

 ## Subnet Creation
 
 [https://docs.avax.network/tooling/cli-guides/install-avalanche-cli] - Installation docs

Subnet creation:

```
avalanche subnet create mysubnet
```

Subnet Deploy :

```
avalanche subnet deploy mysubnet
```

Ensure that your MetaMask account has sufficient funds for gas fees on the Avalanche local subnet.
Double-check the contract logic and values before deploying.
 
 ## Authors
 
Pranav S Devang
 
@pranavssdevang@gmail.com
 
## License
 
This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
