---
title: "Scalable Practical Byzantine Fault Tolerance with Short-Lived Signature Schemes"
authors:
- admin

date: "2018-10-29T00:00:00Z"
doi: "10.5555/3291291.3291316"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The 28th Annual International Conference on Computer Science and Software Engineering (CASCON 2018)*"
publication_short: ""

abstract: The Practical Byzantine Fault Tolerance (PBFT) algorithm is a popular solution for establishing consensus in blockchain systems. The execution time of the PBFT consensus algorithm has an important effect on the blockchain throughput. Digital signatures are extensively used in PBFT to ensure the authenticity of messages during the different phases. Due to the round-based and broadcast natures of PBFT, nodes need to verify multiple signatures received from their peers, which incurs significant computational overhead and slows down the consensus process. To address this issue, we propose an efficient short-lived signature based PBFT variant, which utilizes short-length cryptographic keys to sign/verify messages in PBFT for a short period of time and blockchain-aided key distribution mechanisms to update those keys periodically. We also present efficient algorithms for accelerating the software implementation of the BLS threshold signature scheme. Our extensive experiments with three elliptic curves and two signature schemes demonstrate the efficacy of using short-lived signature schemes for improving the scalability of PBFT significantly.
---