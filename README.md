Project Description
The Stellar-Asset-Minter is an all-in-one tool for token creators. It simplifies the process of minting assets on both the Stellar Classic network and the Soroban smart contract layer, providing a unified interface for supply management, metadata updates, and distribution.

Technical Architecture
Dashboard: A React-based UI that allows non-technical users to issue tokens with custom flags (clawback, authorization, etc.).

Issuance SDK: A headless library for developers to programmatically manage assets within their own applications.

Compatibility: Fully supports both Classic (Trustlines) and Soroban (SEP-41) asset standards.

🌊 Drips Wave Program
This repository is an active participant in the Drips Wave Program.

How to contribute:

Register: Link your GitHub to Drips.

Claim an Issue:

Trivial (100 pts): Styling improvements for the minting dashboard.

Medium (150 pts): Adding support for SEP-10 metadata uploads.

High (200 pts): Implementing batch-distribution (airdrop) functionality for new assets.

Submit & Earn: Contribute code and earn XLM/Drips rewards.

Project Structure
Plaintext
├── src/
│   ├── ui/          # Next.js frontend components
│   └── sdk/         # Asset management helper functions
├── contracts/       # Soroban asset wrapper contracts
└── tests/           # Unit tests for issuance logic
