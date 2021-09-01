---
title: "KCRS: A Blockchain-Based Key Compromise Resilient Signature System"
authors:
- Lei Xu
- Lin Chen
- Zhimin Gao
- admin
- Kimberly Doan
- Shouhuai Xu
- Weidong Shi

date: "2019-12-06T00:00:00Z"
doi: "10.1007/978-981-15-2777-7_19"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The First International Conference on Blockchain and Trustworthy Systems (BlockSys'2019)*"
publication_short: ""

abstract: Digital signatures are widely used to assure authenticity and integrity of messages (including blockchain transactions). This assurance is based on assumption that the private signing key is kept secret, which may be exposed or compromised without being detected in the real world. Many schemes have been proposed to mitigate this problem, but most schemes are not compatible with widely used digital signature standards and do not help detect private key exposures. In this paper, we propose a Key Compromise Resilient Signature (KCRS) system, which leverages blockchain to detect key compromises and mitigate the consequences. Our solution keeps a log of valid certificates and digital signatures that have been issued on the blockchain, which can deter the abuse of compromised private keys. Since the blockchain is an open system, KCRS also provides a privacy protection mechanism to prevent the public from learning the relationship between signatures. We present a theoretical framework for the security of the system and a provably-secure construction. We also implement a prototype of KCRS and conduct experiments to demonstrate its practicability.

links:
- name: Best Paper Award
  url: publication/blocksys2019/Award.pdf
---