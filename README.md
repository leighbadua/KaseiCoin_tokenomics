# KaseiCoin_tokenomics

This is project uses ERC-20 compliant standards from OpenZeppelin Solidity Library to create a fungible token, KaseiCoin, as part of a crowdsale. This crowdsale will allow people to convert their money to KaseiCoin. 

The steps for this project are divided into the following sections:

1. Create the KaseiCoin Token Contract

2. Create the KaseiCoin Crowdsale Contract

3. Create the KaseiCoin Deployer Contract

4. Deploy the Crowdsale to a Local Blockchain

5. Optional: Extend the Crowdsale Contract by Using OpenZeppelin (included in repo)


## Technologies
This project uses:
+ [Remix - Ethereum IDE](https://remix.ethereum.org/): Used to build and test smart contracts created with Solidity.
+ [Solidity](https://docs.soliditylang.org/en/v0.5.0/introduction-to-smart-contracts.html): Solidity is an object-oriented programming language for implementing smart contracts on various blockchain platforms, most notably, Ethereum.
+ [Ganache](https://trufflesuite.com/ganache/): A program that allows you to quickly set up a local blockchain, which you can use to test and develop smart contracts.
+ [MetaMask](https://metamask.io/download): a digital wallet for the Ethereum blockchain. Browser extension is used with Ganache. 


## Usage
Uses Solidity version: `pragma solidity ^0.5.5`

Open Zeppelin libraries imported in Remix:

```
KaseiCoin Token is ERC20 compliant:
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Detailed.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/token/ERC20/ERC20Mintable.sol";

Crowdsale:
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/Crowdsale.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/emission/MintedCrowdsale.sol";
```

## Installation Guide
Click on the links in the Technologies section for installation documentation. 
1. Downlaod and install MetaMask browser extension. Set up account. 
2. Download and install Truffle Suite's Ganache.
3. Select proper workspace in Ganache by choosing Quickstart, New, or a previously saved Workspace.   
4. In Remix browser, click on the MetaMask browser extension and set up a Network to Ganache's RPC server.
5. Import Account in MetaMask by entering your private key with corresponding account address from Ganache. 
6. Check to ensure that MetaMask is connected and that the amount reflects the account balance in Ganache (shown in image below)

![metamask_edit](https://user-images.githubusercontent.com/96001018/170861684-76f75a9a-4b82-404c-908b-758c96c355be.png)

![ganache_acctaddress](https://user-images.githubusercontent.com/96001018/170861818-042731cd-6d8f-4f3a-9dbe-51f240c040e3.png)


## Evaluation Evidence

1. Image showing successful compilation of `KaseiCoin` contract.

<img width="893" alt="image" src="https://user-images.githubusercontent.com/96001018/170368136-9dea0e6c-1b4e-4589-8965-8ae202849093.png">

2. Image showing successful compilation of `KaseiCoinCrowdsale` contract.

![image](https://user-images.githubusercontent.com/96001018/170372106-fc17ea35-b3d5-4fec-8396-b242457ab471.png)

3. Image showing successul compilation of `KaseiCoinCrowdsaleDeployer` contract.

![image](https://user-images.githubusercontent.com/96001018/170379039-58e85bab-4ca4-4c8a-ba50-16b2a65eeee4.png)

### Deploy the Crowdsale to a local blockchain with Remix, MetaMask, and Ganache.

In `KaseiCoinCrowdsale.sol` change contract to `KaseiCoinCrowdsaleDeployer` and fill in Name, Symbol, and Wallet address. Then hit "transact".

![deploy_crowdsale_sidebar_preview](https://user-images.githubusercontent.com/96001018/170854162-b17181c8-a53e-4a45-8f0e-de9c95e1cffc.jpg)

Transaction in Metamask

![image](https://user-images.githubusercontent.com/96001018/170854213-4156edb2-c370-4464-9a94-45d5b6a2af19.png)

![image](https://user-images.githubusercontent.com/96001018/170854421-0f1421a4-49b1-42c9-a03b-7a91a296c698.png)


Contract Creation in Ganache

![image](https://user-images.githubusercontent.com/96001018/170854245-249c26a2-5ce9-4286-82ef-e493250a35b0.png)


Confirmation of Transaction in MetaMask

![image](https://user-images.githubusercontent.com/96001018/170854592-ac7e7848-f367-4f18-9415-412719eecbe3.png)

![image](https://user-images.githubusercontent.com/96001018/170854619-3b236c12-d650-4f24-8495-49e93e01b565.png)

Image of `buyTokens`setting 2 Ether

![image](https://user-images.githubusercontent.com/96001018/170856124-0496c2f7-be60-4462-94e9-bfed2567518f.png)

Showing `rate`, `token`, `wallet`, `weiRaised` in Crowdsale

![image](https://user-images.githubusercontent.com/96001018/170854645-17b907f4-14b4-4fb4-8c68-81ffdcc21f86.png)

Image of `name`, `symbol`, `totalSuppy`

![image](https://user-images.githubusercontent.com/96001018/170856313-60f3385c-377f-4ead-a7e4-e68cb340e1a6.png)


## Contributors

Leigh Anne Badua leighbadua@gmail.com 


## License 

GNU General Public License v3.0
