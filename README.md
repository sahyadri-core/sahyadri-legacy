<div align="center">
  <img src="https://www.sahyadri.io/img/IMG_3277.png" alt="Sahyadri Logo" width="200"/>
  <h1>Sahyadri on Rust</h1>
  <p><b>High-Performance PoW DAG | Account-Object Based Model | High TPS | 21 Million Fixed Supply</b></p>
</div>

---

Welcome to the Rust-based implementation of the **Sahyadri Layer 1 Protocol**. Sahyadri is a high-performance, Decentralized Web Node (DWN) integrated, Proof-of-Work (PoW) DAG network.

    ⚠️ NOT FOR MAINNET USE — This is the archived secp256k1-based Sahyadri node, preserved for reference, testing, and forking purposes only.

Important

The Sahyadri mainnet has migrated to Dilithium (post-quantum cryptography). This repository contains the previous secp256k1 implementation and is no longer used in production.

    Current mainnet node (Dilithium): sahyadri-core/sahyadri
    This repo (secp256k1 legacy): For research, testing, and forking only

What is this?

This is the original Rust-based Sahyadri node using secp256k1 elliptic curve for signatures. It was the foundation before the network upgraded to post-quantum Dilithium signatures.

Use this code if you want to:

    Study the original Sahyadri architecture
    Fork and build your own DAG-based network
    Test and experiment in isolation

Quick Start

# Prerequisitessudo apt update && sudo apt install -y git build-essential cmake pkg-config libssl-dev# Clone and buildgit clone https://github.com/sahyadri-core/sahyadri-legacy.gitcd sahyadri-legacycargo build --release

## 🔗 Official Links
 * **Official Code:** https://github.com/sahyadri-core/sahyadri
 * **Website:** https://sahyadri.io
 * **Explorer:** explorer.sahyadri.io (upcoming)
 * **Wallet:** wallet.sahyadri.io (upcoming)
 * **Discord/Telegram:** 
[X: https://x.com/sahyadricore?s=21]
[Discord: https://discord.gg/Dz9NDUwWPe]
</details>
