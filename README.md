<p align="center">
  <a href="" rel="noopener">
 <img width=450px height=200px src="https://github.com/farid786/bchain/blob/master/src/assets/img/github-project-logo.png" alt="Project logo"></a>
</p>

<h3 align="center">Blockchain Demo</h3>

<div align="center">

  [![Build Status](https://travis-ci.org/Savjee/savjeecoin-frontend.svg?branch=master)](https://travis-ci.org/farid786/bchain)
  [![GitHub Issues](https://img.shields.io/github/issues/farid786/bchain.svg)](https://github.com/farid786/bearclaw/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/farid786/bchain.svg)](https://github.com/farid786/bearclaw/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---


Angular application that allows you to interact with a blockchain. You can see the blocks on chain, see transaction within them and even create new transactions and mine blocks.

Built on top of [bchain](https://github.com/Savjee/SavjeeCoin) (simply Blockchain implementation in Javascript).

## 👀 Live demo
**[Check it out here.](https://farid786.github.io/bchain/)** You can create transactions, mine blocks and explore your own blockchain.

## 🏁 Getting Started <a name = "getting_started"></a>
Get a copy of the bchain running on your local machine (for playing around, testing or development).

```
git clone https://github.com/farid786/bchain.git
```

Install the dependencies:
```
cd bchain
npm install
```

Run the application:
```
npm start
```

At this point the application should be running on your machine on [http://localhost:4200](http://localhost:4200)


## 📸 Screenshots

**Home page:** Seeing blocks on the chain & exploring transactions in each block.
![](https://farid786.github.io/bchain/assets/screenshots/blockchain-overview.png)

**Creating new transactions:** You can create new transactions to any wallet for any amount (no validation). New transactions will be added to the "pending transactions", ready to be included in the next block.
![](https://farid786.github.io/bchain/assets/screenshots/create-new-transactions.png)

**Pending transactinos:** List of all pending transactions. These will be included in the next block when the mining process starts.
![](https://farid786.github.io/bchain/assets/screenshots/pending-transactions.png)

**Wallet details:** You can click on any wallet address and see an overview of that wallet: its current balance and all transaction to/from that wallet.
![](https://farid786.github.io/bchain/assets/screenshots/wallet-details.png)

*⚠️This is for educational purposes only. This is by no means a complete blockchain implementation (nor does it aim to be one). Use it to learn how blockchains operate.*
