# Awesome Crypto Payment Gateways [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of crypto payment gateways, SDKs, integration resources, and guides for merchants and developers.

Maintained by [CryptoPayHub](https://cryptopayhub.net) — independent reviews and integration guides for crypto payment infrastructure.

---

## Contents

- [Payment Gateways](#payment-gateways)
- [Self-Hosted Solutions](#self-hosted-solutions)
- [SDKs & Libraries](#sdks--libraries)
- [Stablecoin Payment Solutions](#stablecoin-payment-solutions)
- [Fiat On/Off Ramps](#fiat-onoff-ramps)
- [Resources & Guides](#resources--guides)
- [Community](#community)

---

## Payment Gateways

### Full-Service (Custodial)

| Gateway | Coins | Fiat Settlement | KYC | Pricing |
|---------|-------|-----------------|-----|---------|
| [BitPay](https://bitpay.com) | BTC, ETH, LTC, DOGE, stablecoins + more | ✅ 40+ currencies | Required | 1% per tx |
| [Coinbase Commerce](https://commerce.coinbase.com) | BTC, ETH, LTC, DOGE, USDC, DAI | ✅ USD, EUR | Required | 1% per tx |
| [NOWPayments](https://nowpayments.io) | 300+ coins | ✅ via exchange | Optional | 0.5% per tx |
| [CoinGate](https://coingate.com) | 70+ coins | ✅ EUR, USD, GBP | Required | 1% per tx |
| [CoinsPaid](https://coinspaid.com) | 50+ coins | ✅ Multi-currency | Required | 0.8% per tx |
| [Plisio](https://plisio.net) | 20+ coins | ✅ Limited | Optional | 0.5% per tx |
| [MoonPay](https://moonpay.com) | 100+ coins | ✅ Multi-currency | Required | Variable |
| [TripleA](https://triple-a.io) | BTC, ETH, USDT, USDC | ✅ 20+ currencies | Required | 0.8% per tx |
| [Confirmo](https://confirmo.net) | BTC, LTC, ETH, USDT | ✅ EUR, CZK | Required | 0.5% per tx |
| [Blockonomics](https://blockonomics.co) | BTC | ❌ Direct to wallet | None | 1% per tx |

### Non-Custodial / Privacy-Focused

| Gateway | Coins | KYC | Notes |
|---------|-------|-----|-------|
| [BTCPay Server](https://btcpayserver.org) | BTC, LTC, XMR + Lightning | None | Open source, self-hosted |
| [Blockonomics](https://blockonomics.co) | BTC | None | Direct-to-wallet payments |
| [GoUrl](https://gourl.io) | BTC, LTC, DASH, and more | None | WordPress plugin available |

> 📖 **Detailed comparison:** [Best Crypto Payment Gateways 2026](https://cryptopayhub.net/best-crypto-payment-gateway) — tested with real merchant accounts.

## Self-Hosted Solutions

- [BTCPay Server](https://github.com/btcpayserver/btcpayserver) — Self-hosted, open-source payment processor. Supports BTC, Lightning, Liquid, and altcoins.
- [SatSale](https://github.com/nickfarrow/SatSale) — Lightweight, self-hosted Bitcoin payment processor.
- [CypherpunkPay](https://cypherpunkpay.org) — Privacy-focused, self-hosted payment gateway.
- [Bitcart](https://github.com/bitcart/bitcart) — Open-source cryptocurrency payment processor with admin panel.

> 📖 **Build guide:** [Crypto Payment Gateway Development](https://cryptopayhub.net/crypto-payment-gateway-development) — architecture, tech stack, and cost analysis.

## SDKs & Libraries

### JavaScript / Node.js
- [bitpay-sdk](https://github.com/bitpay/nodejs-bitpay-client) — Official BitPay Node.js client
- [coinbase-commerce-node](https://github.com/coinbase/coinbase-commerce-node) — Official Coinbase Commerce SDK
- [nowpayments-api](https://www.npmjs.com/package/@nowpaymentsio/nowpayments-api-js) — NOWPayments JavaScript SDK

### Python
- [bitpay-python](https://github.com/bitpay/bitpay-python) — Official BitPay Python client
- [coinbase-commerce-python](https://github.com/coinbase/coinbase-commerce-python) — Official Coinbase Commerce SDK
- [python-bitcoinlib](https://github.com/petertodd/python-bitcoinlib) — Low-level Bitcoin protocol library

### PHP
- [bitpay-php](https://github.com/bitpay/php-bitpay-client-v2) — Official BitPay PHP client
- [coingate-php](https://github.com/coingate/coingate-php) — Official CoinGate PHP client

### E-Commerce Plugins
- [BTCPay for WooCommerce](https://github.com/btcpayserver/woocommerce-plugin) — WooCommerce integration
- [BitPay for Magento](https://github.com/bitpay/bitpay-magento2-plugin) — Magento 2 plugin
- [NOWPayments for Shopify](https://nowpayments.io/payment-integration/shopify-plugin) — Shopify app

## Stablecoin Payment Solutions

- [Circle (USDC)](https://www.circle.com/en/usdc) — USDC issuer with merchant APIs
- [Stripe Crypto Payouts](https://stripe.com/use-cases/crypto) — Stablecoin payouts via Bridge
- [Bitso](https://bitso.com/business) — LATAM-focused stablecoin payments
- [Conduit](https://www.conduit.financial) — Cross-border stablecoin payments

> 📖 **Integration guide:** [Fiat to Crypto Payment Gateway](https://cryptopayhub.net/fiat-to-crypto-payment-gateway) — bridging traditional and crypto payments.

## Fiat On/Off Ramps

| Service | Coverage | Integration |
|---------|----------|-------------|
| [MoonPay](https://moonpay.com) | 160+ countries | Widget, API |
| [Transak](https://transak.com) | 100+ countries | Widget, API |
| [Wyre](https://www.sendwyre.com) | US, EU | API |
| [Ramp](https://ramp.network) | 150+ countries | Widget, SDK |
| [Sardine](https://sardine.ai) | US, EU | API |

## Resources & Guides

### Merchant Guides
- [How to Accept Crypto Payments on Your Website](https://cryptopayhub.net/how-to-accept-crypto-payments-on-website) — Step-by-step integration guide
- [How to Accept Crypto Payments as a Business](https://cryptopayhub.net/how-to-accept-crypto-payments-as-a-business) — Compliance, accounting, and operations
- [Benefits of Accepting Crypto Payments (B2B)](https://cryptopayhub.net/benefits-accepting-crypto-payments-b2b) — ROI analysis for B2B companies
- [Cost to Develop a Crypto Payment Gateway](https://cryptopayhub.net/cost-to-develop-crypto-payment-gateway) — Build vs buy analysis

### Specialized Guides
- [White Label Crypto Payment Gateway](https://cryptopayhub.net/white-label-crypto-payment-gateway) — Launch your own branded gateway
- [Crypto Payment Gateway Without KYC](https://cryptopayhub.net/crypto-payment-gateway-without-kyc) — Privacy-preserving options

### Industry News
- [Stablecoin Payments News](https://cryptopayhub.net/stablecoin-payments-news) — Latest developments in crypto payments

### External Resources
- [Bitcoin.org - Merchant Tools](https://bitcoin.org/en/spend-bitcoin) — Official Bitcoin merchant resources
- [Ethereum.org - Payments](https://ethereum.org/en/defi/) — Ethereum DeFi payment infrastructure
- [Lightning Network](https://lightning.network/) — Layer 2 scaling for instant BTC payments

## Community

- [r/CryptoCurrency](https://www.reddit.com/r/CryptoCurrency/) — General crypto discussion
- [r/BitcoinMerchants](https://www.reddit.com/r/BitcoinMerchants/) — Merchant-focused community
- [BTCPay Server Chat](https://chat.btcpayserver.org/) — Self-hosted gateway community

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

If you know of a crypto payment gateway, SDK, or resource that should be listed here, please open an issue or submit a pull request.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0. You can copy, modify, and distribute without asking permission.

---

*Curated by [CryptoPayHub](https://cryptopayhub.net) — Independent crypto payment gateway reviews and guides.*
