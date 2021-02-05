# United States

The United States proves to be one of the most complex regulatory environments with respect to tokens and digital assets. Comments and policies by regulators tend to change rapidly and without warning.

Based on this, a prudent approach is to assess if a token readily available on the market, being offered from firms which are well managed, regulated and have clear policies on token availability. In adhering to this approach, there will be no meaningful additional access to the US market of these tokens or assets.

# Comments by Regulatory Agencies

## Secutities and Exchange Comission

 1. [ Statement on Digital Assets and Trading ](https://www.sec.gov/news/public-statement/digital-asset-securites-issuuance-and-trading)
- Based on this assessment, additional care is to be taken being taken with respect to utility tokens, as they may be classified as securities

2. [Remarks by William Hinman](https://www.sec.gov/news/speech/speech-hinman-061418)

> putting aside the fundraising that accompanied the creation of Ether, based on my understanding of the present state of Ether, the Ethereum network and its decentralized structure, current offers and sales of Ether are not securities transactions

 - Based on these statements, a token that has completed a fundraise is not necessarily a security; ethereum completed a fundraise, but is not at this time a security.

## Unlawful Internet Gambling Enforcement Act of 2006

In 2006 the United States congress passed what is now known as [UIGEA](https://www.fdic.gov/news/news/financial/2010/fil10035a.pdf), which imposes severe restrictions on online gaming and gambling. Tokens that are designed specifically to assist in or facilitate online gambling may be considered to be:

> (i) automated clearing house (ACH) systems, (ii) card systems, (iii) check collection systems, (iv) money transmitting businesses, and (v) wire transfer systems.

# Comments by Regulated Businesses

## Coinbase
Last Updated July 17, 2019

[Coinbase Listing Policy](https://listing.coinbase.com/policy#legal-compliance)

> The asset is not classified as a security using Coinbase's Securities Law Framework.

#### Coinbase Tokens Available

- [New Digital Assets](https://blog.coinbase.com/coinbase-continues-to-explore-support-for-new-digital-assets-92ba4ab7f465)
- [Supported Digital Currencies](https://support.coinbase.com/customer/en/portal/articles/2630943-supported-digital-currencies)
- Coinbase does restrict certain assets from residents of New York State
- Coinbase has also removed all trading functionality of MKR and ZIL

## Kraken
Last Updated November 11, 2020

- [Kraken Terms and conditions](https://www.kraken.com/legal)
- "Kraken does not offer securities services, is not registered under the securities laws of any jurisdiction and the provision of the Off-chain Staking Program has not been and will not be registered under the securities laws of any jurisdiction or otherwise approved by securities regulators in any jurisdiction."
#### Kraken Tokens Available    
- [List of tokens available on Kraken](https://api.kraken.com/0/public/Assets)

## Gemini
Last updated November 11, 2020

- [Gemini Terms and Conditions](https://gemini.com/legal/user-agreement)
#### Gemini Tokens Available   
- [List of tokens available on Gemini](https://support.gemini.com/hc/en-us/articles/115005868106-What-digital-assets-are-supported-on-the-Gemini-Exchange-)


# The List

Below is a list of tokens which are readily available to the US market from the companies listed above. This list available as a [JSON](https://raw.githubusercontent.com/go-faast/tokenCuration/master/US/US.json) and can be pulled in via script for automation.

| **Name**                   | **Symbol**| **Mined**| **Category**| **Companies Approved**            | **Contract Address (if ERC20 Token)**      |
|----------------------------|--------|-------|-----------------|-------------------------------------|--------------------------------------------|
| 0x Protocol                | ZRX    | FALSE | Swap            | ["Coinbase", "Kraken", "Gemini"]    | 0xE41d2489571d322189246DaFA5ebDe1F4699F498 |
| Aave Protocol              | AAVE   | FALSE | Defi Platform   | ["Coinbase", "Kraken", "Gemini"]    | 0x7Fc66500c84A76Ad7e9c93437bFc5Ac33E2DDaE9 |
| Augur v2                   | REPV2  | FALSE | Prediction Market| ["Coinbase", "Kraken"]             | 0x221657776846890989a759BA2973e427DfF5C9bB |
| Basic Attention Token      | BAT    | FALSE | App             | ["Coinbase", "Kraken", "Gemini"]    | 0x0D8775F648430679A709E98d2b0Cb6250d2887EF |
| Bitcoin Cash               | BCH    | TRUE  | Cryptocurrency  | ["Coinbase", "Kraken", "Gemini"]    |                                            |
| Bitcoin                    | BTC    | TRUE  | Cryptocurrency  | ["Coinbase", "Kraken", "Gemini"]    |                                            |
| Binance USD                | BUSD   | FALSE | Stable Coin     | ["Paxos"]                           | 0x4Fabb145d64652a948d72533023f6E7A623C7C53 |
| Compound                   | COMP   | FALSE | Defi Platform   | ["Coinbase", "Kraken", "Gemini"]    | 0xc00e94Cb662C3520282E6f5717214004A7f26888 |
| ChainLink                  | LINK   | FALSE | Data Publishing | ["Coinbase", "Kraken", "Gemini"]    | 0x514910771af9ca656af840dff83e8264ecf986ca |
| DAI Stablecoin             | DAI    | FALSE | Stable Coin     | ["Coinbase", "Kraken", "Gemini"]    | 0x6B175474E89094C44Da98b954EedeAC495271d0F |
| Dogecoin                   | DOGE   | TRUE  | Cryptocurrency  | ["Kraken"]                          |                                            |
| Ethereum                   | ETH    | TRUE  | Smart Contracts | ["Coinbase", "Kraken", "Gemini"]    |                                            |
| Golem                      | GNT    | FALSE | Computing       | ["Coinbase"]                        | 0xa74476443119A942dE498590Fe1f2454d7D4aC0d |
| Maker                      | MKR    | FALSE | Defi Platform   | ["Coinbase", "Gemini"]              | 0x9f8F72aA9304c8B593d555F12eF6589cC3A579A2 |
| Litecoin                   | LTC    | TRUE  | Cryptocurrency  | ["Coinbase", "Kraken", "Gemini"]    |                                            |
| Decentraland               | MANA   | FALSE | App             | ["Coinbase", "Kraken", "Gemini"]    | 0x0f5d2fb29fb7d3cfee444a200298f468908cc942 |
| Paxos Standard             | PAX    | FALSE | Stable Coin     | ["Paxos"]                           | 0x8e870d67f660d95d5be530380d0ec0bd388289e1 |
| Paxos Gold                 | PAXG   | FALSE | Stable Coin     | ["Paxos"]                           | 0x45804880De22913dAFE09f4980848ECE6EcbAf78 |
| Synthetix                  | SNX    | FALSE | Defi Platform   | ["Coinbase", "Kraken", "Gemini"]    | 0xc011a73ee8576fb46f5e1c5751ca3b9fe0af2a6f |
| Tron                       | TRX    | TRUE  | Smart Contracts | ["Kraken"]                          |                                            |
| TrueUSD                    | TUSD   | FALSE | Stable Coin     | ["TrustToken"]                      | 0x0000000000085d4780B73119b644AE5ecd22b376 |
| USD Coin                   | USDC   | FALSE | Stable Coin     | ["Coinbase", "Kraken"]              | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48 |
| Tether USD                 | USDT   | FALSE | Stable Coin     | ["Kraken"]                          | 0xdAC17F958D2ee523a2206206994597C13D831ec7 |
| Stellar                    | XLM    | TRUE | Cryptocurrency   | ["Kraken", "Bittrex", "Coinbase"]   |                                            |
| Monero                     | XMR    | TRUE | Cryptocurrency   | ["Kraken"]                          |                                            |
| Uniswap                    | UNI    | FALSE | DeFi            | ["Gemini", "Coinbase", "Kraken"]    | 0x1f9840a85d5aF5bf1D1762F925BDADdC4201F984 |
| Wrapped Bitcoin            | WBTC   | FALSE | Stable Coin     | ["CoinList"]                        | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599 |
| Yearn.finance              | YFI    | FALSE | DeFi            | ["Coinbase", "Gemini", "Kraken"]    | 0x0bc529c00C6401aEF6D220BE8C6Ea1667F6Ad93e |
| Zcash                      | ZEC    | TRUE | Cryptocurrency   | ["Coinbase", "Gemini", "Kraken"]    |                                            |
