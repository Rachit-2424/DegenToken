# Degen Token
## Description
- DegenToken is a decentralized ERC-20 token contract built on the Ethereum blockchain. - It allows for the creation, transfer, and management of tokens.

## Features
The Degen Token contract provides the following features:

- Name: The name of the token.
- Symbol: The symbol or ticker of the token.
- Total Supply: The total supply of tokens in existence.
- Owner: The address of the contract owner.

## The contract includes the following functions:

## Constructor
- The constructor function initializes the token by setting the name, symbol, and contract owner.

# Transfer:
The transfer function allows token holders to transfer tokens to another address. It requires a valid recipient address and checks if the sender has sufficient balance to complete the transfer.

# Approve:
The approve function enables the token owner to approve a spender to transfer a specific number of tokens on their behalf. It sets the allowance for the spender.

# TransferFrom:
The transferFrom function allows a spender with sufficient allowance to transfer tokens from a specific address to another. It verifies the recipient address, available balance, and allowance before executing the transfer.

# Mint:
The mint function is only accessible by the contract owner and allows them to create new tokens. It increases the balance of the recipient address and updates the total supply.

# Redeem:
The redeem function enables token holders to redeem a specific number of tokens. It reduces the balance of the sender and updates the total supply accordingly.

# Burn:
The burn function allows token holders to permanently remove a specific number of tokens from circulation. It decreases the balance of the sender and updates the total supply.

## MIT License

The DegenToken contract is licensed under the MIT License. Please see the LICENSE file for more details.

## Created by:

 Rachit Gupta
 