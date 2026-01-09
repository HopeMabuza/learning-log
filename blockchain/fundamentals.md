# Blockchain Fundamentals

## What is Blockchain?
Blockchain is a decentralised way of transacting that does not rely on a central authority such as a bank. Instead of trusting one organisation, transactions are validated by a network of participants, which makes the system trustless and transparent.

## Blocks and Hashes
A blockchain is made up of blocks that are linked together to form a chain. Each block contains:
- A list of transactions
- The hash of the previous block
- Its own unique hash

Hashes are created using cryptographic hash functions and act like digital fingerprints. No two blocks can have the same hash, and even a very small change in the data will produce a completely different hash. This is what makes the blockchain very difficult to tamper with.

## Consensus Mechanisms
Before a transaction is added to a block, the network must agree that it is valid. This agreement process is called a consensus mechanism and ensures that all nodes share the same version of the ledger.

- **Proof of Work (PoW):** Nodes called miners compete to solve complex computational problems. The first miner to solve the problem adds the block and is rewarded with the network’s native cryptocurrency.
- **Proof of Stake (PoS):** Validators are chosen based on the amount of cryptocurrency they have staked in the network. This method reduces the amount of computational power required compared to PoW.

## Smart Contracts
Smart contracts are pieces of code stored on the blockchain that define rules and conditions for transactions. Once deployed, smart contracts cannot be changed and automatically execute when their conditions are met. This removes the need for intermediaries and allows transactions to be processed automatically.

## Distributed Ledger
Blockchain uses a distributed ledger, meaning that every node in the network keeps a copy of all transactions. This improves transparency and security, since no single entity controls the data.

## Key Takeaways
- Blockchain is decentralised and does not rely on a central authority
- Cryptographic hashes protect data integrity
- Consensus mechanisms allow nodes to agree on valid transactions
- Smart contracts automate trust without intermediaries

## Sources
- Cardano Academy – *Blockchain Fundamentals*
- IBM – *Introduction to Blockchain* (edX)
- Nakamoto, S. (2008). *Bitcoin: A Peer-to-Peer Electronic Cash System*
- IBM Blockchain Documentation
- Ethereum Documentation (Smart Contracts & Consensus)
