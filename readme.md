# POC RECREATING PARITY WALLET HACK

POC useful to test harhat mainnet forking feature with pin block number.

## Install 

* install dependencies
```sh
npm install
```

* create .env file 
```sh
touch .env 
```

* get api_key from [alchemy](https://www.alchemy.com/) of ethereum node.

* configure .env file, add ALCHEMY_URL = https://eth-mainnet.alchemyapi.io/v2/API_KEY

## RUN 
```sh
npx hardhat test
```