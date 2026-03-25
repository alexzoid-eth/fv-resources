# Certora Formal Verification Resources

A curated list of resources for Formal Verification with Certora Prover. Please DM me if you'd like to update it.

[General ↓](#general) · [EVM ↓](#evm) · [Stellar ↓](#stellar) · [Solana ↓](#solana)

<img src="https://www.certora.com/gradientlogo.png" height="50" alt="Certora">

### General

### Docs

- <img src="assets/certora.png" height="20"> [Certora Technology White Paper](https://www.certora.com/blog/white-paper)
  How the Prover works, its capabilities and limitations
  <sub>Chandrakana Nandi, Mooly Sagiv & Daniel Jackson, Feb 2025</sub>

- <img src="assets/dravee.png" height="20"> [The Three Prompts of Spec Thinking: Yet Another Lens for Smart Contract Auditing](https://justdravee.github.io/posts/the-3-prompts-of-spec-thinking/)
  Framework for writing properties and invariants through three guiding questions
  <sub>Dravee, Apr 2025</sub>

### Videos

- ![yt][yt] [Why Formal Verification Matters: Fireside Chat with Certora CEO Mooly Sagiv](https://www.youtube.com/watch?v=2tARWL61wCo)
  FV role in smart contract security, Certora vision
  <sub>RareTalks, May 2025</sub>

### Works

- ![gh][gh] [Certora Security Reports](https://github.com/Certora/SecurityReports)
  Collection of formal verification reports across all chains
  <sub>Certora, Mar 2026</sub>

### Libs & Tools

- ![gh][gh] [Certora Prover](https://github.com/Certora/CertoraProver)
  Automated formal verification of smart contracts for EVM, Solana and Stellar
  <sub>Certora, Mar 2026</sub>

- ![gh][gh] [CVLR — Rust verification primitives](https://github.com/Certora/cvlr)
  Rust libraries for writing formal specs of Solana and Soroban contracts
  <sub>Certora, Mar 2026</sub>

- ![gh][gh] [GitHub Action for running Certora Prover](https://github.com/Certora/certora-run-action)
  CI/CD integration for automated Prover runs
  <sub>Certora, Mar 2026</sub>

---

<img src="https://raw.githubusercontent.com/ethereum/ethereum-org-website/dev/public/images/assets/eth-diamond-purple.png" height="50" alt="Ethereum">

### EVM
`In progress — more resources coming soon`

### Docs

- <img src="assets/certora.png" height="20"> [Official documentation for Certora Prover](https://docs.certora.com/en/latest/docs/user-guide/install.html)
  Setup, configuration, CVL language reference and examples

- <img src="assets/rareskills.svg" height="20"> [Book of Formal Verification with Certora Prover](https://rareskills.io/tutorials/certora-book)
  Comprehensive CVL guide from basics to advanced patterns

- <img src="assets/cyfrin.png" height="20"> [Formal Verification & Assembly course](https://updraft.cyfrin.io/courses/formal-verification)
  Video course covering CVL, assembly and FV fundamentals
  <sub>Cyfrin Updraft: Patrick Collins</sub>

- <img src="assets/rasengansec.png" height="20"> [Learning CVL Language](https://rasengansec.hashnode.dev/learning-certora-prover-part-1) ([Part 2](https://rasengansec.hashnode.dev/learning-certora-prover-part-2), [Part 3](https://rasengansec.hashnode.dev/learning-cvl-language-part-3), [Part 4](https://rasengansec.hashnode.dev/learning-cvl-language-part-4))
  Hands-on walkthrough: CVL syntax, rules, invariants, hooks
  <sub>Certora: Lilian Cariou, Mar-Apr 2025</sub>

- <img src="assets/dacian.jpg" height="20"> [Find Highs Before External Auditors Using Certora Formal Verification](https://dacian.me/find-highs-before-external-auditors-using-certora-formal-verification) ([GitHub](https://github.com/devdacian/solidity-fuzzing-comparison))
  Practical guide to finding critical bugs with CVL, fuzzing tools comparison
  <sub>Dacian, Feb 2025</sub>

- <img src="assets/alexzoid.jpg" height="20"> [Certora FV Practical Guide: Insights from the Badger eBTC Competition](https://alexzoid.com/certora-formal-verification-practical-guide)
  Practical workflow and methodology from Badger eBTC FV competition
  <sub>alexzoid, Mar 2025</sub>

- <img src="assets/alexzoid.jpg" height="20"> [Inside Certora FV Contests: A Step-by-Step Guide Based on the Uniswap v4 Contest](https://alexzoid.com/practical-guide-to-certora-formal-verification-contests)
  Contest structure, best practices and mutation bug walkthrough
  <sub>alexzoid, Feb 2025</sub>

- <img src="assets/alexzoid.jpg" height="20"> [First Steps with Certora FV: Catching a Real Bug with a Universal 5-Line Rule](https://alexzoid.com/first-steps-with-certora-fv-catching-a-real-bug)
  Beginner-friendly setup and a universal CVL rule for storage bugs
  <sub>alexzoid, Feb 2025</sub>

### Works

- ![pdf][pdf] [Cozy Finance](https://github.com/Certora/SecurityReports/blob/main/Reports/2026/03_05_2026_Cozy_Finance_FV.pdf)
  DeFi safety protocol FV report
  <sub>Certora, Mar 2026</sub>

- ![pdf][pdf] [Predict](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2026_01_predict_dot_fun_fv_report_cyfrin_alexzoid.pdf)
  Prediction market FV report
  <sub>Cyfrin/alexzoid, Jan 2026</sub>

- ![gh][gh] [Lido Dual Governance](https://github.com/lidofinance/dual-governance)
  Dual governance mechanism with CVL specs
  <sub>Lido, Mar 2026</sub>
- ![pdf][pdf] [Lido V3](https://github.com/Certora/SecurityReports/blob/main/Reports/2026/01_10_2026_Lido_V3_FV.pdf)
  Staking protocol v3 FV report
  <sub>Certora, Jan 2026</sub>
- ![pdf][pdf] [Lido DG ReAudit](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/02_18_2025_Lido_DG_ReAudit-FV-MR.pdf)
  Dual governance re-audit FV report
  <sub>Certora, Feb 2025</sub>
- ![pdf][pdf] [Lido DG](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/02_05_2025_Lido_DG-FV-MR.pdf)
  Dual governance FV report
  <sub>Certora, Feb 2025</sub>

- ![pdf][pdf] [Accountable](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_10_accountable_fv_report_cyfrin_alexzoid.pdf)
  Credit vaults FV report
  <sub>Cyfrin/alexzoid, Oct 2025</sub>

- ![pdf][pdf] [L2 Angstrom](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_09_sorella_l2_angstrom_fv_report_cyfrin_alexzoid.pdf)
  L2 DEX protocol FV report
  <sub>Cyfrin/alexzoid, Sep 2025</sub>

- ![gh][gh] [Licredity](https://github.com/alexzoid-eth/2025-08-licredity-fv)
  Lending protocol FV specs
  <sub>Cyfrin/alexzoid, Aug 2025</sub>

- ![gh][gh] [Safe Locking](https://github.com/safe-fndn/safe-locking)
  Token locking module with CVL specs
  <sub>Safe, May 2024</sub>
- ![gh][gh] [Safe Smart Account](https://github.com/safe-global/safe-smart-account)
  Multisig wallet with CVL specs
  <sub>Safe, Mar 2026</sub>
- ![pdf][pdf] [Safe v1.5.0](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/06_16_2025_Safe_v1.5.0-FV-MR.pdf)
  Multisig wallet v1.5.0 FV report
  <sub>Certora, Jun 2025</sub>

- ![gh][gh] [EigenLayer Contracts](https://github.com/Layr-Labs/eigenlayer-contracts)
  Restaking protocol with CVL specs
  <sub>EigenLayer, Mar 2026</sub>
- ![pdf][pdf] [EigenLayer Slashing](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/02_20_2025_EigenLayer_Slashing-FV-MR.pdf)
  Slashing mechanism FV report
  <sub>Certora, Feb 2025</sub>
- ![pdf][pdf] [EigenLayer PEPE](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/08_12_2024_EigenLayer_PEPE-FV-MR.pdf)
  Restaking protocol FV report
  <sub>Certora, Aug 2024</sub>

- ![gh][gh] [Silo Contracts V3](https://github.com/silo-finance/silo-contracts-v3)
  Lending protocol v3 with CVL specs
  <sub>Silo Finance, Mar 2026</sub>
- ![gh][gh] [Silo V2](https://github.com/alexzoid-eth/silo-v2-cantina-fv)
  Lending protocol v2 FV specs
  <sub>Cantina/alexzoid, Jan 2025</sub>
- ![pdf][pdf] [Silo V2](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/01_07_2025_Silo_V2-FV-MR.pdf)
  Lending protocol v2 FV report
  <sub>Certora, Jan 2025</sub>

- ![pdf][pdf] [Origin Dollar](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/01_15_2025_Origin_Dollar-FV.pdf)
  Yield-bearing stablecoin FV report
  <sub>Certora, Jan 2025</sub>

- ![pdf][pdf] [Liquity Bold](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/12_12_2024_Liquity_Bold-FV.pdf)
  Stablecoin protocol FV report
  <sub>Certora, Dec 2024</sub>

- ![pdf][pdf] [Frax Bamm](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/12_10_2024_Frax_Bamm-FV-MR.pdf)
  AMM protocol FV report
  <sub>Certora, Dec 2024</sub>

- ![pdf][pdf] [Sonic Gateway](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/12_06_2024_Sonic_Gateway-FV-MR.pdf)
  Cross-chain gateway FV report
  <sub>Certora, Dec 2024</sub>

- ![pdf][pdf] [Balancer V3](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/11_27_2024_Balancer_V3-FV-MR.pdf)
  DEX protocol v3 FV report
  <sub>Certora, Nov 2024</sub>

- ![pdf][pdf] [Euler EVK V3](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/09_08_2024_Euler_EVK_V3-FV-MR.pdf)
  Euler Vault Kit v3 FV report
  <sub>Certora, Sep 2024</sub>
- ![pdf][pdf] [Euler Vault](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2024_06_euler_fv_report_cantina_alexzoid.pdf)
  Vault protocol FV report
  <sub>Cantina/alexzoid, Jun 2024</sub>

- ![pdf][pdf] [Uniswap V4 Core](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/09_05_2024_Uniswap_V4_Core-FV-MR.pdf)
  DEX protocol v4 FV report
  <sub>Certora, Sep 2024</sub>

- ![pdf][pdf] [Symbiotic](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/09_02_2024_Symbiotic_Shared_Security_Protocol-FV-MR.pdf)
  Shared security protocol FV report
  <sub>Certora, Sep 2024</sub>

- ![gh][gh] [Aave Governance V3](https://github.com/bgd-labs/aave-governance-v3)
  Governance framework with CVL specs
  <sub>BGD Labs, Feb 2026</sub>
- ![gh][gh] [Aave V3 Origin](https://github.com/aave-dao/aave-v3-origin)
  Lending protocol v3 with CVL specs
  <sub>Aave, Feb 2026</sub>
- ![gh][gh] [Aave V4](https://github.com/aave/aave-v4/tree/certora)
  Lending protocol v4 with CVL specs
  <sub>Aave, Mar 2026</sub>
- ![gh][gh] [GHO Core](https://github.com/aave/gho-core)
  GHO stablecoin with CVL specs
  <sub>Aave, Sep 2025</sub>
- ![pdf][pdf] [Aave Risk Steward](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/06_20_2024_Aave_Risk_Steward-FV-MR.pdf)
  Risk steward module FV report
  <sub>Certora, Jun 2024</sub>
- ![pdf][pdf] [Aave GhoStewardV2](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/03_14_2024_Aave_GhoStewardV2-FV-MR.pdf)
  GHO steward module FV report
  <sub>Certora, Mar 2024</sub>

- ![pdf][pdf] [Warp Exchange](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/05_30_2024_Warp_Exchange-FV-MR.pdf)
  Exchange protocol FV report
  <sub>Certora, May 2024</sub>

- ![pdf][pdf] [Seamless ILM](https://github.com/Certora/SecurityReports/blob/main/Reports/2024/04_08_2024_Seamless_ILM-FV-MR.pdf)
  Integrated liquidity market FV report
  <sub>Certora, Apr 2024</sub>

- ![gh][gh] [Morpho Blue](https://github.com/morpho-org/morpho-blue)
  Lending protocol with CVL specs
  <sub>Morpho, Feb 2026</sub>
- ![gh][gh] [Morpho Pre Liquidation](https://github.com/morpho-org/pre-liquidation)
  Pre-liquidation module with CVL specs
  <sub>Morpho, Mar 2026</sub>
- ![gh][gh] [Morpho Vault V2](https://github.com/morpho-org/vault-v2)
  Vault module with CVL specs
  <sub>Morpho, Mar 2026</sub>

- ![gh][gh] [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts/tree/update/certora-7.3.0)
  Standard library with CVL specs
  <sub>OpenZeppelin, Mar 2026</sub>

- ![gh][gh] [Certora Examples](https://github.com/Certora/Examples)
  Reference CVL examples and patterns
  <sub>Certora, Mar 2026</sub>

- ![gh][gh] [Certora Vault Tutorial](https://github.com/Certora/certora-vault-tutorial)
  Step-by-step vault verification tutorial
  <sub>Certora, Nov 2025</sub>

### Libs & Tools

- ![gh][gh] [AI Composer](https://github.com/Certora/AIComposer)
  AI-powered generation of verified implementations from docs and CVL specs
  <sub>Certora, Mar 2026</sub>

- ![gh][gh] [Gambit — Mutant Generation for Solidity](https://github.com/Certora/gambit)
  Mutation testing to evaluate quality of test suites and FV specs
  <sub>Certora, May 2025</sub>

---

<img src="https://github.com/stellar/.github/raw/master/stellar-logo.png" height="50" alt="Stellar">

### Stellar
`updated: March 2026`

### Docs

- <img src="assets/certora.png" height="20"> [Official documentation for Certora Sunbeam (Soroban) Prover](https://docs.certora.com/en/latest/docs/sunbeam/index.html)
  Setup, CVLR language, Soroban verification guide

- <img src="assets/certora.png" height="20"> [Tutorials for Certora Sunbeam](https://certora-sunbeam-tutorials.readthedocs-hosted.com/en/latest/)
  Hands-on examples for Soroban contract verification

- ![gh][gh] [Sunbeam Tutorials — source code](https://github.com/Certora/sunbeam-tutorials)
  Tutorial projects and example specs for Soroban verification
  <sub>Certora, Nov 2025</sub>

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

### Works

- ![gh][gh] [Aquarius](https://github.com/alexzoid-eth/aquarius-cantina-fv/tree/main/fees_collector/src/certora_specs)
  Verification specs for fees_collector module
  <sub>Cantina/alexzoid, #2 place, Jun 2025</sub>
- ![gh][gh] [Aquarius — top winners](https://github.com/Certora/aquarius-cantina-fv/tree/main/Example_Submissions)
  Winning submissions from Aquarius FV competition
  <sub>Certora competition, Aug 2025</sub>
- ![gh][gh] [Aquarius FV Competition Report](https://github.com/Certora/aquarius-cantina-fv/blob/main/Report.md)
  Competition results and findings summary
  <sub>Cantina, Jun 2025</sub>

- ![gh][gh] [Blend v2](https://github.com/Certora/blend-contracts-v2/tree/certora/pool/src/spec)
  Official pool verification specs
  <sub>Certora, Jun 2025</sub>
- ![gh][gh] [Blend v2](https://github.com/alexzoid-eth/2025-02-blend-fv/tree/main/blend-contracts-v2/backstop)
  Backstop module verification specs
  <sub>Code4rena/alexzoid, #1 place, Feb 2025</sub>
- ![gh][gh] [Blend v2 FV Competition Report](https://github.com/code-423n4/2025-02-blend-fv/blob/main/Report.md)
  Competition results and findings summary
  <sub>Code4rena, Feb-Mar 2025</sub>
- ![pdf][pdf] [Blend v2](https://github.com/alexzoid-eth/2025-02-blend-fv/blob/main/blend-contracts-v2/backstop/2025_02_blend_v2_backstop_fv_report_alexzoid.pdf)
  Backstop module FV report
  <sub>Code4rena/alexzoid, Feb 2025</sub>
- ![gh][gh] [Blend v1](https://github.com/Certora/blend-contracts/tree/certora/pool/src/spec)
  Pool verification specs
  <sub>Certora, Jan 2025</sub>
- ![pdf][pdf] [Blend v1](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/01_30_2025_Blend_V1-FV.pdf)
  Pool module FV report
  <sub>Certora, Feb 2025</sub>

- ![gh][gh] [Meridian Certora Workshop](https://github.com/Certora/meridian2024-workshop)
  Simple introductory Sunbeam example
  <sub>Certora, Feb 2025</sub>

- ![gh][gh] [OpenZeppelin Contracts for Stellar Soroban](https://github.com/Certora/stellar-contracts/tree/certora/packages/access/src/ownable/specs)
  Formal specs for Ownable access control module
  <sub>Certora, Mar 2026</sub>

### Libs & Tools

- ![gh][gh] [CVLR for Soroban smart contracts](https://github.com/Certora/cvlr-soroban)
  Rust library for writing verification specs on Soroban
  <sub>Certora, Feb 2026</sub>

---

<img src="https://solana.com/src/img/branding/solanaLogoMark.svg" height="50" alt="Solana">

### Solana
`updated: March 2026`

### Docs

- <img src="assets/certora.png" height="20"> [Official documentation for Certora Solana Prover](https://docs.certora.com/en/latest/docs/solana/index.html)
  Setup, CVLR language, Solana program verification

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

### Works

- ![pdf][pdf] [Deriverse DEX](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_11_deriverse_fv_report_cyfrin_alexzoid.pdf)
  DEX protocol FV findings
  <sub>Cyfrin/alexzoid, Nov 2025</sub>

- ![pdf][pdf] [Kamino LIMO](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_28_2025_Kamino_LIMO.pdf)
  Limit order protocol FV findings
  <sub>Certora, Jul 2025</sub>
- ![pdf][pdf] [Kamino Vault](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/07_07_2025_Kamino_Vault.pdf)
  Yield management protocol FV findings
  <sub>Certora, Jul 2025</sub>
- ![pdf][pdf] [Kamino Lending](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/02_24_2025_Kamino_Lending-FV-MR.pdf)
  Lending protocol FV findings
  <sub>Certora, Feb 2025</sub>

- ![gh][gh] [Solana applications verification examples](https://github.com/Certora/SolanaExamples/tree/main/cvlr_by_example)
  CVLR by example: practical verification patterns
  <sub>Certora, Mar 2026</sub>

- ![gh][gh] [Certora Tokenized Vault for Solana Tutorial](https://github.com/Certora/certora-vault-tutorial/tree/main/programs/vault/src/certora)
  Step-by-step tokenized vault verification
  <sub>Certora, Nov 2025</sub>

- ![pdf][pdf] [Squads multi-signature wallet](https://github.com/Certora/SecurityReports/blob/main/Reports/2025/02_15_2025_Squads-FV-MR.pdf)
  Multisig wallet FV findings
  <sub>Certora, Feb 2025</sub>

- ![gh][gh] [Examples from Prover's Public/TestSolana directory](https://github.com/Certora/CertoraProver/tree/master/Public/TestSolana)
  Reference specs from Prover's test suite
  <sub>Certora, Mar 2026</sub>

### Libs & Tools

- ![gh][gh] [CVLR library for Solana](https://github.com/Certora/cvlr-solana)
  Rust library for writing verification specs on Solana
  <sub>Certora, Jan 2026</sub>

- ![gh][gh] [Solana spec template](https://github.com/Certora/solana-spec-template)
  Boilerplate for new Solana FV projects
  <sub>Certora, Jan 2026</sub>

- ![gh][gh] [cargo-certora-sbf](https://github.com/Certora/cargo-certora-sbf)
  Compiles Solana programs for Certora Prover
  <sub>Certora, Mar 2026</sub>

- ![gh][gh] [Certora Solana Platform Tools](https://github.com/Certora/certora-solana-platform-tools)
  Solana build toolchain for verification
  <sub>Certora, Mar 2026</sub>

<!-- Badge references -->
[gh]: https://img.shields.io/badge/%20-181717?style=flat-square&logo=github&logoColor=white
[pdf]: https://img.shields.io/badge/PDF-EC1C24?style=flat-square
[yt]: https://img.shields.io/badge/%20-FF0000?style=flat-square&logo=youtube&logoColor=white
