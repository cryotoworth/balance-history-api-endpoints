# balance-history-api-endpoints
Cryptocurrency balance history api endpoints used inside the cryptoworth's coin-service engine.
You can use these endpoints to get wallet balances of cryptocurrency blockchains.

Replace [address] with the wallet address.

| Cryptocurrency        | Addresss           |
| -------------         |:-------------:|
| Bitocoin          | ttps://insight.bitpay.com/api/addr/[address]/?noTxList=1 |
| Bitcoin Cash      | https://bch-chain.api.btc.com/v3/address/[address]      |  
| Bitcoin Gold      | https://btgexplorer.com/api/addr/[address]/?noTxList=1      |  
| Ethereum          | https://api.etherscan.io/api?module=account&action=balance&address=[address]      |  
| Litecoin          | https://chain.so/api/v2/get_address_balance/LTC/[address]     |  
| Ripple            | https://data.ripple.com/v2/accounts/[address]/balances     |  


