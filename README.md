# Simple Blockchain in Rust

This project is a simple implementation of a blockchain in Rust. It creates a series of blocks linked together using cryptographic hashing to form a chain, following the core structure of a blockchain.

## Project Overview

The blockchain is implemented with the following features:
- Each block stores an index, timestamp, data, the hash of the previous block, and its own hash.
- SHA-256 hashing is used to create the block hash.
- The blockchain maintains the integrity of the data by validating each block in the chain.

## Dependencies

This project uses the `sha2` crate for SHA-256 hashing. To add it to your project, include the following in your `Cargo.toml`:

```
[dependencies]
sha2 = "0.10"
```