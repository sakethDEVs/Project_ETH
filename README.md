# Minting & Burning Tokens

## Description

MyToken is a simple ERC-20 token contract that implements the basic functionality of a cryptocurrency. It allows users to mint and burn tokens, as well as transfer them to other addresses. The token has a fixed name (ALGORAND), symbol (ALGO), and initial supply (0).

## Installation

To use MyToken, you need to have [Solidity] installed on your system. You can use any Solidity compiler version equal to or higher than 0.8.18. 
## Usage

To deploy and interact with the contract, you need to use [Remix IDE], a web-based integrated development environment that allows you to write, compile, debug, and test Solidity code.

To use Remix IDE, you need to follow these steps:

- Copy and paste the code of MyToken contract in a new file in Remix IDE.
- Select the Solidity compiler version from the dropdown menu. Make sure it is equal to or higher than 0.8.18,.
- Click on the compile button to compile the contract.
- Select the Deploy & Run Transactions tab from the sidebar.
- Click on the deploy button to deploy the contract to the network of your choice.
- You will see the deployed contract instance under Deployed Contracts section.
- You can interact with the contract functions by clicking on the buttons next to them and providing the required parameters.

To mint tokens, you need to call the `mintSupply` function with the address and the amount of tokens you want to create. For example, if you want to mint 100 tokens for yourself, you can enter your address and 100 in the fields next to the `mintSupply` button and click on it.

To burn tokens, you need to call the `burnSupply` function with the address and the amount of tokens you want to destroy. For example, if you want to burn 50 tokens from yourself, you can enter your address and 50 in the fields next to the `burnSupply` button and click on it.

You can also use the `balances` function to check the balance of any address. For example, if you want to check your own balance, you can enter your address in the field next to the `balanceOf` button and click on it.

## Help

Feel Free to Contact me on my EMAil

## Authors
- SATYA

## License

MyToken is licensed under the MIT License. See [LICENSE] file for more details.
