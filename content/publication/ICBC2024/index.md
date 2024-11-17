---
title: "Enabling a Smooth Migration Towards Post-Quantum Security for Ethereum"
authors:
- admin
- Teik Guan Tan
- Nicholas Ho 
- Shi Hong Choy 

date: "2024-11-15T00:00:00Z"
doi: "10.1007/978-3-031-77095-1_1"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2024 International Conference on Blockchain (ICBC 2024)*"
publication_short: ""

abstract: Digital signatures based on Elliptic Curve Digital Signing Algorithm (ECDSA) are widely used in Ethereum to secure transactions and Proof-of-Stake (PoS) consensus protocols. However, those digital signatures are vulnerable to quantum computing and therefore endanger the security of Ethereum and its millions of users’ crypto assets. Based on the previous work in [16, 17], we present two proposals for a smooth migration of Ethereum towards post-quantum security in this paper. While the first proposal introduces a new Ethereum transaction type to encapsulate a quantum-safe zero-knowledge proof, the second one further improves system scalability via proof aggregation and zero-knowledge rollups. Our proposals only introduce minimal changes to the software running on Ethereum validators and clients, thereby achieving great backward compatibility. We report our initial evaluation results of the two proposals on Microsoft’s Azure cloud platform and highlight the key observations, in the area of improving proof generation timing and proof sizes, for deploying our solutions in practice.

links:
- name: Best Paper Award
  url: publication/icbc2024/Award.pdf
---