
# Hardhat Events_and_Logs 
<br>


**There are 2 kinds of events params: indexed params called topics and non-indexed params** : <br> 

**Indexed params are much easier to query than the non-indexed params. <br>

** Non-indexed params are harder to search for because they are abi-encoded and so you have to know the abi in ordfer to decode them**<br>
**Those non-indexed params cost less gas to pump into the logs.**

**This project demonstrates how to work with events in hardhat. In the `deploy_and_store` script, you'll see the output of the events**. 

 ## Requirements

- [nodejs](https://nodejs.org/en/download/)
  - You can test it's installed by running `node --version`
- [yarn](https://yarnpkg.com/)
  - You can test it's installed by running `yarn --version`
- [git](https://git-scm.com/downloads)
  - You can test it's installed by running `git --version`



**Quickstart**

<br>

Run:
```
npx hardhat run scripts/deploy_and_store.js
```

This will print out the events from our smart contracts. 

## Testnet Goerli Deployment


Create a `.env` file and add the following lines:
```
ETHERSCAN_API_KEY=ABC123ABC123ABC123ABC123ABC123ABC1
GOERLI_RPC_URL=https://eth-goerli.alchemyapi.io/v2/<YOUR ALCHEMY KEY>
PRIVATE_KEY=YOUR_BLOCKCHAIN_WALLET_PRIVATE_KEY



```
<br>  


**Run**:


**yarn  run scripts/deploy_and_store.js --network goerli**


**Testing**: 


**npx hardhat test**


