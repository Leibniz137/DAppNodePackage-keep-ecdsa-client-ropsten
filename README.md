# Keep ECDSA Dappnode Package
This dappnode package will allow you to participate in the keep ropsten testnet.
see: https://keep.network/

## Install
Access this link using your dappnode wifi:
http://my.dappnode/#/installer/%2Fipfs%2FQmWh5o98xojFQyw785TsBUnNfCEA3eU9xQtadcy5mDAb94

current ipfs hash `QmWh5o98xojFQyw785TsBUnNfCEA3eU9xQtadcy5mDAb94`

## Quick Start
1. Set `KEEP_ETHEREUM_PASSWORD` and `PEERS` environment variables in config.

Note, peers should be a comma-delimited string with no spaces or quotation marks, eg:
```
/dns4/ecdsa-2.test.keep.network/tcp/3919/ipfs/16Uiu2HAmNNuCp45z5bgB8KiTHv1vHTNAVbBgxxtTFGAndageo9Dp,/dns4/ecdsa-3.test.keep.network/tcp/3919/ipfs/16Uiu2HAm8KJX32kr3eYUhDuzwTucSfAfspnjnXNf9veVhB12t6Vf
```
2. Copy operator address from package logs
3. GOTO https://dashboard.keep.network/
4. Delegate your keep tokens to the operator address
5. Authorize all 3 contracts (random beacon, ecdsa, tBTC)
6. Send the operator address some ropsten eth (0.001 eth is fine)
7. Wait for ropsten to sync
