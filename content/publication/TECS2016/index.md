---
title: "Design and Implementation of Warbler Family of Lightweight Pseudorandom Number Generators for Smart Devices"
authors:
- Kalikinkar Mandal
- admin
- Guang Gong

date: "2016-02-01T00:00:00Z"
doi: "10.1145/2808230"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*ACM Transactions on Embedded Computing Systems, 15*(1)"
publication_short: ""

abstract: With the advent of ubiquitous computing and the Internet of Things (IoT), the security and privacy issues for various smart devices such as radio-frequency identification (RFID) tags and wireless sensor nodes are receiving increased attention from academia and industry. A number of lightweight cryptographic primitives have been proposed to provide security services for resource-constrained smart devices. As one of the core primitives, a cryptographically secure pseudorandom number generator (PRNG) plays an important role for lightweight embedded applications. The most existing PRNGs proposed for smart devices employ true random number generators as a component, which generally incur significant power consumption and gate count in hardware. In this article, we present Warbler family, a new pseudorandom number generator family based on nonlinear feedback shift registers (NLFSRs) with desirable randomness properties. The design of the Warbler family is based on the combination of modified de Bruijn blocks together with a nonlinear feedback Welch-Gong (WG) sequence generator, which enables us to precisely characterize the randomness properties and to flexibly adjust the security level of the resulting PRNG. Some criteria for selecting parameters of the Warbler family are proposed to offer the maximum level of security. Two instances of the Warbler family are also described, which feature two different security levels and are dedicated to EPC C1 Gen2 RFID tags and wireless sensor nodes, respectively. The security analysis shows that the proposed instances not only can pass the cryptographic statistical tests recommended by the EPC C1 Gen2 standard and NIST but also are resistant to the cryptanalytic attacks such as algebraic attacks, cube attacks, time-memory-data tradeoff attacks, Mihaljević et al.’s attacks, and weak internal state and fault injection attacks. Our ASIC implementations using a 65nm CMOS process demonstrate that the proposed two lightweight instances of the Warbler family can achieve good performance in terms of speed and area and provide ideal solutions for securing low-cost smart devices.
---