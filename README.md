# MyToken Smart Contract

This repository contains a simple ERC-20-like smart contract implemented in Solidity. The contract includes basic functionalities such as minting and burning tokens.

## Contract Details

- **Token Name**: Haadi
- **Token Symbol**: Auggie
- **Total Supply**: Variable, initialized to 0

## Features

1. **Public Variables**
    - `name`: Stores the name of the token.
    - `symbol`: Stores the abbreviated name of the token.
    - `totalSupply`: Stores the total supply of the token.

2. **Mapping**
    - `balances`: Maps addresses to their respective token balances.

3. **Functions**
    - `mint(address _address, uint256 _value)`: Mints new tokens and assigns them to the specified address. This function increases the total supply and the balance of the given address.
    - `burn(address _address, uint256 _value)`: Burns tokens from the specified address. This function decreases the total supply and the balance of the given address. It checks if the address has enough balance before burning.
## Creator
- [Vaibhav Kushwaha](https://www.linkedin.com/in/professorauggie)
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
