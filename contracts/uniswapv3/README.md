# Uniswap V3 Area

Core contracts are from [Uniswap/v3-core](https://github.com/Uniswap/v3-core) with no modification.

Periphery contracts are from [Uniswap/v3-periphery](https://github.com/Uniswap/v3-core) with the following modifications.

1. ERC721Permit Token names changed to Ubeswap in `NonfungiblePositionManager.sol:75`
2. Name has been changed to Ubeswap in `libraries/NFTDescriptor.sol:115`
3. Name has been changed to Ubeswap in `libraries/NFTDescriptor.sol:163`

## Deployed Ubeswap V3 Contracts

- UniswapV3Factory - https://celoscan.io/address/0x67FEa58D5a5a4162cED847E13c2c81c73bf8aeC4
- NonfungiblePositionManager - https://celoscan.io/address/0x897387c7B996485c3AAa85c94272Cd6C506f8c8F
  - NftDescriptorProxy - https://celoscan.io/address/0x6e23691e355703FDE907aA97fE9ACaBb2E4FfE67
  - NftPositionDescriptor - https://celoscan.io/address/0x64422150636683d9b87E1845EDda086EBeFf19EA
- TickLens - https://celoscan.io/address/0x1D8C564cCE485C2f053EF32652E4dba00D4265C4
- V3Migrator - https://celoscan.io/address/0x7167338eA247CC20B7a559Bf171a3dcDb5DE7A8a
- SwapRouter02 - https://celoscan.io/address/0xE389f92B47d913F773254962eD638E12C28aA82d
- MixedRouteQuoterV1 - https://celoscan.io/address/0x1f34a843832044A085bB9cAe48cc7294D5478FAA
- UniversalRouter - https://celoscan.io/address/0x3C255DED9B25f0BFB4EF1D14234BD2514d7A7A0d
- tokenValidator - https://celoscan.io/address/0x4eC243A7d67c7E3F0235A11350f8260f130221d4
- Multicall2 - https://celoscan.io/address/0x4d446f092461A0bfDeBC72AbC831541ca949d63F

## Audit Info

Ubeswap V3 contracts are direct fork of Uniswap V3 contracts so they are battle tested and audited code.

Also we have used Solidity scan for scaning our contracts repository. 

[Solidityscan report](https://solidityscan.com/published-report/project/98873171995978e7)