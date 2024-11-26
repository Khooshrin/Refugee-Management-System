# Refugee-Management-System

Welcome to our Refugee Management System built on blockchain technology! Our platform is designed to securely manage refugee-related data, ensuring integrity and trustworthiness. By leveraging the power of blockchain, we guarantee tamper-proof records and transparent transactions.

# REQUIREMENTS

1.Install nodeJs

* [Node JS](https://nodejs.org/en/download/)

2.Install Ganache

* [Ganache Truffle](https://www.trufflesuite.com/ganache)

3.open Ganache
 
 *  New Workspace
 *  AddProject
 *  Select truffle-config.js in Project Directory
 *  Save Workspace

4. Download IPFS (kubo)

* [IPFS Kubo](https://dist.ipfs.tech/#go-ipfs)

5. Add the HTTP Headers to IPFS config settings 

```
"Access-Control-Allow-Methods": [
"POST",
"GET"
],
"Access-Control-Allow-Origin": [
"*"
]
```

6.Add Metamask Extension in Browser

* [Metamask Chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en-US)

7. open cmd in project directory

```
npm install --force
```

8.open cmd/terminal as Administrator and type

```
npm install -g truffle
```


9.Compile and migrate Contracts
 ```
 truffle migrate
 ```
10. Run Server

```
npm start
```
