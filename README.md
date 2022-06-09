# DAI Hack

This repo is meant to demonstrate Hardhat forking using the DAI contract.

## Steps

Create a mainnet archival node provider (Alchemy provides this by default, even to free accounts) and input in `.env` and then run the following commands:

```bash
npx hardhat node
# a local JSON RPC node is now running in this shell terminal at `http://127.0.0.1:8545/` and will provide debug logs
# open a new terminal window
npx hardhat run --network localhost scripts/hack-dai.js
```
