# AVALYNXLinkFeeds
Using Chainlink Price Feeds on Avalanche

## Quickstart
1. Head over to [`remix`](https://remix.ethereum.org/)
2. Create a new file
3. Paste the code from `AVALYNXLinkFeeds.sol` into a new file in remix. 
4. Compile using `0.8.0` version of solidity or above. 
5. Setup your Metamask to work with Avalanche:
```
Network Name: Avalanche FUJI C-Chain  
New RPC URL: https://api.avax-test.network/ext/bc/C/rpc  
ChainID: 43113  
Symbol: AVAX  
Explorer: https://cchain.explorer.avax-test.network  
```
5. Deploy the contract with "Injected Web3" environment
6. Run "getLatestPrice" to retrieve price data
