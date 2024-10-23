# TokenSol Course Project
This is a simple solidity contract that implements a token system with minting and burning functionality. The contract is built to store details such as name, abbreviation, and total supply, and allows minting(creation) and burning (destruction) of tokens.

# Getting Started
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy the code onto the created file. 


# Contract Features and Variables
The mint function allows for the creation of new tokens. The total supply of tokens is increased, and the balance of the specified address is increased by the same amount.

The burn function allows for the destruction of tokens.
The total supply is decreased, and the balance of the specified address is decreased by the same amount, but only if the address has enough tokens to burn.

TokenName: Stores the name of the token.

TokenAbbrv: Stores the abbreviation or symbol of the token.

totalSupply: Stores the total number of tokens currently in circulation. It is updated whenever tokens are minted or burned.
