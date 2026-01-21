# Certora Formal Verification Resources

A curated list of resources for Formal Verification with Certora Prover (EVM/Stellar/Solana). Please DM me if you'd like to update it.

## EVM (Ethereum Virtual Machine)

... in progress

## Stellar

### Documentation

[->](https://docs.certora.com/en/latest/docs/sunbeam/index.html) Official documentation for Certora Sunbeam (Soroban) Prover

### Articles

[->](https://www.certora.com/blog/formally-verifying-webassembly) Formally Verifying WebAssembly: A Soroban Case Study (Certora, Oct 2025)

[->](https://www.certora.com/blog/bringing-formal-verification-to-rust) Inside Certora’s First Soroban Contests (Certora, Sept 2025)

### Specifications

OpenZeppelin Contracts written in Rust for Stellar Soroban (Certora, constantly updated, [->](https://github.com/Certora/stellar-contracts/tree/certora/packages/access/src/ownable/specs), [->](https://github.com/Certora/stellar-contracts/tree/certora/packages/access/src/access_control/specs) and more)

[->](https://github.com/alexzoid-eth/aquarius-cantina-fv/tree/main/fees_collector/src/certora_specs) Aquarius liquidity layer (alexzoid 🥈#2 place Certora competition, Jun 2025)

[->](https://github.com/Certora/aquarius-cantina-fv/tree/main/Example_Submissions) Aquarius liquidity layer (top competition winners, Jun 2025)

[->](https://github.com/Certora/blend-contracts-v2/tree/certora/pool/src/spec) Blend v2 liquidity protocol primitive (Certora, March 2025)

[->](https://github.com/alexzoid-eth/2025-02-blend-fv/tree/main/blend-contracts-v2/backstop) Blend v2 liquidity protocol primitive (alexzoid 🏆#1 place Certora competition, Feb 2025)

[->](https://github.com/Certora/blend-contracts/tree/certora/pool/src/spec) Blend v1 liquidity protocol primitive (Certora, Jan 2025)

[->](https://github.com/Certora/meridian2024-workshop) Meridian Certora workshop, show you how to use Sunbeam on a simple example (Certora, Nov 2024)

### Reports

[->](https://github.com/alexzoid-eth/2025-02-blend-fv/blob/main/blend-contracts-v2/backstop/2025_02_blend_v2_backstop_fv_report_alexzoid.pdf) Blend v2 liquidity protocol primitive (alexzoid, Feb 2025)

[->](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/01_30_2025_Blend_V1-FV.pdf) Blend v1 liquidity protocol primitive (Certora, Feb 2025)

## Solana

### Documentation

[->](https://docs.certora.com/en/latest/docs/solana/index.html) Official documentation for Certora Solana Prover

### Articles

[->](https://www.certora.com/blog/writing-verification-friendly-smart-contracts-in-rust) Writing Verification-friendly Smart Contracts in Rust (Certora, Aug 2025)

[->](https://www.certora.com/blog/securing-kamino-lending) Securing Kamino Lending (Certora, Mar 2025)

[->](https://www.certora.com/blog/sol-formal-verification) Solana Verification: Formal Verification of Solana Smart Contracts (Certora, Aug 2023) / [->](https://www.certora.com/blog/sol-token) / [->](https://www.certora.com/blog/spl-extension)

### Specifications

[->](https://github.com/Certora/CertoraProver/tree/master/Public/TestSolana) Examples of specifications from lastest Prover's Public/TestSolana directory

[->](https://github.com/Certora/SolanaExamples/tree/main/cvlr_by_example) Examples of Solana applications verification with the Certora Prover (Certora, ~June 2025)

[->](https://github.com/Certora/certora-vault-tutorial/tree/main/programs/vault/src/certora) Certora Tokenized Vault for Solana Tutorial (Certora, ~May 2025)

### Reports

[->](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_11_deriverse_fv_report_cyfrin_alexzoid.pdf) Deriverse DEX (alexzoid/cyfrin, Nov 2025)

[->](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_28_2025_Kamino_LIMO.pdf) Kamino’s LIMO (Liquidity Integration and Matching Order) Solana program implements a limit order protocol (Certora, Jul 2025)

[->](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_07_2025_Kamino_Vault.pdf) Kamino Vault protocol for optimized borrowing, lending, and automated yield management (Certora, Jul 2025)

[->](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/02_15_2025_Squads-FV-MR.pdf) Squads multi-signature wallet platform (Certora, Feb 2025)

### Tools 

[->](https://github.com/Certora/solana-spec-template) Template for Certora specifications for Solana projects (Certora, constantly updated)