Please use Ubuntu LTS for running this code

1. Make changes to the .env file.
Add your Infura project ID
Add metamask wallet keys 

or use mine

export WEB3_INFURA_PROJECT_ID=7510eac2a754478db6ab9a0474b79276

export ETHERSCAN_TOKEN=YourApiToken

export PRIVATE_KEY="0xbd9653f023c1ea605794be1de957cdf2886045ba5c1d31547c6634bd0c57ac69"

2. Run : source .env
3. Install brownie using : pip install eth-brownie
4. Make sure you have DAI coins in your Kovan testnet wallet (or Just use my wallet keys and skip this step)
5. Run this to deploy contracts on Kovan : brownie run scripts/deployment_v2.py --network kovan
6. Run this to execute flashloan : brownie run scripts/run_flash_loan_v2.py --network kovan

https://kovan.etherscan.io/tx/0x746e13689c110a727a629818fb61b7ba3a8babe2b47baf79e9b1c7d7dc5978d8
