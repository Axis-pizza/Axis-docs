# Axis Docs

Documentation for [Axis](https://axs.pizza) — a permissionless on-chain ETF platform built on Solana.

## Structure

```
├── getting-started/   # How Axis works, Devnet, Mainnet, FAQ
├── products/          # ETF creation, investing, rebalancing, fees
├── protocol/          # Overview, PFDA mechanism, oracle
├── research/          # Open questions, long-tail assets, papers
├── developers/        # Architecture, smart contracts, repos
└── trust/             # Security, risks, legal
```

## Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```bash
npm i -g mintlify
```

Run at the repo root (where `docs.json` is located):

```bash
mintlify dev
```

Preview at `http://localhost:3000`.

## Deployment

Push to `main` — changes deploy automatically via the Mintlify GitHub app.

## Contact

- X: [@Axis_pizza](https://x.com/Axis_pizza)
- GitHub: [github.com/Axis-pizza](https://github.com/Axis-pizza)
