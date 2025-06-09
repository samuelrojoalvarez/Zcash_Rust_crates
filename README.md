# Zcash Rust Crates

A collection of Rust crates for cryptographic primitives, proof systems, and client integration, supporting the Zcash protocol.

## Overview

This repository gathers together several interdependent Rust crates that power Zcash’s Sapling shielded transaction protocol and other cryptographic features.

## Crates in this Repository

- **bellman**: A zk-SNARKs circuit construction library.
- **ff**: Finite field arithmetic library for cryptographic operations.
- **group**: Group theory abstractions used in cryptographic protocols.
- **librustzcash**: Rust library for Zcash protocol logic and integration.
- **pairing**: Implementation of pairing-friendly elliptic curves.
- **sapling-crypto**: Cryptographic primitives for Zcash Sapling shielded addresses and transactions.
- **zcash_client_backend**: Logic for building and scanning Zcash shielded transactions.
- **zcash_primitives**: Core Zcash cryptographic primitives.
- **zcash_proofs**: zk-SNARK proving system implementation.

## Getting Started

### Prerequisites

- **Rust** (latest stable recommended)  
- Optional: Zcash node or testnet for full integration testing

### Building

·Clone this repository:

```bash
git clone https://github.com/samuelrojoalvarez/Zcash_Rust_crates.git
cd Zcash_Rust_crates
```
·Build all crates:
```bash
cargo build --release
```
·Testing
```bash
cargo test
```
Each crate can be used as a library in your own Rust projects. For example, to use the Zcash primitives in your Cargo.toml:
```bash
[dependencies]
zcash_primitives = { path = "zcash_primitives" }
```



