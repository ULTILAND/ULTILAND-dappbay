# Ultiland ARToken Launchpad

Ultiland ARToken Launchpad enables artists, studios, and IP holders to launch project-specific tokens for real-world assets (RWAs) and intellectual property (IP) on **BNB Smart Chain (BSC)**. [Ultiland overview](https://docs.ultiland.io/about-ultiland/the-brief)

## Technology Stack

- **Blockchain** — BNB Smart Chain (EVM-compatible)
- **Smart contracts** — Solidity 0.8.20
- **Frontend** — Next.js and ethers.js
- **Development** — Hardhat

## Supported Networks

| Network | Chain ID |
| --- | --- |
| BNB Smart Chain Mainnet | 56 |

## Contract Addresses

| Network | Core Contract | ARTX Token | miniARTX Token |
| --- | --- | --- | --- |
| BNB Smart Chain Mainnet | [`0x88f01f6a73125e18385b2b005195033Af3Ab1C9F`](https://bscscan.com/address/0x88f01f6a73125e18385b2b005195033af3ab1c9f) | [`0x8105743e8A19c915a604D7D9e7aa3A060A4C2c32`](https://bscscan.com/address/0x8105743e8a19c915a604d7d9e7aa3a060a4c2c32) | [`0x905fA52f2927a7cddaA4CEA8a47f89fB9075200D`](https://bscscan.com/token/0x905fa52f2927a7cddaa4cea8a47f89fb9075200d) |

The core contract creates individual project tokens. [Example token creation record](https://bscscan.com/token/0x84cb6967252e854602297f35c45e699277784118?a=0x97e03f850a139281f7b65236e3b786a9835bb673)

## Features

- **RWA tokenization** — Launch an ARToken for an artwork or collectible. Ultiland’s documented issuance model combines AI-assisted appraisal with third-party valuation and uses that valuation and the token supply to set a uniform subscription price. The offering terms specify custody and any asset-linked benefits. [RWA tokenization](https://docs.ultiland.io/launchpad/tokenization)
- **IP launches** — Structure an offering around a creative work, design, or brand. Ultiland’s white paper describes IPFS-based metadata references and IProtocol support for IP registration, licensing permissions, and royalty distribution. The launch terms define which rights or benefits apply. [Technology and IProtocol](https://docs.ultiland.io/white-paper/4.-technology)
- **ARTX and miniARTX dual-token model** — ARTX supports platform payments and governance. miniARTX records contributions and can be released into ARTX at a documented 1:1 ratio under the applicable release schedule. [Tokenomics](https://docs.ultiland.io/white-paper/6.-tokenomics) · [Ultiland FAQ](https://docs.ultiland.io/about-ultiland/the-know)
- **Project-specific tokens** — Each launch issues its own ARToken. ARTX and miniARTX serve roles across the Ultiland platform, while each ARToken follows the terms of its individual offering. [White paper introduction](https://docs.ultiland.io/white-paper/1.-introduction)
- **Participation rewards** — Eligible activity, including ARToken subscriptions and liquidity participation, can earn Inspiration Power that counts toward miniARTX rewards. [Tokenomics](https://docs.ultiland.io/white-paper/6.-tokenomics) · [RWA tokenization](https://docs.ultiland.io/launchpad/tokenization)
