# Certora Formal Verification Resources

A curated list of resources for Formal Verification with Certora Prover (EVM/Stellar/Solana). Please DM me if you'd like to update it.

## EVM (Ethereum Virtual Machine)

... in progress

## Stellar

### Documentation

- Official [documentation](https://docs.certora.com/en/latest/docs/sunbeam/index.html) for Certora Sunbeam (Soroban) Prover

### Articles

- Inside Certora’s First Soroban Contests (Certora, Sept 2025, [blog/bringing-formal-verification-to-rust](https://www.certora.com/blog/bringing-formal-verification-to-rust))


### Specifications

- OpenZeppelin Contracts written in Rust for Stellar Soroban (Certora, constantly updated, [Certora/stellar-contracts/ownable](https://github.com/Certora/stellar-contracts/tree/certora/packages/access/src/ownable/specs), [Certora/stellar-contracts/access_control](https://github.com/Certora/stellar-contracts/tree/certora/packages/access/src/access_control/specs) and more)

- Aquarius liquidity layer (alexzoid 🥈#2 place Certora competition, Jun 2025, [aquarius-cantina-fv/fees_collector](https://github.com/alexzoid-eth/aquarius-cantina-fv/tree/main/fees_collector/src/certora_specs))

- Aquarius liquidity layer (top competition winners, Jun 2025, [aquarius-cantina-fv/Example_Submissions](https://github.com/Certora/aquarius-cantina-fv/tree/main/Example_Submissions))

- Blend v2 liquidity protocol primitive (Certora, March 2025, [blend-contracts-v2/pool](https://github.com/Certora/blend-contracts-v2/tree/certora/pool/src/spec))

- Blend v2 liquidity protocol primitive (alexzoid 🏆#1 place Certora competition, Feb 2025, [blend-contracts-v2/backstop](https://github.com/alexzoid-eth/2025-02-blend-fv/tree/main/blend-contracts-v2/backstop))

- Blend v1 liquidity protocol primitive (Certora, Jan 2025, [blend-contracts/pool](https://github.com/Certora/blend-contracts/tree/certora/pool/src/spec))

- Meridian Certora workshop, show you how to use Sunbeam on a simple example (Certora, Nov 2024, [Certora/meridian2024-workshop](https://github.com/Certora/meridian2024-workshop))

### Reports

- Blend v2 liquidity protocol primitive (alexzoid, Feb 2025, [2025_02_blend_v2_backstop_fv_report_alexzoid.pdf](https://github.com/alexzoid-eth/2025-02-blend-fv/blob/main/blend-contracts-v2/backstop/2025_02_blend_v2_backstop_fv_report_alexzoid.pdf))

- Blend v1 liquidity protocol primitive (Certora, Feb 2025, [01_30_2025_Blend_V1-FV.pdf](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/01_30_2025_Blend_V1-FV.pdf))


## Solana

### Documentation

- Official [documentation](https://docs.certora.com/en/latest/docs/solana/index.html) for Certora Solana Prover

### Articles

- Writing Verification-friendly Smart Contracts in Rust (Certora, Aug 2025, [blog/writing-verification-friendly-smart-contracts-in-rust](https://www.certora.com/blog/writing-verification-friendly-smart-contracts-in-rust))

- Securing Kamino Lending (Certora, Mar 2025, [blog/securing-kamino-lending](https://www.certora.com/blog/securing-kamino-lending))

- Solana Verification: Formal Verification of Solana Smart Contracts (Certora, Aug 2023, [Part 1](https://www.certora.com/blog/sol-formal-verification) / [Part 2](https://www.certora.com/blog/sol-token) / [Part 3](https://www.certora.com/blog/spl-extension))

### Specifications

- Examples of specifications from lastest Prover's [Public/TestSolana](https://github.com/Certora/CertoraProver/tree/master/Public/TestSolana) directory

- Examples of Solana applications verification with the Certora Prover (Certora, ~June 2025, [Certora/SolanaExamples](https://github.com/Certora/SolanaExamples/tree/main/cvlr_by_example))

- Certora Tokenized Vault for Solana Tutorial (Certora, ~May 2025, [Certora/certora-vault-tutorial](https://github.com/Certora/certora-vault-tutorial/tree/main/programs/vault/src/certora))

### Reports

- Deriverse DEX (alexzoid/cyfrin, Nov 2025, [2025_11_deriverse_fv_report_cyfrin_alexzoid.pdf](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_11_deriverse_fv_report_cyfrin_alexzoid.pdf))

- Kamino’s LIMO (Liquidity Integration and Matching Order) Solana program implements a limit order protocol (Certora, Jul 2025, [07_28_2025_Kamino_LIMO.pdf](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_28_2025_Kamino_LIMO.pdf))

- Kamino Vault protocol for optimized borrowing, lending, and automated yield management (Certora, Jul 2025, [07_07_2025_Kamino_Vault.pdf](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_07_2025_Kamino_Vault.pdf))

- Squads multi-signature wallet platform (Certora, Feb 2025, [02_15_2025_Squads-FV-MR.pdf](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/02_15_2025_Squads-FV-MR.pdf))

### Tools 

- Template for Certora specifications for Solana projects (Certora, constantly updated, [Certora/solana-spec-template](https://github.com/Certora/solana-spec-template))