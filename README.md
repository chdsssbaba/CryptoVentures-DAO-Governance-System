# CryptoVentures DAO Governance System

**Author:** chdsssbaba
**GitHub:** [https://github.com/chdsssbaba/CryptoVentures-DAO-Governance-System](https://github.com/chdsssbaba/CryptoVentures-DAO-Governance-System)

A production-ready **DAO governance system** for managing a decentralized investment treasury using **ETH staking, quadratic voting, delegation, and timelock-secured execution**.

---

## Overview

CryptoVentures DAO enables members to stake ETH to gain voting power and collectively decide how treasury funds are allocated through on-chain proposals.

**Core principles:**

* Stake-based governance
* Quadratic voting
* Transparent proposal lifecycle
* Tiered treasury risk management
* Timelock-enforced execution

---

## Key Features

### Governance

* ETH staking → quadratic voting power
* Proposal creation with minimum stake requirement
* Token-weighted voting with delegation
* Immutable voting and execution flow

### Treasury

* **High-Conviction Fund** (large, high-security proposals)
* **Experimental Fund** (medium-risk investments)
* **Operational Fund** (low-risk operations)
* Automatic fund tier detection and allocation

### Security

* Timelock delays before execution
* Guardian emergency cancellation
* Re-entrancy protection
* Role-based access control

---

## Architecture

**Core Contracts**

* `GovernanceToken` – staking & voting power
* `GovernanceProposal` – proposals, voting, delegation
* `TimelockController` – delayed execution
* `MultiTierTreasury` – fund allocation & transfers

---

## Getting Started

### Install

```bash
git clone https://github.com/chdsssbaba/CryptoVentures-DAO-Governance-System.git
cd CryptoVentures-DAO-Governance-System
npm install
cp .env.example .env
```

### Run Locally

```bash
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
```

### Test

```bash
npx hardhat test
```

✅ **43 passing tests**
✅ High coverage on governance logic

---

## Tech Stack

* Solidity `0.8.20`
* Hardhat
* OpenZeppelin
* JavaScript / Node.js

---

## Status

✔ Governance complete
✔ Treasury logic implemented
✔ Timelock security enforced
✔ Ready for audit, demo, or submission

---

