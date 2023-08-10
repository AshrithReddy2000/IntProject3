# IntProject3
# Custom Token Smart Contract

This repository contains a simple Solidity smart contract that implements a custom token. The contract allows the contract owner to mint tokens to a provided address, and any user can transfer and burn tokens.

## Contract Details

- **Solidity Version:** 0.8.0
- **Token Name:** Custom Token
- **Token Symbol:** CTK

## Functions

1. **`mint(address _to, uint256 _amount)`**: Allows the contract owner to mint new tokens to a provided address.
   - Access: Only the contract owner can call this function.
   - Effect: Mints and assigns `_amount` of tokens to `_to` address.

2. **`transferTokens(address _to, uint256 _amount)`**: Allows any user to transfer tokens to another address.
   - Access: Any user can call this function.
   - Effect: Transfers `_amount` of tokens from the caller's address to `_to` address.

3. **`burnTokens(uint256 _amount)`**: Allows any user to burn (destroy) tokens from their own balance.
   - Access: Any user can call this function.
   - Effect: Burns `_amount` of tokens from the caller's balance.

## Usage

1. Deploy the smart contract on an Ethereum network compatible with Solidity 0.8.0.

2. Use the contract functions to mint, transfer, and burn tokens as needed.

3. Customize the contract further to include additional features or security measures.

## Deployment

To deploy the smart contract, you can use tools like Remix IDE or Truffle. Make sure to select the appropriate Solidity version (0.8.0) during deployment.


