# ETH-proof-Beginner-EVM-course
In this phase of the project, We are making our project using solidity.
# Description
In this project, we are going to use the mint function, burnt function, and some more operations to perform the code.
# installing
This code is run on the online platform i.e. Online Remix IDE.
we can directly publish our code through it or make a new repository over GitHub and create a new file there.
# executing program
so after completing the code on online remix ide their an option of compiling the program. 
# Performing operations
After the compilation of the code, we need to deploy the code and check the functionality of the functions that we are using in our code.
# mint function
The mint function allows for the creation of new tokens. It takes two parameters:

address: The address for which the token balance will be increased.
value: The number of tokens to be minted. The function increases the total supply by the specified value and adds the same amount to the balance of the specified address.
# burn function
The burn function allows for the destruction of tokens. It works in the opposite way to the mint function. It takes two parameters:

address: The address from which the token balance will be decreased. 
value: The number of tokens to be burned. The function checks if the balance of the specified address is greater than or equal to the amount to be burned. If it is, the total supply is decreased by the specified value, and the balance of the specified address is decreased by the same amount.
https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.18+commit.87f61d96.js

