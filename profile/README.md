# CantorFi

**Isolated lending and settlement infrastructure on Base.**

CantorFi is an EVM protocol for isolated lending vaults, CVT staking, prediction market settlement and B20 token infrastructure. The current public deployment is a developer preview on Base Sepolia (chain ID 84532).

- Website: https://www.cantorfi.xyz
- Application: https://app.cantorfi.xyz/yield
- Developer documentation: https://www.cantorfi.xyz/docs
- Open-source liquidation bot: https://www.cantorfi.xyz/bots

## What CantorFi does

- **Isolated vaults**: supply an ERC-20 and borrow that same underlying token. One asset per vault, so a problem in one vault stays in that vault.
- **Variable rates**: borrow and supply APR are derived from pool utilization.
- **CVT staking**: lock the vault receipt token and receive distributed rewards.
- **Settlement services for integrators**: wager, bond, trade and prediction market settlement, after governance onboarding.
- **Launch and swap**: bonding-curve launches followed by V2-compatible DEX trading.
- **B20 service**: public token and account inspection, and unsigned Asset or Stablecoin campaign preparation.

## Guides

- [Isolated lending vaults](https://www.cantorfi.xyz/isolated-lending-vaults)
- [CVT staking](https://www.cantorfi.xyz/cvt-staking)
- [Prediction market settlement](https://www.cantorfi.xyz/prediction-market-settlement)
- [How prediction markets are resolved: oracles explained](https://www.cantorfi.xyz/how-prediction-markets-are-resolved)
- [B20 token standard on Base, explained](https://www.cantorfi.xyz/b20-token-standard)
- [How to launch a token on Base: three ways compared](https://www.cantorfi.xyz/launch-a-token-on-base)
- [Lending protocols on Base compared by design](https://www.cantorfi.xyz/lending-protocols-on-base)
- [DeFi liquidations explained](https://www.cantorfi.xyz/defi-liquidations)
- [ERC-4626 vault standard, and why CVT is not one](https://www.cantorfi.xyz/erc-4626-vault)

## For AI assistants and agents

- Short description: https://www.cantorfi.xyz/llms.txt
- Full protocol description: https://www.cantorfi.xyz/llms-full.txt
- Public B20 inspection endpoint: https://www.cantorfi.xyz/api/b20/inspect

## Status

Developer preview on Base Sepolia, with temporary governance: this is not a mainnet configuration. Rates are variable annualized estimates, not guaranteed yield. CVT is not ERC-4626 and has restricted transfers. Cross-asset collateral is disabled.
