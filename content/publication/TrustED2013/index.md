---
title: "Efficient Hardware Implementation of the Stream Cipher WG-16 with Composite Field Arithmetic"
authors:
- admin
- Nusa Zidaric
- Mark Aagaard
- Guang Gong

date: "2013-11-04T00:00:00Z"
doi: "10.1145/2517300.2517305"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The 2013 ACM Workshop on Trustworthy Embedded Devices (TrustED 2013)*"
publication_short: ""

abstract: The Welch-Gong (WG) stream cipher family was designed based on the WG transformation and is able to generate keystreams with mathematically proven randomness properties such as long period, balance, ideal tuple distribution, ideal two-level autocorrelation and high and exact linear complexity. In this paper, we present a compact hardware architecture and its pipelined implementation of the stream cipher WG-16, an efficient instance of the WG stream cipher family, using composite field arithmetic and a newly proposed property of the trace function in tower field representation. Instead of using the original binary field $F_{2^16}$, we demonstrate that its isomorphic tower field $F_{(((2^2)^2)^2)^2}$ can lead to a more efficient hardware implementation. Efficient conversion matrices connecting the binary field F2^16 and the tower field $F_{(((2^2)^2)^2)^2}$ are also derived. Our implementation results show that the pipelined WG-16 hardware core can achieve the throughput of 124 MHz at the cost of 478 slices in an FPGA and 552 MHz at the cost of 12,031 GEs in a 65 nm ASIC, respectively.
---