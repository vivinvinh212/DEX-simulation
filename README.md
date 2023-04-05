# Overview

A simulated Decentralized Exchange (DEX) on Ethereum based on Hydro Protocol

- Setup an open source, fully modifyable decentralized exchange on your local server
- Send Ethereum transactions
- Make changes to the front-end UI
- Customize all parts of a DeFi application: change fees, parameters, adding markets, etc.

![web-screen-shot](./assets/hydro_dex_scaffold_screenshot.png)

- Frontend:
  - A Basic Exchange Web UI
  - A modular Ethereum Wallet interface
- Backend:
  - API Server
  - Websocket Server to handle keepalive connections and serve realtime data
  - Matching Engine to send matching orders to the hydro smart contracts on Ethereum
  - Monitoring processes to watch for transaction changes on the blockchain
  - Examples of market making bots, including a Uniswap-like constant price AMM
- [PostgresSQL](https://www.postgresql.org) database
- [ganache-cli](https://github.com/trufflesuite/ganache-cli) to run a local ethereum node and support for ropsten and mainnet
