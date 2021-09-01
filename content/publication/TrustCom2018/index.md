---
title: "Lightweight Verification for Searchable Encryption"
authors:
- Boyang Wang
- admin

date: "2018-08-01T00:00:00Z"
doi: "10.1109/TrustCom/BigDataSE.2018.00132"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The 17th IEEE International Conference On Trust, Security And Privacy In Computing And Communications (TrustCom 2018)*"
publication_short: ""

abstract: Symmetric Searchable Encryption (SSE) is a promising primitive to securely perform keyword queries and to efficiently retrieve associated files from a curious server without sacrificing data privacy. Unfortunately, besides being curious, an untrusted server could also be malicious, which would return incorrect or incomplete results to a client. Since a client does not maintain its entire dataset locally after outsourcing, preventing malicious servers is necessary and challenging. In this paper, we propose a lightweight Verifiable SSE scheme, which can verify the correctness and completeness of keyword search results obtained from SSE against a malicious server. Our scheme not only achieves an asymptotically efficient verification time and communication overhead, but also outperforms previous solutions in practice. Moreover, our scheme can efficiently support updates on verification metadata. We formally define and analyze the security of our scheme, and conduct extensive experiments on massive datasets to demonstrate the efficiency of our scheme.
---