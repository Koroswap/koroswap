# Ubeswap

Ubeswap is a protocol for decentralized exchange and automated liquidity provision on Celo.

https://ubeswap.org

## Deployed Contracts V2

- UniswapV2Factory - https://explorer.celo.org/address/0x62d5b84be28a183abb507e125b384122d2c25fae
- UniswapV2Router02 - https://explorer.celo.org/address/0xe3d8bd6aed4f159bc8000a9cd47cffdb95f96121

## Deployed Contracts V3

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

## Verification

Verified sources are available on [Sourcify](https://sourcify.dev/).

To verify the sources yourself on Sourcify:

1. Run `./verify.sh` from the root directory.
2. For each of `UniswapV2Factory` and `UniswapV2Router02`:
   a. Upload the verified metadata from `deployments/metadata/<Contract Name>/metadata.json`
   b. Upload the sources from `verified-sources/`

### Mainnet

- [Factory](https://repo.sourcify.dev/contracts/full_match/42220/0x62d5b84bE28a183aBB507E125B384122D2C25fAE/)
- [Router](https://repo.sourcify.dev/contracts/full_match/42220/0xE3D8bd6Aed4F159bc8000a9cD47CffDb95F96121/)

### Alfajores

- [Factory](https://repo.sourcify.dev/contracts/full_match/44787/0x62d5b84bE28a183aBB507E125B384122D2C25fAE/)
- [Router](https://repo.sourcify.dev/contracts/full_match/44787/0xE3D8bd6Aed4F159bc8000a9cD47CffDb95F96121/)

## License

MIT
