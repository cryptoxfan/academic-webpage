---
title: "On the Security of Hummingbird-2 Against Side Channel Cube Attacks"
authors:
- admin
- Guang Gong

date: "2011-07-20T00:00:00Z"
doi: "10.1007/978-3-642-34159-5_2"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The 4th Western European Workshop on Research in Cryptology (WEWoRC 2011)*"
publication_short: ""

abstract: Hummingbird-2 is a recently proposed ultra-lightweight cryptographic algorithm targeted for resource-constrained devices like RFID tags, smart cards, and wireless sensor nodes. In this paper, we address the security of the Hummingbird-2 cipher against side channel cube attacks under the single-bit-leakage model. To this end, we describe an efficient term-by-term quadraticity test for extracting simple quadratic equations besides linear ones, obtainable from the original cube attack proposed by Dinur and Shamir at EUROCRYPT 2009. Moreover, we accelerate the implementation of the proposed term-by-term quadraticity test by fully exploiting the power of a Graphic Processing Unit (GPU). Our experimental results show that using a single bit of the internal state during the initialization process of the Hummingbird-2 cipher we can recover the $48$ out of $128$ key bits of the Hummingbird-2 with a data complexity of about $2^{18}$ chosen plaintexts.
---