# Doughnutswap Interface

An open source interface for Doughnutswap -- a protocol for decentralized exchange of Ethereum based tokens.

- Website: [doughnutswap.shop](https://doughnutswap.shop/)
- Interface: [app.doughnutswap.shop](https://app.doughnutswap.shop/)
- Docs: [doughnutswap.shop/docs/](https://docs.doughnutswap.shop)
- Twitter: [@Dough](https://twitter.com/doughnutswap)
- Reddit: [/r/Doughnutswap](https://www.reddit.com/r/doughnutswap/)
- Email: [contact@doughnutswap.shop](mailto:contact@doughnutswap.shop)
- Discord: [Doughnutswap](https://discord.gg/F7ejrjf)
- Whitepapers:
  - [V1](https://hackmd.io/C-DvwDSfSxuh-Gd4WKE_ig)
  - [V2](https://doughnutswap.shop/whitepaper.pdf)
  - [V3](https://doughnutswap.shop/whitepaper-v3.pdf)

## Accessing the Doughnutswap Interface

To access the Doughnutswap Interface, use an IPFS gateway link from the
[latest release]
or visit [app.doughnutswap.shop](https://app.doughnutswap.shop).

## Unsupported tokens

Check out `useUnsupportedTokenList()` in [src/state/lists/hooks.ts](./src/state/lists/hooks.ts) for blocking tokens in your instance of the interface.

You can block an entire list of tokens by passing in a tokenlist like [here](./src/constants/lists.ts) or you can block specific tokens by adding them to [unsupported.tokenlist.json](./src/constants/tokenLists/unsupported.tokenlist.json).

## Contributions

For steps on local deployment, development, and code contribution, please see [CONTRIBUTING](./CONTRIBUTING.md).

## Accessing Doughnutswap V2

The Doughnutswap Interface supports swapping, adding liquidity, removing liquidity and migrating liquidity for Uniswap protocol V2.

- Swap on Uniswap V2: https://app.uniswap.org/#/swap?use=v2
- View V2 liquidity: https://app.uniswap.org/#/pool/v2
- Add V2 liquidity: https://app.uniswap.org/#/add/v2
- Migrate V2 liquidity to V3: https://app.uniswap.org/#/migrate/v2

## Accessing Uniswap V1

The Uniswap V1 interface for mainnet and testnets is accessible via IPFS gateways
linked from the [v1.0.0 release](https://github.com/Uniswap/uniswap-interface/releases/tag/v1.0.0).
