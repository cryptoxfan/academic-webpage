---
title: "Warbler: A Lightweight Pseudorandom Number Generator for EPC C1 Gen2 Passive RFID Tags"
authors:
- Kalikinkar Mandal
- admin
- Guang Gong

date: "2013-12-01T00:00:00Z"
doi: "10.20533/ijrfidsc.2046.3715.2013.0011"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal of RFID Security and Cryptography, 2*(1-4)"
publication_short: ""

abstract: A pseudorandom number generator is an important component for implementing security functionalities on RFID tags. Most previous proposals focus on true random number generators that are usually inefficient for low-cost tags in terms of power consumption, area, and throughput. In this contribution, we propose a lightweight pseudorandom number generator (PRNG) for EPC Class-1 Generation-2 (EPC C1 Gen2) RFID tags. The proposed PRNG fully exploits nonlinear feedback shift registers and provides 16-bit random numbers that are required in the tag identification protocol of the EPC C1 Gen2 standard. The generated sequences are able to pass the EPC C1 Gen2 standard's statistical tests as well as the NIST randomness test suite. Moreover, a detailed cryptanalysis shows that the proposed PRNG is resistant to the most common attacks such as algebraic attacks, cube attacks, and time-memorydata tradeoff attacks. In particular, the proposed PRNG can be implemented on low-cost Xilinx Spartan-3 FPGA devices with 46 slices.
---