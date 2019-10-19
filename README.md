# CoffeeChain - SupplyChainApp 
by James Kwon Lee - 10.19.19

CoffeeChain utilizes Ethereum's blockchain to package, sell, purchase, ship, etc. and implement other actions in the Supply Chain of a Coffee Business, from Farmer to Consumer. 

Try out my website in Seven Easy Steps:

1) Note the versions used, update/download as needed:
    Truffle v5.0.34 (core: 5.0.34)
    Solidity v0.5.8 (solc-js)
    Node v10.16.3
    Web3.js v1.2.1
    
2) Make sure you download the following libraries/dependencies:
    "truffle-hdwallet-provider": "^1.0.17"
    "lite-server": "^2.4.0"

3) Under truffle.js, please input your metamask seed in the variable, "const mnemonic", and also input your infurakey in the variable "const infuraKey". 

4) Open terminal , then input the following commands: 
    a) truffle develop
    b) compile
    c) migrate --reset --network rinkeby
    
5) Open a new tab in the terminal, make sure you are in the src directory of the file, then type: 
    a) npm run dev
    
6) Website should open automatically, if not, type this in the URL: http://localhost:3000/
    
7) Here's how you can see the contract address on the Rinkeby Test Network: 
    a) Go to https://rinkeby.etherscan.io
    b) Input the following Rinkeby Contract Address in search bar: 0x354Add35af584CF97A2fA537C4B09157F7b5788C



## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open. 
--NOTE: IFPS was not implemented, but will be in the future. 
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

See also the list of [contributors](https://github.com/your/project/contributors.md) who participated in this project.

## Acknowledgments

* Solidity
* Ganache-cli
* Truffle
* IPFS
