## Usage
1. **Token Name:** The name of the token is "QuantumPoints".
2. **Token Abbreviation:** The abbreviation for the token is "QP".
3. **Total Supply:** The initial total supply of tokens is set to 0 and can be increased through minting.
4. **Mint Function:** The `mint` function allows the contract owner to create new tokens and assign them to a specific address.
    - Parameters: `_address` (address to mint tokens to), `_value` (amount of tokens to mint).
5. **Burn Function:** The `burn` function enables the contract owner to destroy tokens held by a specific address.
    - Parameters: `_address` (address to burn tokens from), `_value` (amount of tokens to burn).

## Getting Started
To deploy and interact with this contract:
1. Deploy the contract on an Ethereum-compatible blockchain using a development environment like Remix or Truffle.
2. Use Ethereum wallets or custom scripts to interact with the deployed contract, calling the `mint` and `burn` functions as needed.

## License
This contract is licensed under the MIT License. You are free to use, modify, and distribute it according to the terms of the license.

## Disclaimer
This contract is provided as-is and may not be suitable for production use without further customization and auditing. Use it at your own risk.
