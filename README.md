# Conditional Tokens Framework (Solidity 0.8.x)

This repository contains the main smart contract for creating a prediction market, using the **Conditional Tokens Framework** on Solidity version 0.8.x. It allows users to create, trade, and resolve prediction markets by defining conditional outcomes and associating them with tokenized assets.

## Overview

The Conditional Tokens Framework enables the creation of tokenized outcomes that are contingent upon the result of a future event. These tokens can be freely traded on secondary markets, allowing users to speculate on future events and hedge against potential outcomes.

### Key Features:
- **Prediction Market Creation**: Easily create new prediction markets around future events (e.g., elections, sports outcomes, etc.).
- **Conditional Outcome Tokens**: Users can trade tokens representing different possible outcomes of an event.
- **Outcome Resolution**: When the event occurs, the contract resolves the prediction market and distributes tokens based on the correct outcome.
- **Supports Conditional Splits**: Token outcomes can be divided into further conditional outcomes for more complex predictions.
- **Optimized for Solidity 0.8.x**: Leverages Solidity 0.8.x for improved gas efficiency, safety, and compiler features.


## Installation

```shell
npx hardhat compile
npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
```