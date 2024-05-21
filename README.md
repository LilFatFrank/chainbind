# chainbind
an eth to base erc721 bridge

this is currently a testnet version

## deploy
the deploy functionality means deploying the eth nft contract on base bridge
use case: if the nft you want to bridge to base doesn't have a contract on base
1. enter the eth contract address
2. enter the exact same token name
3. enter the exact same token ticker

if your nft is already deployed on base, this will fail

## bridge
the bridge functionality allows you to bridge a token from eth to base
1. enter the eth contract address
2. select your nft token
3. enter the destination contract address (contract address for the same eth token on base)

this is an attempt to build a truly permissionless bridge

if your nft is not deployed on base but you want to bridge it, feel free to do it yourself!

[ChainBind](https://www.chainbind.xyz)


for testnet, we have also added an eth nft with it's base pair. feel free to mint it and try the bridge!

[sepolia faucet](https://www.alchemy.com/faucets/ethereum-sepolia)
