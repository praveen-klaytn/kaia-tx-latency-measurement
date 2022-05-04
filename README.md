# Transaction Latency Measurement

### 1) Introduction 
Using this repo, you can measure transaction latency on Solana mainnet-beta, Avalanche C-chain, Polygon PoS, and Klaytn mainnet. Transaction latency is measured by sending a simple value transfer transaction through public RPC url provided by each chain. Each subdirectory is for each different blockchain platform. Codes for other chains will be updated.

### 2) Getting Started 
1. Open terminal 
2. Clone the repo by running `https://github.com/klaytn/tx-latency-measurement.git`
3. `cd tx-latency-measurement/{BlockchainName}-tx-latency-measurement` by selecting which blockchain you want to measure.  
4. Copy and paste `.env.template` file. Then rename it to `.env` and update variables with your Private key, url of blockchain explorer, and public rpc url.
6. Run `npm install` to install node packages.
7. Run `node sendtx-{BlockchainName}.js`. 
