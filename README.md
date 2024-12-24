# SPL Token Staking Program

This is a Solana SPL Token staking program that supports dual token staking, where rewards are accumulated per second, and each token can have a defined weight for accumulation. The program is governance-controlled, allowing all parameters to be upgraded by governance accounts.

## Requirements

- Anchor 0.29.0
- Solana 1.18.1
- Rust 1.75.0

## Setup

Install Anchor using instructions found [here](https://book.anchor-lang.com/getting_started/installation.html#anchor).

Set up a valid Solana keypair at the path specified in the `wallet` in `Anchor.toml` and replace the pubkey of DEPLOYER with that account key in `state.rs`.

To do local testing with `anchor test` flows.
