# "PIE Token Contract: MyToken"

# Overview / Description 
The PIE Token Contract: MyToken project involves creating a basic token on the Ethereum blockchain using Solidity. This smart contract, named MyToken, manages the creation (minting) and destruction (burning) of tokens, while maintaining a record of token balances for different addresses. The token is named "PIE" with an abbreviation of "PIE".

### The contract includes the following key features:

> Token Details:

-tokenName: Public variable storing the name of the token, "PIE Cash".

-tokenAbbrv: Public variable storing the token's abbreviation, "PIE".

-totalSupply: Public variable that tracks the total supply of the token, initially set to 0.

> Balances Mapping:

-balances: A mapping that associates each address with its respective token balance.

 > Mint Function:
 
-mint(address a, uint _money): Allows the creation of new tokens. Increases the totalSupply by the specified _money and credits the amount to the balance of the to address.

 > Burn Function:

-burn(uint _money): Allows the destruction of existing tokens. Decreases the totalSupply by the specified _moneyand debits the amount from the balance of from msg.sender, provided that the address has enough tokens to burn.


This program provides a foundational example of a simple token contract on the  PIE, showcasing fundamental Solidity concepts and contract interactions.

# Getting Started

To run and interact with this program, you can use Remix, an online Solidity Integrated Development Environment (IDE). 
Here are the steps to get started:

# Execution Instructions

To deploy and interact with the "PIE Cash" contract using Remix, follow these steps:

## Step-by-Step Instructions

1. Go to the Remix Website:
   
   => Open https://remix.ethereum.org/
   
3. Create a New File:

   => Click on the "+" icon in the left-hand sidebar.
   
   => Name the file ETH Proof/project.sol.
   
4. Copy and Paste the Solidity Code:

   =>Copy the Solidity code provided link :  https://github.com/Ayushsaini123/Solidity-project/blob/main/Solidity%20code which is visible on github page.
   
   =>Paste it into the newly created BifrostToken.sol file in Remix.
   
5. Compile the Code:

   => Click on the "Solidity Compiler" tab in the left-hand sidebar.
   
   => Ensure the compiler version is set to 0.8.9 (or another compatible version).
   
   =>Click on the "Compile project.sol" button.
   
6. Deploy the Contract:

   =>Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.
   
   =>Ensure the environment is set to "Remix VM (London)" or a suitable network.
   
   =>Select the Bitcoin Cash contract from the dropdown menu.
   
   =>Click on the "Deploy" button.
   
 7. Interact with the Contract:

     i) Mint Tokens:
  
        =>In the deployed contract section, find the mint function.
   
        =>Enter the recipient's address and the amount of tokens to mint.
   
        =>Click on the transact button to mint tokens.
      
      ii) Burn Tokens:
 
         =>Find the burn function.
   
         =>Enter the amount to burn.
   
         =>Click on the transact button to burn tokens.
       
 8. Check Balances:

    => Enter an address into the balances function and click on the call button to see the balance.
   
 9.  View Token Details:

     => Click on the tokenName, tokenAbbrv, and totalSupply buttons to display their values.
 
By following these instructions, you can successfully deploy and interact with the "PIE Cash" contract on the Ethereum blockchain using Remix.

# Authors
 => Ayush Saini
 
   Github  :  (https://github.com/Ayushsaini123)
     
# License 
  This project is licensed under the MIT License - see the link ( https://github.com/Ayushsaini123/Solidity-project/blob/main/LICENSE) for details.
