# Flashloans on AAVE using Brownie

I wrote a code that allows you to borrow millions of dollars of worth of cryptocurrency with no collateral ❕❗ 💰

-

How⁉🧐

-

Transactions on Ethereum are atomic. As long as the loan is repaid in the same transaction block, users can borrow as much money as they want. If not, the loan fails. Below is the code with instructions. 🐱‍💻

-

Exploit the benefits using arbitrage trade or loan swaps. 💹

-

#ethereumblockchain #smartcontracts #solidity

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Brownie.

```bash
pip install eth-brownie
```

## Setting up the wallet

```bash
pip install eth-brownie
```
1. Make changes to the .env file. 


i. Add your Infura project ID.

ii. Add metamask wallet keys.

```python
export WEB3_INFURA_PROJECT_ID=7510bds2a754478db6ab9a0474b79276 # Add your Infura project.
export PRIVATE_KEY="0xbd9653f023c1ea608884be1de957cdf2886045ba5c1d31547c6634bd0c57ac69" # Export your private key from metamask.
```
iii. Save the file and run the below code.

```bash
source .env
```
2. Make sure you have DAI coins in your test wallet. (I'm using kovan)

```bash
brownie run scripts/deployment_v2.py --network kovan
```

```bash
brownie run scripts/run_flash_loan_v2.py --network kovan
```



## Contributing
Please use Ubuntu LTS for running this code

## Etherscan Transaction Prood
[$1 Flashloan on Kovan Test Net](https://kovan.etherscan.io/tx/0x746e13689c110a727a629818fb61b7ba3a8babe2b47baf79e9b1c7d7dc5978d8)
