# Certora Formal Verification Resources

A curated list of resources for Formal Verification with Certora Prover. Please DM me if you'd like to update it.

[General ↓](#general) · [EVM ↓](#evm) · [Stellar ↓](#stellar) · [Solana ↓](#solana)

<img src="https://www.certora.com/gradientlogo.png" height="50" alt="Certora">

### General

### Articles

- <img src="assets/certora.png" height="20"> [Certora Technology White Paper](https://www.certora.com/blog/white-paper)
  How the Prover works, its capabilities and limitations
  <sub>Chandrakana Nandi, Mooly Sagiv & Daniel Jackson, Feb 2025</sub>

### Videos

- ![yt][yt] [Why Formal Verification Matters: Fireside Chat with Certora CEO Mooly Sagiv](https://www.youtube.com/watch?v=2tARWL61wCo)
  FV role in smart contract security, Certora vision
  <sub>RareTalks, May 2025</sub>

### Tools

- ![gh][gh] [GitHub Action for running Certora Prover](https://github.com/Certora/certora-run-action)
  CI/CD integration for automated Prover runs
  <sub>Certora, constantly updated</sub>

---

<img src="https://raw.githubusercontent.com/ethereum/ethereum-org-website/dev/public/images/assets/eth-diamond-purple.png" height="50" alt="Ethereum">

### EVM

> In progress — more resources coming soon

### Documentation

- <img src="assets/certora.png" height="20"> [Official documentation for Certora Prover](https://docs.certora.com/en/latest/docs/user-guide/install.html)
  Setup, configuration, CVL language reference and examples

- <img src="assets/rareskills.svg" height="20"> [Book of Formal Verification with Certora Prover](https://rareskills.io/tutorials/certora-book)
  Comprehensive CVL guide from basics to advanced patterns

### Articles

- [Learning CVL Language](https://rasengansec.hashnode.dev/learning-certora-prover-part-1) ([Part 2](https://rasengansec.hashnode.dev/learning-certora-prover-part-2), [Part 3](https://rasengansec.hashnode.dev/learning-cvl-language-part-3), [Part 4](https://rasengansec.hashnode.dev/learning-cvl-language-part-4))
  Hands-on walkthrough: CVL syntax, rules, invariants, hooks
  <sub>Certora: Lilian Cariou, Mar-Apr 2025</sub>

---

<img src="https://github.com/stellar/.github/raw/master/stellar-logo.png" height="50" alt="Stellar">

### Stellar
`updated: March 2026`

### Documentation

- <img src="assets/certora.png" height="20"> [Official documentation for Certora Sunbeam (Soroban) Prover](https://docs.certora.com/en/latest/docs/sunbeam/index.html)
  Setup, CVLR language, Soroban verification guide

- <img src="assets/certora.png" height="20"> [Tutorials for Certora Sunbeam](https://certora-sunbeam-tutorials.readthedocs-hosted.com/en/latest/)
  Hands-on examples for Soroban contract verification

### Articles

- <img src="assets/certora.png" height="20"> [Formally Verifying WebAssembly — A Soroban Case Study](https://www.certora.com/blog/formally-verifying-webassembly)
  Applying FV to Wasm bytecode through Soroban
  <sub>Chandrakana Nandi, Oct 2025</sub>

- <img src="assets/certora.png" height="20"> [Inside Certora's First Soroban Contests — Bringing Formal Verification to Rust](https://www.certora.com/blog/bringing-formal-verification-to-rust)
  Lessons and insights from first Soroban FV competitions
  <sub>Shane Runquist & Chandrakana Nandi, Sept 2025</sub>

- <img src="assets/certora.png" height="20"> [Writing Verification-friendly Smart Contracts in Rust](https://www.certora.com/blog/writing-verification-friendly-smart-contracts-in-rust)
  Rust patterns that simplify formal verification
  <sub>Chandrakana Nandi, Aug 2025</sub>

- <img src="assets/positive.png" height="20"> [Formal Methods for Stellar DeFi: Verifying Lending Protocol with Certora Sunbeam Prover](https://blog.positive.com/formal-methods-for-stellar-defi-verifying-lending-protocol-with-certora-sunbeam-prover-e860a192afac)
  Practical Sunbeam methodology on a lending protocol
  <sub>Kirill Ziborov, Aug 2025</sub>

### Videos

- ![yt][yt] [Formally Verifying Soroban Smart Contracts with Certora Sunbeam](https://www.youtube.com/watch?v=Mcv8WCfyJKk)
  Specs, CVLR, SMT solvers, Blend and Reflector examples
  <sub>Chandrakana Nandi, May 2025</sub>

- ![yt][yt] [Verifying Smart Contract Properties with Certora's Sunbeam Tool | Meridian 2024](https://www.youtube.com/watch?v=uoq5SmVKUE8)
  Demo on deployed Soroban contracts with property checks
  <sub>Stellar Development Foundation, Nov 2024</sub>

- ![yt][yt] [Sunbeam: Usable Formal Verification for Smart Contracts on Stellar](https://www.youtube.com/watch?v=kn-mGCv0EFk)
  Architecture, usability, and integration overview
  <sub>Mooly Sagiv, Nov 2024</sub>

- ![yt][yt] [Smart Contract Security Using Certora Prover](https://www.youtube.com/watch?v=62tCJGBcvOY)
  Certora Prover introduction and Soroban demo
  <sub>Cyfrin Audits: Chandrakana Nandi, Nov 2023</sub>

### Specifications

- ![gh][gh] [OpenZeppelin Contracts for Stellar Soroban](https://github.com/Certora/stellar-contracts/tree/certora/packages/access/src/ownable/specs)
  Formal specs for Ownable access control module
  <sub>Certora, constantly updated</sub>

- ![gh][gh] [Aquarius](https://github.com/alexzoid-eth/aquarius-cantina-fv/tree/main/fees_collector/src/certora_specs)
  Verification specs for fees_collector module
  <sub>Certora competition: alexzoid, #2 place, Jun 2025</sub>

- ![gh][gh] [Aquarius — top winners](https://github.com/Certora/aquarius-cantina-fv/tree/main/Example_Submissions)
  Winning submissions from Aquarius FV competition
  <sub>Certora competition, Jun 2025</sub>

- ![gh][gh] [Blend v2](https://github.com/Certora/blend-contracts-v2/tree/certora/pool/src/spec)
  Official pool verification specs
  <sub>Certora, Mar 2025</sub>

- ![gh][gh] [Blend v2](https://github.com/alexzoid-eth/2025-02-blend-fv/tree/main/blend-contracts-v2/backstop)
  Backstop module verification specs
  <sub>Certora competition: alexzoid, #1 place, Feb 2025</sub>

- ![gh][gh] [Blend v1](https://github.com/Certora/blend-contracts/tree/certora/pool/src/spec)
  Pool verification specs
  <sub>Certora, Jan 2025</sub>

- ![gh][gh] [Meridian Certora Workshop](https://github.com/Certora/meridian2024-workshop)
  Simple introductory Sunbeam example
  <sub>Certora, Nov 2024</sub>

### Reports

- ![gh][gh] [Aquarius FV Competition Report](https://github.com/Certora/aquarius-cantina-fv/blob/main/Report.md)
  Competition results and findings summary
  <sub>Cantina, Jun 2025</sub>

- ![gh][gh] [Blend v2 FV Competition Report](https://github.com/code-423n4/2025-02-blend-fv/blob/main/Report.md)
  Competition results and findings summary
  <sub>Code4rena, Feb-Mar 2025</sub>

- ![pdf][pdf] [Blend v2](https://github.com/alexzoid-eth/2025-02-blend-fv/blob/main/blend-contracts-v2/backstop/2025_02_blend_v2_backstop_fv_report_alexzoid.pdf)
  Backstop module FV report
  <sub>Certora competition: alexzoid, Feb 2025</sub>

- ![pdf][pdf] [Blend v1](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/01_30_2025_Blend_V1-FV.pdf)
  Pool module FV report
  <sub>Certora, Feb 2025</sub>

### Libraries

- ![gh][gh] [CVLR for Soroban smart contracts](https://github.com/Certora/cvlr-soroban)
  Rust library for writing verification specs on Soroban
  <sub>Certora, constantly updated</sub>

---

<img src="https://solana.com/src/img/branding/solanaLogoMark.svg" height="50" alt="Solana">

### Solana
`updated: March 2026`

### Documentation

- <img src="assets/certora.png" height="20"> [Official documentation for Certora Solana Prover](https://docs.certora.com/en/latest/docs/solana/index.html)
  Setup, CVLR language, Solana program verification

### Articles

- <img src="assets/certora.png" height="20"> [Securing Kamino Lending — How Formal Verification Prevented Future Risks](https://www.certora.com/blog/securing-kamino-lending)
  How FV found risks in Kamino's lending protocol
  <sub>Pamina Georgiou, Mar 2025</sub>

- <img src="assets/certora.png" height="20"> [Reviewing Token Extensions on Solana Using Formal Verification](https://www.certora.com/blog/token-extensions-audit)
  FV of Solana SPL token extensions
  <sub>Jorge Navas, Aug 2024</sub>

- <img src="assets/certora.png" height="20"> [Solana Verification Part 3: Formal Verification of the Confidentiality Extension of SPL](https://www.certora.com/blog/spl-extension)
  FV of SPL Confidential Transfer extension
  <sub>Jorge Navas, Aug 2023</sub>

- <img src="assets/certora.png" height="20"> [Solana Verification Part 2: Formal Verification of SPL Token 2022](https://www.certora.com/blog/sol-token)
  FV of SPL Token 2022 standard
  <sub>Jorge Navas, Aug 2023</sub>

- <img src="assets/certora.png" height="20"> [Solana Verification Part 1: Formal Verification of Solana Smart Contracts](https://www.certora.com/blog/sol-formal-verification)
  Introduction to FV for Solana programs
  <sub>Jorge Navas, Aug 2023</sub>

### Videos

- ![yt][yt] [How Certora Secures Billions on Solana, Myths & AI Risks in 2026!](https://www.youtube.com/watch?v=mFmKHbgUzHo)
  Certora's Solana security approach, myths and AI risks
  <sub>SolanaFloor: Mooly Sagiv, Dec 2025</sub>

- ![yt][yt] [Security Block: Certora](https://www.youtube.com/watch?v=j8BMKFQQPWY)
  FV overview at Solana Breakpoint 2025
  <sub>Pamina Georgiev, Dec 2025</sub>

- ![yt][yt] [Securing Solana programs with formal verification](https://www.youtube.com/watch?v=tNmRscHydzE)
  Live demo of Solana program verification
  <sub>Superteam Canada, May 2025</sub>

- ![yt][yt] [Securing Solana Protocols With Formal Verification](https://www.youtube.com/watch?v=qn3z4zRInLo)
  Academic perspective on FV for Solana
  <sub>Crossroads '25: Arie Gurfinkel, May 2025</sub>

### Specifications

- ![gh][gh] [Examples from Prover's Public/TestSolana directory](https://github.com/Certora/CertoraProver/tree/master/Public/TestSolana)
  Reference specs from Prover's test suite
  <sub>Certora</sub>

- ![gh][gh] [Solana applications verification examples](https://github.com/Certora/SolanaExamples/tree/main/cvlr_by_example)
  CVLR by example: practical verification patterns
  <sub>Certora, ~Jun 2025</sub>

- ![gh][gh] [Certora Tokenized Vault for Solana Tutorial](https://github.com/Certora/certora-vault-tutorial/tree/main/programs/vault/src/certora)
  Step-by-step tokenized vault verification
  <sub>Certora, ~May 2025</sub>

### Reports

- ![pdf][pdf] [Deriverse DEX](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_11_deriverse_fv_report_cyfrin_alexzoid.pdf)
  DEX protocol FV findings
  <sub>Cyfrin contractor: alexzoid, Nov 2025</sub>

- ![pdf][pdf] [Kamino LIMO](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_28_2025_Kamino_LIMO.pdf)
  Limit order protocol FV findings
  <sub>Certora, Jul 2025</sub>

- ![pdf][pdf] [Kamino Vault](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_07_2025_Kamino_Vault.pdf)
  Yield management protocol FV findings
  <sub>Certora, Jul 2025</sub>

- ![pdf][pdf] [Squads multi-signature wallet](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/02_15_2025_Squads-FV-MR.pdf)
  Multisig wallet FV findings
  <sub>Certora, Feb 2025</sub>

### Libraries

- ![gh][gh] [CVLR library for Solana](https://github.com/Certora/cvlr-solana)
  Rust library for writing verification specs on Solana
  <sub>Certora, constantly updated</sub>

### Tools

- ![gh][gh] [Solana spec template](https://github.com/Certora/solana-spec-template)
  Boilerplate for new Solana FV projects
  <sub>Certora, constantly updated</sub>

- ![gh][gh] [cargo-certora-sbf](https://github.com/Certora/cargo-certora-sbf)
  Compiles Solana programs for Certora Prover
  <sub>Certora, constantly updated</sub>

- ![gh][gh] [Certora Solana Platform Tools](https://github.com/Certora/certora-solana-platform-tools)
  Solana build toolchain for verification
  <sub>Certora, constantly updated</sub>

<!-- Badge references -->
[gh]: https://img.shields.io/badge/%20-181717?style=flat-square&logo=github&logoColor=white
[pdf]: https://img.shields.io/badge/PDF-EC1C24?style=flat-square
[yt]: https://img.shields.io/badge/%20-FF0000?style=flat-square&logo=youtube&logoColor=white
