## Overview
| GitHub statistics | Top languages |
| ----------------- | ------------- |
| ![Github statistics](https://github-readme-stats-one-taupe-15.vercel.app/api?username=jimmychu0807&show_icons=true) | ![Github top languages](https://github-readme-stats-one-taupe-15.vercel.app/api/top-langs/?username=jimmychu0807&layout=compact&langs_count=5) |

8+ years of software engineering experience across blockchain protocols, smart contracts, and distributed systems, with 6 years of Solidity and 5 years of Rust. Selected for the Ethereum Protocol Fellowship (Cohort 6) — where I integrated zkVM provers into an Ethereum consensus client in Rust. 

Architected and shipped a production EVM-compatible rollup protocol stack at AltLayer using polkadot-sdk and Rust. Deep expertise in advanced cryptography (ZKP , FHE, ECDSA), account abstraction, and cross-chain bridge design. Proven ability to design and communicate complex systems to technical and non-technical audiences across multiple organizations.

For my professional experience, please refer to my [LinkedIn profile](https://www.linkedin.com/in/jimmychu0807).

## Technical Skills

- **Smart Contracts**: Solidity (6 yrs), Foundry, Hardhat, Tenderly, Account Abstraction (ERC-4337, ERC-7579, ERC-7702), Defi (ERC-4626, ERC-7887), T-REX (ERC-3643), Cross-chain (ERC-7683), Trustless agent (ERC-8004)
- **Rust / Systems**: Rust (5 yrs), async/await, tokio, Substrate/polkadot-sdk, Ethereum consensus clients (Grandine, Ream), zkVM (RiscZero, Brevis Pico, Zisk)
- **Cryptography**: ZK-SNARKs, PLONK, Groth16, FHE (Zama fhEVM), ECDSA, KZG commitments, circom, Semaphore
- **Architecture**: Distributed systems design, cross-chain bridge design, protocol specification, EVM internals, rollup architecture, Layer 2 infrastructure
- **Frontend / Integration**: TypeScript (7 yrs), Next.js/React, wagmi, viem, ethers.js
- **DevOps**: Shell, GitHub CI, Docker, Kubernetes, Vercel, AWS, Google Cloud

## Notable Projects

### [**Ethereum Protocol Fellowship — Cohort 6**](https://github.com/jimmychu0807/epf-cohort6-zkvm)
- Selected globally for the Ethereum Protocol Fellowship, a flagship Ethereum Foundation program for core protocol contributors.
- Integrated two zkVM provers — Brevis Pico ([PR#386](https://github.com/grandinetech/grandine/pull/386)) and Zisk ([PR#475](https://github.com/grandinetech/grandine/pull/475)) — into the [Grandine](https://github.com/grandinetech/grandine) Ethereum consensus client in Rust, benchmarking the Ethereum state transition function.
- Delivered a [technical presentation at Devconnect 2025](https://docs.google.com/presentation/d/1a1n-GMzIe9ALcUcrq4O_Tme6zmKSvh-lfnIxbqo7l5o/edit?usp=sharing) on zkVM-based Ethereum state verification.
- Key skills: Rust, zkVM (RiscZero, Brevis Pico, Zisk), Ethereum consensus client (Grandine, Ream), Ethereum spec & testing


#### [**Anonymous Multi-Sig Smart Account Module**](https://github.com/jimmychu0807/semaphore-msa-modules)
- Designed and implemented an ERC-4337 smart account module preserving multi-sig signer privacy using **Semaphore ZK proofs** — one of the first privacy-preserving account abstraction modules on mainnet.
- Awarded a grant by the [**Ethereum Foundation**](https://blog.ethereum.org/2025/02/06/allocation-q4-24#:~:text=Semaphore%20Modular%20Smart%20Contract%20Validator%20Module).
- Key skills: Solidity, Account Abstraction (ERC-4337, ERC-7579), [Semaphore](https://semaphore.pse.dev/), Tenderly, Rhinestone moduleKit, Pimlico
- 🌐 [dApp website](https://semaphore-msa-modules.jimmychu0807.hk/) | 🎥 [Demo video](https://www.loom.com/share/0b800171a4f1491f9eedd4f555569e37) | 📜 [Write up](https://jimmychu0807.hk/semaphore-msa-modules)


##### [**Privacy-Preserving Voting dApp — Zama fhEVM**](https://github.com/jimmychu0807/analytics-dapp-zama)
- Built an on-chain voting system with fully homomorphic encryption: answers encrypted client-side, aggregation computed on-chain without decryption.
- Won [2nd place](https://github.com/zama-ai/bounty-program#:~:text=%F0%9F%A5%88%202nd%20place%3A%20A%20submission%20by%20jimmychu0807) in Zama Bounty Program Season #8.
- Key skills: Solidity, [Zama fhEVM](https://github.com/zama-ai/fhevm), FHE, Hardhat, wagmi, viem
- 🌐 [dApp website](https://analytics-zama.vercel.app) | 🎥 [Demo video](https://www.loom.com/share/13061bce424e4bed9d7f7551d3f5f33d) | 📜 [Write up](https://jimmychu0807.hk/analytics-zama)

[**OpenZeppelin Ethernaut — Security Challenges**](https://github.com/jimmychu0807/openzeppelin-ethernaut-solutions)
- Ranked #18 out of 10k+ participants on the [Ethernaut leaderboard](https://ethernaut.openzeppelin.com/leaderboard#:~:text=18-,jimmychu0807,-39); solved 95% of challenges.
- Key skills: Solidity, Foundry, ECDSA signature exploitation, Typescript

[**ZK Guessing Game — PSE Core Program Capstone**](https://github.com/jimmychu0807/zk-guessing-game)
- Implemented commit-reveal scheme using ZK proofs (circom) for a multi-player on-chain game, ensuring fairness without revealing private inputs.
- Key skills: Solidity, Circom 2, Semaphore, Hardhat, Next.js
- 🌐 [dApp website](https://guessing.jimmychu0807.hk) | 🎥 [Demo video](https://www.youtube.com/watch?v=MrhGMfzsAX0) | 📜 [Write up](https://jimmychu0807.hk/pse-core-capstone-project)
