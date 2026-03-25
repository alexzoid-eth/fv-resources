# Certora Formal Verification Resources

A curated list of resources for Formal Verification with Certora Prover. Please DM me if you'd like to update it.

[General ↓](#general) · [EVM ↓](#evm) · [Stellar ↓](#stellar) · [Solana ↓](#solana)

<img src="https://www.certora.com/gradientlogo.png" height="50" alt="Certora">

### General

### Articles

- ![certora][certora] [Certora Technology White Paper](https://www.certora.com/blog/white-paper)
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

- ![certora][certora] [Official documentation for Certora Prover](https://docs.certora.com/en/latest/docs/user-guide/install.html)
  Setup, configuration, CVL language reference and examples

- ![rareskills][rareskills] [Book of Formal Verification with Certora Prover](https://rareskills.io/tutorials/certora-book)
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

- ![certora][certora] [Official documentation for Certora Sunbeam (Soroban) Prover](https://docs.certora.com/en/latest/docs/sunbeam/index.html)
  Setup, CVLR language, Soroban verification guide

- ![certora][certora] [Tutorials for Certora Sunbeam](https://certora-sunbeam-tutorials.readthedocs-hosted.com/en/latest/)
  Hands-on examples for Soroban contract verification

### Articles

- ![certora][certora] [Formally Verifying WebAssembly — A Soroban Case Study](https://www.certora.com/blog/formally-verifying-webassembly)
  Applying FV to Wasm bytecode through Soroban
  <sub>Chandrakana Nandi, Oct 2025</sub>

- ![certora][certora] [Inside Certora's First Soroban Contests — Bringing Formal Verification to Rust](https://www.certora.com/blog/bringing-formal-verification-to-rust)
  Lessons and insights from first Soroban FV competitions
  <sub>Shane Runquist & Chandrakana Nandi, Sept 2025</sub>

- ![certora][certora] [Writing Verification-friendly Smart Contracts in Rust](https://www.certora.com/blog/writing-verification-friendly-smart-contracts-in-rust)
  Rust patterns that simplify formal verification
  <sub>Chandrakana Nandi, Aug 2025</sub>

- ![positive][positive] [Formal Methods for Stellar DeFi: Verifying Lending Protocol with Certora Sunbeam Prover](https://blog.positive.com/formal-methods-for-stellar-defi-verifying-lending-protocol-with-certora-sunbeam-prover-e860a192afac)
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

- ![certora][certora] [Official documentation for Certora Solana Prover](https://docs.certora.com/en/latest/docs/solana/index.html)
  Setup, CVLR language, Solana program verification

### Articles

- ![certora][certora] [Securing Kamino Lending — How Formal Verification Prevented Future Risks](https://www.certora.com/blog/securing-kamino-lending)
  How FV found risks in Kamino's lending protocol
  <sub>Pamina Georgiou, Mar 2025</sub>

- ![certora][certora] [Reviewing Token Extensions on Solana Using Formal Verification](https://www.certora.com/blog/token-extensions-audit)
  FV of Solana SPL token extensions
  <sub>Jorge Navas, Aug 2024</sub>

- ![certora][certora] [Solana Verification Part 3: Formal Verification of the Confidentiality Extension of SPL](https://www.certora.com/blog/spl-extension)
  FV of SPL Confidential Transfer extension
  <sub>Jorge Navas, Aug 2023</sub>

- ![certora][certora] [Solana Verification Part 2: Formal Verification of SPL Token 2022](https://www.certora.com/blog/sol-token)
  FV of SPL Token 2022 standard
  <sub>Jorge Navas, Aug 2023</sub>

- ![certora][certora] [Solana Verification Part 1: Formal Verification of Solana Smart Contracts](https://www.certora.com/blog/sol-formal-verification)
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
[pdf]: https://img.shields.io/badge/%20-EC1C24?style=flat-square
[yt]: https://img.shields.io/badge/%20-FF0000?style=flat-square&logo=youtube&logoColor=white
[certora]: https://img.shields.io/badge/%20-2CB67D?style=flat-square&logoColor=white&logo=data:image/png;base64,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
[rareskills]: https://img.shields.io/badge/%20-7c3aed?style=flat-square&logoColor=white&logo=data:image/svg%2Bxml;base64,PHN2ZyB3aWR0aD0iNDkiIGhlaWdodD0iNzAiIHZpZXdCb3g9IjAgMCA0OSA3MCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTAuMDAyOTI5NjkgMzkuNzJWNjkuODcxM0gxMS44NDgyVjQzLjc3NDJMMC4wMDI5Mjk2OSAzOS43MloiIGZpbGw9InVybCgjcGFpbnQwX2xpbmVhcl83OTdfMTU5KSIvPgo8cGF0aCBkPSJNMC4wMDMwMjMzIDBWNDAuMzAzNkMwLjAwMzAyMzMgNDAuMjUyMiAwIDQ0LjM1MTggMCA0NC4zNTE4TDExLjg1MTMgNDQuMzU0OEgyMC4yNUMyOS40OTIzIDQ0LjM1NDggMzcuMDA1MSA1Mi4xNjA5IDM3LjAwNTEgNjEuNzU2OVY2OS45MDE2SDQ4Ljg1MzVWNjEuNzU2OUM0OC44NTM1IDQ1LjYzMDYgMzYuMDI1NiAzMi41MDk1IDIwLjI1IDMyLjUwOTVIMTEuODUxM1YxMS44NDgzSDIwLjI1QzI5LjQ5MjMgMTEuODQ4MyAzNy4wMDUxIDE5LjY1NDUgMzcuMDA1MSAyOS4yNTA0VjMyLjYzMDRDMzcuMDA1MSAzMi42MzM1IDM3LjAwODIgMzIuNjM2NSAzNy4wMDgyIDMyLjYzOTVWMzYuMjFINDAuNTc4N0M0MC41ODE3IDM2LjIxIDQwLjU4NzggMzYuMjEzIDQwLjU5MzggMzYuMjEzSDQ4Ljg1MzVWMjkuMjUwNEM0OC44NTM1IDEzLjEyMTEgMzYuMDI1NiAwIDIwLjI1IDBIMC4wMDMwMjMzWiIgZmlsbD0idXJsKCNwYWludDFfbGluZWFyXzc5N18xNTkpIi8+CjxkZWZzPgo8bGluZWFyR3JhZGllbnQgaWQ9InBhaW50MF9saW5lYXJfNzk3XzE1OSIgeDE9Ii01LjU4ODA4IiB5MT0iNDUuMzA5NyIgeDI9IjE1LjQxMTMiIHkyPSI2Ni4zMDkxIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSI+CjxzdG9wIHN0b3AtY29sb3I9IiM4NTNDOTIiLz4KPHN0b3Agb2Zmc2V0PSIxIiBzdG9wLWNvbG9yPSIjOTQzRTlEIi8+CjwvbGluZWFyR3JhZGllbnQ+CjxsaW5lYXJHcmFkaWVudCBpZD0icGFpbnQxX2xpbmVhcl83OTdfMTU5IiB4MT0iLTIuMTc3MDgiIHkxPSI1OC4wNzkiIHgyPSI0Ni42NTk0IiB5Mj0iMTUuNjI2MiIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiPgo8c3RvcCBzdG9wLWNvbG9yPSIjOEEzMzkyIi8+CjxzdG9wIG9mZnNldD0iMSIgc3RvcC1jb2xvcj0iIzkzN0FCNyIvPgo8L2xpbmVhckdyYWRpZW50Pgo8L2RlZnM+Cjwvc3ZnPgo=
[positive]: https://img.shields.io/badge/%20-FC3E24?style=flat-square&logoColor=white&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAArklEQVR42q2TTQ6CQAxGXwei8TC6QO9/ADfMaYwhQl0wkwy1I/7QpJtp+/jytcCfIfZBITCnOr2TwFSlqQNc65GyIKAKR6BLKswsUSDmXisbhZPCTWeQl3eFSzkTjJIOOAADMJocgD0JkGdaxygFmpSOBUtzwyebMTVZA3wVoSLzzRaX9bYic3TeH8lE8QCZGpPbOwfQJEhfzniHdLarKj7QC1xfDmmTU97kZ/olnisoRF3PrsgIAAAAAElFTkSuQmCC
