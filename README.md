# Etherium-Smart-Contract
Ethereum-testrpc along with the Web3.js Ethereum API to create a web-based UI for interacting with the smart contract.

We have to install MetaMask chrome plugin, which will allow us to connect to the Ropsten test network to more accurately simulate the experience of the dApp on the live Ethereum blockchain. Because of this, we have to install a lite-server in order for MetaMask to inject an instance of the Web3 API. If we don't, MetaMask will not work by just loading our index.html file into the browser straight from the hard drive.

For installing lite-server :

```
npm install lite-server --save-dev
```
 
For accessing localhost:3000
```
npm run dev 
```

For getting Etherium accounts:
```
testrpc
```
