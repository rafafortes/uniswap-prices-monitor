# Uniswap Prices Monitor

This project includes a bot written in Node.js that monitors the prices of a specific pair on Uniswap.

## Prerequisites

- Node.js v18.17.0 or greater

## Installation

- npm install

## Enviroment variables

- Make sure to setup an Infura API Key on: https://www.infura.io/
- Then finally make sure to fill in the environment variables on the .env file

Example:

INFURA_API_KEY: .... // YOUR INFURA API KEY
INTERVAL: 300000 // 5 Minutes  
NETWORK: goerli // NETWORK NAME
FACTORY_ADDRESS: // POOL FACTORY CONTRACT ADDRESS - https://docs.uniswap.org/contracts/v3/reference/deployments
QUOTER_ADDRESS: // QUOTE CONTRACT ADDRESS - https://docs.uniswap.org/contracts/v3/reference/deployments
TOKEN_IN_ADDRESS: 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2 // WETH
TOKEN_OUT_ADDRESS: 0xdac17f958d2ee523a2206206994597c13d831ec7 // USDT

## Initialization

- npm start

## Disclaimer

The bot has been inspired by the following article:

https://www.luiztools.com.br/post/como-monitorar-precos-de-criptomoedas-na-uniswap-v3/

Thanks to Luiz Tools! :)