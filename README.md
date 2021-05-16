# Create ICO and Smart Contract

Learning ICO and Token creation with Solidity and deploy it on blockchain.

This is a learning code base an this url:

- [Video](https://www.youtube.com/watch?v=d7cf7KomR6o)
- [Repo](https://github.com/jklepatch/eattheblocks/tree/master/screencast/223-personal-tokens)

## How to start

1. create a dir and init a truffle project

```
mkdir myDir && cd myDir
truffle init
```

2. change config

Change solitidy version used bei truffle by changing `truffle-config.js`

```
compilers: {
    solc: {
      version: "0.7.0",
```

3. init npm and instal zeppelin

```
npm init
npm install @openzeppelin/contracts --save

# check truffle version
truffle version
```
