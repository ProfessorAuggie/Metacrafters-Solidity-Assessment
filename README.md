# Solidity Token Contract

This repository contains a Solidity contract for creating a basic token named "Haadi" with the symbol "Auggie". The contract includes functions for minting new tokens and burning existing ones, along with appropriate safety checks.

## Contract Details

- **Token Name**: Haadi
- **Token Symbol**: Auggie
- **Total Supply**: Initially set to 0

## Contract Structure

The contract consists of the following components:

1. **Token Details**: Public variables storing the name, symbol, and total supply of the token.
2. **Mapping of Balances**: A mapping associating addresses with their token balances.
3. **Mint Function**: A function for minting new tokens and increasing balances.
4. **Burn Function**: A function for burning existing tokens and decreasing balances, with safety checks.

## Usage

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., token.sol). Copy and paste the following code into the file

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version)

### Interacting with the Contract

Once deployed, you can interact with the contract in the following ways:

- **Minting Tokens**: Call the `mint` function with the desired recipient address and token value to create new tokens.
- **Burning Tokens**: Call the `burn` function with the sender's address and token value to destroy existing tokens.

Ensure that the sender's balance is sufficient before calling the `burn` function to avoid errors.

## Contributing

Contributions to improve the contract or add new features are welcome! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push your changes to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

## Creator
- [Vaibhav Kushwaha](https://www.linkedin.com/in/professorauggie)

## License

This project is licensed under the [MIT License](LICENSE).
