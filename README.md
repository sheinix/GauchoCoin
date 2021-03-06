# GauchoCoin
## This a test cryptocurrency running on the Ethereum Test network Ropsten

Is meant to be an example of what is on the Ethereum tutorial page of cryptocurrencies https://ethereum.org/token. The same code can be found over there. 

I have put it all together and created the **GauchoCoin** with a limited total supply of 1.000.000 coins with 18 decimals. 


In order to be able to send and receive **GauchoCoin** you have to follow the next steps:

1. Download Ethereum Wallet Mist at https://github.com/ethereum/mist/releases
2. Ensure you are connected to the test network **Ropsten**
3. Go to your Main Account -> Contracts -> Click on "Watch Token"
4. Fill the data for adding a custom token:
  - Token Contract Address: `0x3225F1929814cC19334172cE668eE5C4BD2367f0`
  - Token Name: GauchoCoin
  - Token Symbol: GHC
  - Decimals Places of Smallest Unit: 18
 5. All set up! Now you can receive GauchoCoins and see them on your Ethereum Wallet.
 
 
 NOTE: If you need some Ether on your wallet, you can either mine from your Mist wallet -> Develop Menu -> Start Mining (not recommended) or use an Ethereum faucet like [Metamask]: https://metamask.io

### Executing the Contract

1. Go to your Wallet Account
2. Click on Watch Contract
3. Fill the data for executing the contract:
  - Contract Address: `0x3225F1929814cC19334172cE668eE5C4BD2367f0`
  - Contract Name : GauchoCoin
  - JSON Interface: `...copy and paste the ContractInterface.json file...`
4. Now you should be able to execute some of the Contract Functions
5. You can use the [Ropsten etherscan] : https://ropsten.etherscan.io to check the transactions on the testnet
