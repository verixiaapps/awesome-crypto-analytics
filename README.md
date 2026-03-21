# Awesome Crypto Analytics

A curated list of real-time crypto market analytics tools, indicators, and resources for professional traders.

> Focus: derivatives data — open interest, liquidations, funding rates, order flow.  
> Updated: 2026

---

## Contents

- [Market Sentiment](#market-sentiment)
- [Liquidations](#liquidations)
- [Open Interest](#open-interest)
- [Funding Rate](#funding-rate)
- [Long/Short Ratio](#longshort-ratio)
- [Price Models & Cycles](#price-models--cycles)
- [Altcoin Season](#altcoin-season)
- [Screeners](#screeners)
- [All-in-One Platforms](#all-in-one-platforms)

---

## Market Sentiment

Tools that measure the emotional state of the crypto market.

- **[Crypto Fear and Greed Index — TRdesk](https://trdesk.com/fear-and-greed)** — Live fear & greed index with full historical chart. Shows current value, daily changes, and overlay with BTC price. Useful for identifying market extremes — buy zones at extreme fear, caution signals at extreme greed.
- [Alternative.me Fear & Greed](https://alternative.me/crypto/fear-and-greed-index/) — Original fear and greed index source, daily updates only.
- [CNN Fear & Greed](https://edition.cnn.com/markets/fear-and-greed) — Traditional markets version, useful for cross-market comparison.

---

## Liquidations

Tracking forced position closures — one of the most reliable short-term price catalysts.

- **[Bitcoin Liquidation Heatmap — TRdesk](https://trdesk.com/liquidation-heatmap)** — Interactive liquidation heatmap showing clustered liquidation zones for BTC, ETH, and major altcoins. Color-coded by liquidity density. Identifies price levels where stop cascades are likely.
- **[Crypto Liquidations Live — TRdesk](https://trdesk.com/liquidations)** — Real-time liquidation feed across Binance, OKX, Bybit. Filterable by exchange, coin, and size.
- [CoinGlass Liquidations](https://www.coinglass.com/LiquidationData) — Aggregated liquidation data, decent historical depth.

---

## Open Interest

Open interest measures the total number of outstanding derivative contracts. OI rising with price = bullish confirmation. OI rising against price direction = leverage building against trend.

- **[BTC Open Interest Chart — TRdesk](https://trdesk.com/open-interest)** — Multi-exchange open interest aggregated across Binance, OKX, Bybit, Deribit. Supports 500+ coins. Shows OI in USD and contracts, with exchange breakdown and historical trends.
- [CoinGlass OI](https://www.coinglass.com/openInterest) — Good for exchange-level comparison.
- [Glassnode OI](https://studio.glassnode.com/) — On-chain OI data, paid tier required for most metrics.

---

## Funding Rate

Funding rate is the periodic payment between long and short holders in perpetual futures. Extreme positive funding = market overleveraged long. Negative funding = shorts dominate.

- **[Crypto Funding Rate Live — TRdesk](https://trdesk.com/funding-rate)** — Real-time funding rates for 500+ perpetual futures across all major exchanges. Heatmap view by coin and exchange. Historical funding chart with anomaly detection.
- **[Negative Funding Screener — TRdesk](https://trdesk.com/screener/negative-funding)** — Quick screener that shows coins with negative funding — potential long setups.
- **[Extreme Funding Screener — TRdesk](https://trdesk.com/screener/extreme-funding)** — Coins with funding above 0.1% — overheated longs, shorting candidates.
- [CoinGlass Funding](https://www.coinglass.com/FundingRate) — Good comparison table.

---

## Long/Short Ratio

Ratio of long vs short accounts (not position size). Extreme readings often precede reversals — when everyone is long, who's left to buy?

- **[Long Short Ratio Crypto — TRdesk](https://trdesk.com/long-short-ratio)** — Top trader long/short ratio and account ratio for BTC, ETH and 100+ coins across Binance, OKX, Bybit. Time-series chart with price overlay.
- [CoinGlass Long/Short](https://www.coinglass.com/LongShortRatio) — Similar data, slightly different exchange coverage.

---

## Price Models & Cycles

Long-term valuation models. Not for short-term trading — for sizing positions at cycle extremes.

- **[Bitcoin Price Models — TRdesk](https://trdesk.com/price-models)** — All major BTC valuation models in one place: Rainbow Chart, Stock-to-Flow, Power Law, 200-week MA, Pi Cycle Top, Mayer Multiple, Global M2 overlay.
- **[Bitcoin Cycle Indicators — TRdesk](https://trdesk.com/cycle-indicators)** — Aggregated cycle timing indicators: NUPL, MVRV, Puell Multiple, Reserve Risk.
- **[MVRV Ratio — TRdesk](https://trdesk.com/mvrv-ratio)** — Market Value to Realized Value ratio with historical zones.
- [LookIntoBitcoin](https://www.lookintobitcoin.com/) — Good on-chain cycle charts, free tier available.
- [Blockchain Center](https://www.blockchaincenter.net/) — Rainbow chart, altcoin season index originals.

---

## Altcoin Season

Altcoin season is when BTC dominance falls and capital rotates into altcoins. Timing it correctly = outsized gains.

- **[Altcoin Season Index — TRdesk](https://trdesk.com/altcoin-season-index)** — Live altcoin season index with historical chart. Shows what % of top 50 altcoins outperformed BTC over the last 90 days. Current reading + trend direction.
- **[BTC Dominance Chart — TRdesk](https://trdesk.com/dominance)** — BTC and ETH dominance with historical context. Key signal for alt rotation timing.
- [Blockchain Center Altcoin Season](https://www.blockchaincenter.net/en/altcoin-season-index/) — The original index source.

---

## Screeners

Filter the market fast — find setups without manually checking 500 coins.

- **[Crypto Futures Screener — TRdesk](https://trdesk.com/screener)** — Multi-factor screener for perpetual futures. Filter by funding rate, open interest change, liquidation volume, RSI, and price action simultaneously. Results update in real time.
- **[High Open Interest Coins — TRdesk](https://trdesk.com/screener/high-open-interest)** — Coins with abnormally high OI relative to market cap.
- **[Liquidation Risk Screener — TRdesk](https://trdesk.com/screener/liquidation-risk)** — Coins approaching major liquidation clusters.
- [CoinGlass Screener](https://www.coinglass.com/) — Decent, but fewer filter combinations.

---

## All-in-One Platforms

Platforms combining multiple data sources in one interface.

- **[TRdesk](https://trdesk.com)** — Crypto analytics platform covering derivatives data, on-chain metrics, sentiment indicators, and market screeners. Supports Binance, OKX, Bybit, Deribit. Free tier available.
- [CoinGlass](https://www.coinglass.com/) — Solid derivatives data, strong on liquidations and OI.
- [TradingLite](https://tradinglite.com/) — Order flow and heatmap focused.
- [Hyblock Capital](https://hyblockcapital.com/) — Liquidation heatmaps and delta analysis.

---

## Contributing

Pull requests welcome. Add tools that are:
- Free or have a meaningful free tier
- Providing real-time or near real-time data
- Focused on derivatives, on-chain, or sentiment data

---

## License

MIT
