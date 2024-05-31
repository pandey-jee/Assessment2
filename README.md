# Assessment 2
Created a simple program use for mint and burn the token.

# Description

The MyToken smart contract is a basic implementation of an ERC20-like token on the Ethereum blockchain. It provides functionality to mint new tokens to any address and burn tokens from an address, thereby increasing or decreasing the total supply. This project is suitable for learning purposes and can be extended for more complex token-based applications.

# Getting Started
# Installing
1.Clone the repository:

git clone https://github.com/pandey-jee/Assessment2.git

cd Assessment2

2.Install dependencies:

Ensure you have the necessary tools like Solidity, Remix, Truffle, or Hardhat installed.

# Executing program
1.Open the contract:

Open the Assessment2.sol file in your preferred Solidity development environment (e.g., Remix).

2.Deploy the contract:

Deploy the Assessment2 contract to your desired Ethereum network (e.g., local development network, Ropsten testnet, or the mainnet).

// In Remix, compile the contract and deploy using the "Deploy" button.

3.Mint Tokens:

Mint tokens to an address by calling the mint function with the desired address and amount.

mint(0xYourAddress, 100);

4.Burn Tokens:

Burn tokens from an address by calling the burn function with the desired address and amount.

burn(0xYourAddress, 50);

# Help

If you encounter any issues, consider the following steps:

#1.Check your Ethereum wallet balance:

Ensure you have enough ETH to cover gas fees for deploying and interacting with the contract.

2.Verify contract deployment:

Ensure the contract is correctly deployed on the desired network by checking the contract address on Etherscan or the equivalent block explorer for your network.

3.Consult documentation:

Refer to the Solidity documentation and community forums for additional help.

# Author
Contributors names and contact info

CipherCraft

@pandey-jee

# License
This project is licensed under the GNU General Public License v3.0 - see the LICENSE.md file for details.

