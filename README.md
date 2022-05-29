# KaseiCoin_tokenomics

This is project uses ERC-20 compliant standards from OpenZeppelin Solidity Library to create a fungible token, KaseiCoin, as part of a crowdsale. This crowdsale will allow people to convert their money to KaseiCoin. 

The steps for this project are divided into the following sections:

1. Create the KaseiCoin Token Contract

2. Create the KaseiCoin Crowdsale Contract

3. Create the KaseiCoin Deployer Contract

4. Deploy the Crowdsale to a Local Blockchain

5. Optional: Extend the Crowdsale Contract by Using OpenZeppelin (included in repo)


### Evaluation Evidence

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
