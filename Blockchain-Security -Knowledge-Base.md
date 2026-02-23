# 🔐 Blockchain Security Knowledge Base
> A curated compilation of the most reputable GitHub repositories and resources for blockchain security, smart contract auditing, DeFi security, and Web3 OpSec — compiled for AI knowledge ingestion and human reference.

---

## 📚 TABLE OF CONTENTS

1. [Best Practices & Foundational Guides](#-1-best-practices--foundational-guides)
2. [Curated Awesome Lists](#-2-curated-awesome-lists)
3. [Audit Reports & Real-World Findings](#-3-audit-reports--real-world-findings)
4. [Attack Vectors & Vulnerability Databases](#-4-attack-vectors--vulnerability-databases)
5. [Security Tools & Static Analysis](#-5-security-tools--static-analysis)
6. [CTF / Hands-On Learning](#-6-ctf--hands-on-learning)
7. [OpSec & Crypto Self-Defense](#-7-opsec--crypto-self-defense)
8. [Courses & Learning Roadmaps](#-8-courses--learning-roadmaps)
9. [Solana-Specific Security](#-9-solana-specific-security)
10. [Zero-Knowledge & Cryptographic Protocol Security](#-10-zero-knowledge--cryptographic-protocol-security)

---

## 🛡️ 1. Best Practices & Foundational Guides

### [ConsenSysDiligence/smart-contract-best-practices](https://github.com/ConsenSysDiligence/smart-contract-best-practices)
> ⭐ 7,590 stars | Org: ConsenSys Diligence (Industry Authority)

**The** canonical reference for Ethereum/Solidity smart contract security.
- Attack pattern explanations (reentrancy, integer overflow, access control, etc.)
- Design patterns for secure contract development
- Solidity-specific recommendations
- Live docs: https://consensysdiligence.github.io/smart-contract-best-practices/

---

### [slowmist/Blockchain-dark-forest-selfguard-handbook](https://github.com/slowmist/Blockchain-dark-forest-selfguard-handbook)
> ⭐ 6,748 stars | Org: SlowMist (Top-tier security firm)

A comprehensive guide to surviving the "dark forest" of blockchain threats.
- Private key protection, wallet security, OpSec
- Social engineering, phishing, clipboard hijacking attack patterns
- Self-custody best practices and threat modeling

---

### [slowmist/Knowledge-Base](https://github.com/slowmist/Knowledge-Base)
> ⭐ 4,483 stars | Org: SlowMist Security Team

SlowMist's internal knowledge base, made public. Covers:
- Incident analysis and post-mortems
- Security research papers and articles
- Attack taxonomy and defense strategies
- Continuously updated (last push: Feb 2026)

---

## 📋 2. Curated Awesome Lists

### [saeidshirazi/Awesome-Smart-Contract-Security](https://github.com/saeidshirazi/Awesome-Smart-Contract-Security)
> Community-curated exhaustive list

Covers:
- Academic papers on smart contract security
- Vulnerability checklists and audit checklists
- CTF challenges, talks, and writeups
- Bug bounty resources and tools
- Formal verification resources

---

### [Raiders0786/web3-security-resources](https://github.com/Raiders0786/web3-security-resources)
Comprehensive hub for:
- Security tools and frameworks
- Real audit reports
- CTF challenges
- Formal verification resources
- Guides for smart contract security research

---

### [0xisk/awesome-solidity-security](https://github.com/0xisk/awesome-solidity-security)
- Research papers on common smart contract defects
- Detailed attack summaries
- Community-maintained reference

---

### [OffcierCia/DeFi-Developer-Road-Map](https://github.com/OffcierCia/DeFi-Developer-Road-Map)
> ⭐ Widely referenced | Maintained by active researcher

Roadmap with links from basic Solidity to advanced DeFi security topics. Excellent structured learning path for AI context.

---

## 📊 3. Audit Reports & Real-World Findings

### [softstack/Smart-Contract-Security-Audits](https://github.com/softstack/Smart-Contract-Security-Audits)
> ⭐ 795 stars | Certified audits for Ethereum, Solana, Near, Cardano, Aptos, Sui, BSC, Fantom, EOS, Tezos

Multi-chain audit report archive — ideal for AI training on real finding patterns.

---

### [TechRate/Smart-Contract-Audits](https://github.com/TechRate/Smart-Contract-Audits)
> ⭐ 577 stars | Active (last push: Sep 2025)

Real-world security audit reports for DeFi, ERC-20, Solidity contracts.

---

### [ContractWolf/smart-contract-audits](https://github.com/ContractWolf/smart-contract-audits)
> ⭐ 703 stars | Actively maintained (last push: Feb 2026)

Large archive of audited smart contracts for reference and pattern matching.

---

### [EthereumCommonwealth/Auditing](https://github.com/EthereumCommonwealth/Auditing)
400+ publicly documented security audits. Open access to reports, findings, and issues. Excellent for training data on vulnerability classification.

---

## ⚔️ 4. Attack Vectors & Vulnerability Databases

### [harendra-shakya/smart-contract-attack-vectors](https://github.com/harendra-shakya/smart-contract-attack-vectors)
Curated real-world smart contract attack vectors with:
- Attack descriptions and examples
- EVM-chain-specific issues
- Best practices to mitigate each attack type
- Audit tips and checklists

---

### [tintinweb/smart-contract-vulndb](https://github.com/tintinweb/smart-contract-vulndb)
Open dataset of smart contract vulnerabilities and security audit findings.
- Structured vulnerability entries
- Ideal for AI vulnerability detection training and classification

---

### [Decurity/semgrep-smart-contracts](https://github.com/Decurity/semgrep-smart-contracts)
> ⭐ 707 stars | Org: Decurity (Security Research Firm)

Semgrep rules for smart contracts, built directly from **real DeFi exploits**.
- Solidity static analysis rules
- Direct mapping from real-world exploits to detectable patterns
- Excellent for AI pattern-matching training

---

## 🔧 5. Security Tools & Static Analysis

### [crytic/slither](https://github.com/crytic/slither)
> By Trail of Bits (Top security firm) | Industry standard tool

Solidity static analysis framework:
- 90+ built-in vulnerability detectors
- Supports integration into CI/CD
- Python API for custom analyses

---

### [crytic/echidna](https://github.com/crytic/echidna)
> By Trail of Bits

Smart contract fuzzer for Ethereum:
- Property-based testing
- Coverage-guided fuzzing
- Solidity & Vyper support

---

### [crytic/manticore](https://github.com/crytic/manticore)
> By Trail of Bits

Symbolic execution tool for smart contracts and binaries.

---

### [ConsenSys/mythril](https://github.com/ConsenSys/mythril)
Security analysis tool for EVM bytecode:
- Detects reentrancy, integer overflows, and more
- Used as backend in MythX

---

### [blocksecteam/rustle](https://github.com/blocksecteam/rustle)
Static analyzer for **NEAR** smart contracts (Rust).
- Expands security tooling beyond Ethereum/EVM

---

## 🎮 6. CTF / Hands-On Learning

### [OpenZeppelin/ethernaut](https://github.com/OpenZeppelin/ethernaut)
> By OpenZeppelin (Industry Authority) | Most famous Web3 CTF

Web3/Solidity wargame:
- 30+ levels of progressively harder smart contract exploits
- Real testnet interaction
- Gold standard for learning attack patterns hands-on

---

### [fravoll/solidity-patterns](https://github.com/fravoll/solidity-patterns)
Patterns for Solidity showing:
- Secure vs. non-secure usage patterns
- Best design practices
- Great for AI to understand what safe code looks like vs. vulnerable code

---

### [tamjid0x01/SmartContracts-audit-checklist](https://github.com/tamjid0x01/SmartContracts-audit-checklist)
> ⭐ 792 stars

Checklist of things to look for when auditing Solidity smart contracts.
- Comprehensive checklist format (ideal for AI prompting)
- Community maintained

---

## 🔒 7. OpSec & Crypto Self-Defense

### [OffcierCia/Crypto-OpSec-SelfGuard-RoadMap](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap)
> ⭐ 1,752 stars | Actively maintained

Best DeFi, Blockchain, and crypto-related OpSec research and data:
- Hardware wallet security
- Seed phrase management
- Phishing & social engineering defense
- Threat modeling for crypto users

---

### [slowmist/Blockchain-dark-forest-selfguard-handbook](https://github.com/slowmist/Blockchain-dark-forest-selfguard-handbook)
*(also listed in Section 1 — dual relevance)*

---

## 🎓 8. Courses & Learning Roadmaps

### [Cyfrin/security-and-auditing-full-course-s23](https://github.com/Cyfrin/security-and-auditing-full-course-s23)
> ⭐ 1,843 stars | By Cyfrin (Patrick Collins)

"The ultimate, most advanced, security, DeFi, assembly, web3 auditor course ever created."
- Covers full auditing methodology
- Assembly-level EVM knowledge
- DeFi security deep dives
- Free and open source (GPL-3.0)

---

### [slowmist/SlowMist-Learning-Roadmap-for-Becoming-a-Smart-Contract-Auditor](https://github.com/slowmist/SlowMist-Learning-Roadmap-for-Becoming-a-Smart-Contract-Auditor)
> ⭐ 896 stars | By SlowMist

Structured learning roadmap for:
- Beginners entering smart contract security
- Experienced engineers transitioning to auditing
- Skills and knowledge checklist format

---

## 🌐 9. Solana-Specific Security

### [sannykim/solsec](https://github.com/sannykim/solsec)
> ⭐ 866 stars

Collection of resources for:
- Solana smart contract security
- Auditing Solana programs
- Real exploit analysis on Solana

---

## 🔐 10. Zero-Knowledge & Cryptographic Protocol Security

### [unionlabs/union](https://github.com/unionlabs/union)
> ⭐ 74,297 stars | Trust-minimized zero-knowledge bridging protocol

Production-grade ZK bridging protocol:
- Real-world implementation of cryptographic security in bridges
- Cross-chain interoperability security model
- Apache 2.0 licensed

---

### [monero-project/monero](https://github.com/monero-project/monero)
> ⭐ 10,343 stars | The canonical privacy blockchain

Security-first cryptocurrency with:
- Ring signatures, stealth addresses, RingCT
- Cryptographic privacy guarantees
- Extensive security documentation in codebase

---

## 🤖 AI / Benchmarks for Blockchain Security

### EVMbench
> By OpenAI/Paradigm — [Paper](https://cdn.openai.com/evmbench/evmbench.pdf)

Benchmark for evaluating AI agents on smart contract vulnerabilities:
- Detect, patch, and exploit tasks
- Automated test grading and curated exploits
- Measures LLM capabilities in security contexts

---

## 🔗 Key GitHub Topics to Explore Further

- [github.com/topics/smart-contract-security](https://github.com/topics/smart-contract-security)
- [github.com/topics/blockchain-security](https://github.com/topics/blockchain-security)
- [github.com/topics/solidity](https://github.com/topics/solidity)
- [github.com/topics/defi](https://github.com/topics/defi)
- [github.com/topics/web3](https://github.com/topics/web3)

---

## 🏛️ Reputable Organizations to Follow on GitHub

| Organization | GitHub | Specialty |
|---|---|---|
| Trail of Bits | [@trailofbits](https://github.com/trailofbits) | Security research & tools (Slither, Echidna) |
| OpenZeppelin | [@OpenZeppelin](https://github.com/OpenZeppelin) | Secure contracts & Ethernaut CTF |
| ConsenSys Diligence | [@ConsenSysDiligence](https://github.com/ConsenSysDiligence) | Auditing & best practices |
| SlowMist | [@slowmist](https://github.com/slowmist) | Incident response & knowledge base |
| Cyfrin | [@Cyfrin](https://github.com/Cyfrin) | Education & auditing courses |
| Decurity | [@Decurity](https://github.com/Decurity) | Semgrep rules & DeFi exploit research |
| BlockSec | [@blocksecteam](https://github.com/blocksecteam) | On-chain monitoring & NEAR security |
| Coinspect | [@coinspect](https://github.com/coinspect) | Wallet security standards |

---

*Last updated: 2026-02-23 | Compiled for AI knowledge base ingestion and human reference*
