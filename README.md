# BitOMC - Bringing Price Stability to the Bitcoin Economy

<em>Minting begins on block 854,500 (est. Monday 7/29/24)</em>

BitOMC is a metaprotocol that defines a more stable unit of account for Bitcoin payments.

## Intro
In a world with ever-changing economic conditions, Bitcoin's fixed supply makes it unattractive as a unit of account in contracts where payment is due in the future. BitOMC addresses this by defining a market-driven unit of account that can facilitate price stability in a Bitcoin economy, without changing Bitcoin's core protocol. Using two interconvertible assets, Tighten and Ease, BitOMC establishes a dynamic interest rate and a new unit of Bitcoin called the "util". This system allows for more predictable Bitcoin-settled payments, potentially accelerating Bitcoin's adoption in commerce while preserving its fundamental properties as a store of value.

## Economics
Demand for risk-off assets rises and falls with changing economic conditions. When there is more demand for investment, risk-off assets are sold, and when there is less, risk-off assets are purchased. A future economy where Bitcoin is the risk-off asset will be no different. The interplay between demand for Bitcoin versus investment in this economy will be governed by the real rate of interest, or the real rate of return on Bitcoin. A neutral authority that provides a reliable estimate of this value can define a floating unit of Bitcoin whose purchasing power is relatively stable.

## How It Works
BitOMC is a fork of the Runes protocol, consisting of two interconvertible assets, Tighten and Ease, which users can convert between according to a constant function conversion rule. This keeps the system in balance and ensures the conversion rate reflects their relative market price. This conversion rate determines a dynamic interest rate, which in turn defines a floating unit of Bitcoin called the "util". Transactions continue to settle in Bitcoin, but parties seeking greater price stability may choose to denominate their contracts in "utils" rather than BTC or a fiat currency.

BitOMC is not premined. Users can mint Tighten and Ease once per block according to the same four-year halving schedule as Bitcoin. To limit network congestion and MEV, mint and conversion transactions leave a small anchor output, which must be spent by the next respective transaction.

## Implementation
- The [official BitOMC implementation](https://github.com/BitOMC/BitOMC) in Rust

## Resources
- [BitOMC whitepaper](bitomc.pdf)
- [BitOMC Telegram group](https://t.me/bitOMC_chat)
- [BitOMC docs](https://github.com/BitOMC/BitOMC/blob/master/docs/src/SUMMARY.md)
- [BitOMC organization on Github](https://github.com/BitOMC)

### Want to Contribute?
- Join the [Telegram group](https://t.me/bitOMC_chat)
