---
title: Validators
---

# Validators in Heroglyph Protocol

Validators play a vital role in the Ethereum Network by participating in block validation. Heroglyph supports solo and third-party service validators.

## Types of Validators
- **Solo Validator (Full Validator):** Operates own node with 32 ETH staked.
- **Minipods:** Utilizes protocols like Rocket Pool with less than 32 ETH staked.

## Getting Started
To get started as a validator, proper graffiti configuration is required. Validation relies on linking your identifier properly. Refer to the [graffiti testing tool](#) to avoid skipped blocks.

## Resolving Block Skips and Ticker Ignores
### Common Issues:
- Graffiti Formatting: Ensure correct syntax (`#`).
- Ticker Surrendered: Caused by insufficient funds.
- Ticker Reverted: Due to execution errors.

Validators can test configurations using the graffiti testing tool to verify validity and protect against common errors.

---
