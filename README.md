# ETH-proof-Beginner-EVM-course
In this we are making our project using solidity.

# MyToken Solidity Contract
This repository contains a basic implementation of a token contract called MyToken in Solidity.

# Description
In this project we are going to used mint function,burnt function and some more to perform the code.

## Overview

The MyToken contract is a simple ERC-20 compatible token contract with minting and burning functionality. It allows users to create new tokens and destroy existing tokens based on certain conditions.

The contract includes the following features:

- Public variables that store the details about the token, such as token name, token abbreviation, and total supply.
- A mapping of addresses to balances to keep track of token balances for each address.
- A mint function that increases the total supply by a specified amount and increases the balance of the sender's address.
- A burn function that decreases the total supply by a specified amount and decreases the balance of the sender's address, with conditionals to ensure the sender has sufficient balance.

## Usage

1. Clone the repository

2. Install the required dependencies, such as Solidity compiler

3. Open the contract file `MyToken.sol` and customize the token details (token name, abbreviation, total supply) according to your requirements.

4. Compile the contract using the Solidity compiler: To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

5. Deploy the contract to a blockchain network of your choice using your preferred deployment method.

6. Interact with the deployed contract using a compatible wallet or through a custom interface.

## Contributing

Contributions to this project are welcome. Feel free to open issues and submit pull requests to suggest improvements, add new features, or report bugs.

When contributing, please ensure to follow the existing coding style and include appropriate test cases for any changes.

## Authors

Metacrafter Harsh Chaudhary

## License

This project is licensed under the [MIT License](LICENSE).

