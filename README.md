# Certora Formal Verification Resources

A curated list of resources for Formal Verification with Certora Prover (EVM / Stellar / Solana).
Please DM me if you'd like to update it.

## Table of Contents

- [EVM](#-evm)
  - [Documentation](#documentation)
  - [Articles](#articles)
  - [Videos](#videos)
  - [Tools](#tools)
- [Stellar](#-stellar)
  - [Documentation](#documentation-1)
  - [Articles](#articles-1)
  - [Videos](#videos-1)
  - [Specifications](#specifications)
  - [Reports](#reports)
  - [Libraries](#libraries)
- [Solana](#-solana)
  - [Documentation](#documentation-2)
  - [Articles](#articles-2)
  - [Videos](#videos-2)
  - [Specifications](#specifications-1)
  - [Reports](#reports-1)
  - [Libraries](#libraries-1)
  - [Tools](#tools-1)

---

## ⟠ EVM

> In progress — more resources coming soon

### Documentation

- ![certora][certora] [Official documentation for Certora Prover](https://docs.certora.com/en/latest/docs/user-guide/install.html)
- [Book of Formal Verification with Certora Prover](https://rareskills.io/tutorials/certora-book) — RareSkills

### Articles

- [Learning CVL Language](https://rasengansec.hashnode.dev/learning-certora-prover-part-1) ([Part 2](https://rasengansec.hashnode.dev/learning-certora-prover-part-2), [Part 3](https://rasengansec.hashnode.dev/learning-cvl-language-part-3), [Part 4](https://rasengansec.hashnode.dev/learning-cvl-language-part-4)) — Certora: Lilian Cariou, Mar-Apr 2025
- ![certora][certora] [Certora Technology White Paper](https://www.certora.com/blog/white-paper) — Certora: Chandrakana Nandi, Mooly Sagiv & Daniel Jackson, Feb 2025

### Videos

- ![yt][yt] [Why Formal Verification Matters: Fireside Chat with Certora CEO Mooly Sagiv](https://www.youtube.com/watch?v=2tARWL61wCo) — RareTalks, May 2025

### Tools

- ![gh][gh] [GitHub Action for running Certora Prover](https://github.com/Certora/certora-run-action) — Certora, constantly updated

---

## ✦ Stellar
`updated: March 2026`

### Documentation

- ![certora][certora] [Official documentation for Certora Sunbeam (Soroban) Prover](https://docs.certora.com/en/latest/docs/sunbeam/index.html)
- ![certora][certora] [Tutorials for Certora Sunbeam](https://certora-sunbeam-tutorials.readthedocs-hosted.com/en/latest/)

### Articles

- ![certora][certora] [Formally Verifying WebAssembly — A Soroban Case Study](https://www.certora.com/blog/formally-verifying-webassembly) — Certora: Chandrakana Nandi, Oct 2025
- ![certora][certora] [Inside Certora's First Soroban Contests — Bringing Formal Verification to Rust](https://www.certora.com/blog/bringing-formal-verification-to-rust) — Certora: Shane Runquist & Chandrakana Nandi, Sept 2025
- ![certora][certora] [Writing Verification-friendly Smart Contracts in Rust](https://www.certora.com/blog/writing-verification-friendly-smart-contracts-in-rust) — Certora: Chandrakana Nandi, Aug 2025
- [Formal Methods for Stellar DeFi: Verifying Lending Protocol with Certora Sunbeam Prover](https://blog.positive.com/formal-methods-for-stellar-defi-verifying-lending-protocol-with-certora-sunbeam-prover-e860a192afac) — Positive Web3 Security: Kirill Ziborov, Aug 2025

### Videos

- ![yt][yt] [Formally Verifying Soroban Smart Contracts with Certora Sunbeam](https://www.youtube.com/watch?v=Mcv8WCfyJKk) — Certora: Chandrakana Nandi, May 2025
- ![yt][yt] [Verifying Smart Contract Properties with Certora's Sunbeam Tool | Meridian 2024](https://www.youtube.com/watch?v=uoq5SmVKUE8) — Stellar Development Foundation, Nov 2024
- ![yt][yt] [Sunbeam: Usable Formal Verification for Smart Contracts on Stellar](https://www.youtube.com/watch?v=kn-mGCv0EFk) — Stellar Development Foundation: Mooly Sagiv, Nov 2024
- ![yt][yt] [Smart Contract Security Using Certora Prover](https://www.youtube.com/watch?v=62tCJGBcvOY) — Cyfrin Audits: Chandrakana Nandi, Nov 2023

### Specifications

- ![gh][gh] [OpenZeppelin Contracts for Stellar Soroban](https://github.com/Certora/stellar-contracts/tree/certora/packages/access/src/ownable/specs) — Certora, constantly updated
- ![gh][gh] [Aquarius](https://github.com/alexzoid-eth/aquarius-cantina-fv/tree/main/fees_collector/src/certora_specs) — Certora competition: alexzoid, #2 place, Jun 2025
- ![gh][gh] [Aquarius — top winners](https://github.com/Certora/aquarius-cantina-fv/tree/main/Example_Submissions) — Certora competition, Jun 2025
- ![gh][gh] [Blend v2](https://github.com/Certora/blend-contracts-v2/tree/certora/pool/src/spec) — Certora, Mar 2025
- ![gh][gh] [Blend v2](https://github.com/alexzoid-eth/2025-02-blend-fv/tree/main/blend-contracts-v2/backstop) — Certora competition: alexzoid, #1 place, Feb 2025
- ![gh][gh] [Blend v1](https://github.com/Certora/blend-contracts/tree/certora/pool/src/spec) — Certora, Jan 2025
- ![gh][gh] [Meridian Certora Workshop](https://github.com/Certora/meridian2024-workshop) — Sunbeam on a simple example, Nov 2024

### Reports

- ![gh][gh] [Aquarius FV Competition Report](https://github.com/Certora/aquarius-cantina-fv/blob/main/Report.md) — Cantina, Jun 2025
- ![gh][gh] [Blend v2 FV Competition Report](https://github.com/code-423n4/2025-02-blend-fv/blob/main/Report.md) — Code4rena, Feb-Mar 2025
- ![pdf][pdf] [Blend v2](https://github.com/alexzoid-eth/2025-02-blend-fv/blob/main/blend-contracts-v2/backstop/2025_02_blend_v2_backstop_fv_report_alexzoid.pdf) — Certora competition: alexzoid, Feb 2025
- ![pdf][pdf] [Blend v1](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/01_30_2025_Blend_V1-FV.pdf) — Certora, Feb 2025

### Libraries

- ![gh][gh] [CVLR for Soroban smart contracts](https://github.com/Certora/cvlr-soroban) — Certora, constantly updated

---

## ◎ Solana
`updated: March 2026`

### Documentation

- ![certora][certora] [Official documentation for Certora Solana Prover](https://docs.certora.com/en/latest/docs/solana/index.html)

### Articles

- ![certora][certora] [Securing Kamino Lending — How Formal Verification Prevented Future Risks](https://www.certora.com/blog/securing-kamino-lending) — Certora: Pamina Georgiou, Mar 2025
- ![certora][certora] [Reviewing Token Extensions on Solana Using Formal Verification](https://www.certora.com/blog/token-extensions-audit) — Certora: Jorge Navas, Aug 2024
- ![certora][certora] [Solana Verification Part 3: Formal Verification of the Confidentiality Extension of SPL](https://www.certora.com/blog/spl-extension) — Certora: Jorge Navas, Aug 2023
- ![certora][certora] [Solana Verification Part 2: Formal Verification of SPL Token 2022](https://www.certora.com/blog/sol-token) — Certora: Jorge Navas, Aug 2023
- ![certora][certora] [Solana Verification Part 1: Formal Verification of Solana Smart Contracts](https://www.certora.com/blog/sol-formal-verification) — Certora: Jorge Navas, Aug 2023

### Videos

- ![yt][yt] [How Certora Secures Billions on Solana, Myths & AI Risks in 2026!](https://www.youtube.com/watch?v=mFmKHbgUzHo) — SolanaFloor: Mooly Sagiv, Dec 2025
- ![yt][yt] [Security Block: Certora](https://www.youtube.com/watch?v=j8BMKFQQPWY) — Breakpoint 2025: Pamina Georgiev, Dec 2025
- ![yt][yt] [Securing Solana programs with formal verification](https://www.youtube.com/watch?v=tNmRscHydzE) — Superteam Canada, May 2025
- ![yt][yt] [Securing Solana Protocols With Formal Verification](https://www.youtube.com/watch?v=qn3z4zRInLo) — Crossroads '25: Arie Gurfinkel, May 2025

### Specifications

- ![gh][gh] [Examples from Prover's Public/TestSolana directory](https://github.com/Certora/CertoraProver/tree/master/Public/TestSolana) — Certora
- ![gh][gh] [Solana applications verification examples](https://github.com/Certora/SolanaExamples/tree/main/cvlr_by_example) — Certora, ~Jun 2025
- ![gh][gh] [Certora Tokenized Vault for Solana Tutorial](https://github.com/Certora/certora-vault-tutorial/tree/main/programs/vault/src/certora) — Certora, ~May 2025

### Reports

- ![pdf][pdf] [Deriverse DEX](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_11_deriverse_fv_report_cyfrin_alexzoid.pdf) — Cyfrin contractor: alexzoid, Nov 2025
- ![pdf][pdf] [Kamino LIMO](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_28_2025_Kamino_LIMO.pdf) — Certora, Jul 2025
- ![pdf][pdf] [Kamino Vault](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_07_2025_Kamino_Vault.pdf) — Certora, Jul 2025
- ![pdf][pdf] [Squads multi-signature wallet](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/02_15_2025_Squads-FV-MR.pdf) — Certora, Feb 2025

### Libraries

- ![gh][gh] [CVLR library for Solana](https://github.com/Certora/cvlr-solana) — Certora, constantly updated

### Tools

- ![gh][gh] [Solana spec template](https://github.com/Certora/solana-spec-template) — Certora, constantly updated
- ![gh][gh] [cargo-certora-sbf](https://github.com/Certora/cargo-certora-sbf) — Cargo subcommand for building Solana programs for Certora Prover, constantly updated
- ![gh][gh] [Certora Solana Platform Tools](https://github.com/Certora/certora-solana-platform-tools) — Certora, constantly updated

<!-- Badge references -->
[gh]: https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white
[pdf]: https://img.shields.io/badge/-PDF-EC1C24?style=flat-square
[yt]: https://img.shields.io/badge/-YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white
[certora]: https://img.shields.io/badge/-Certora-2CB67D?style=flat-square
