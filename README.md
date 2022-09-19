# Udacity Blockchain Capstone

The capstone will build upon the knowledge you have gained in the course in order to build a decentralized housing product. 

# Project Resources

* [Remix - Solidity IDE](https://remix.ethereum.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Truffle Framework](https://truffleframework.com/)
* [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
* [Open Zeppelin ](https://openzeppelin.org/)
* [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
* [Docker](https://docs.docker.com/install/)
* [ZoKrates](https://github.com/Zokrates/ZoKrates)

# Project Steps

-    :white_check_mark: Clone the project repository
-    Explore the code base.
-    Fill out ERC721 Mintable Contract in ERC721Mintable.sol
-    Write test cases TestERC721Mintable.js
-    Compile and pass test cases in TestERC721Mintable.js
-    Implement Zokrates
     -   Using Docker to install and instantiate a Zokrates zkSnarks development environment
     -   Completes the Zokrates proof in square.code by adding the variable names in square.code
     -   Compile program
     -   Trusted setup
     -   Compute witness
     -   Generate Proof
     -   Export Verifier.sol
     -   Note: This project uses solidity version 0.5.2 so you will be required to update the code in Verifier.sol accordingly based on the compiler errors you receive
-    Write a test script to verify the solidity contract generated by Zokrates executed successfully - TestSquareVerifier.js
-    Write test contract for ZK and ERC721 integration - SolnSquareVerifier.sol
-    Compile and pass with TestSolnSquareVerifier.js
-    Deploy latest contracts generated by Zokrates (a.k.a verifier.sol)
-    Deploy SolnSquareVerifier contract to Rinkeby network
-    Mint 10 tokens
-    Generate OpenSea marketplace
-    Test and Verify OpenSea with your SolnSquareVerifier tokens
     -   List 5 of your tokens on the marketplace
     -   Purchase those 5 tokens using a different address
-    Complete required documentation and submit!