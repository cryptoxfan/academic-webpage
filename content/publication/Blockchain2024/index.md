---
title: "Towards Credential-Based Device Registration in DApps for DePINs with ZKPs"
authors:
- Jonathan Heiss
- Fernando Castillo
- admin

date: "2024-08-19T00:00:00Z"
doi: "10.1109/Blockchain62396.2024.00086"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2024 IEEE International Conference on Blockchain (Blockchain 2024)*"
publication_short: ""

abstract: Decentralized Physical Infrastructure Networks (De-PINS) are secured and governed by blockchains but beyond crypto-economic incentives, they lack measures to establish trust in participating devices and their services. The verification of relevant device credentials during device registration helps to overcome this problem. However, on-chain verification in decentralized applications (dApp) discloses potentially confidential device attributes whereas off-chain verification introduces undesirable trust assumptions. In this paper, we propose a credential-based device registration (CDR) mechanism that verifies device credentials on the blockchain and leverages zero-knowledge proofs (ZKP) to protect confidential device attributes from being disclosed. We characterize CDR for DePINs, present a general system model, and technically evaluate CDR using zkSNARKs with Groth16 and Marlin. Our experiments give first insights into performance impacts and reveal a tradeoff between the applied proof systems.
---