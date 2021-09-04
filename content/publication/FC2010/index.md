---
title: "Hummingbird: Ultra-Lightweight Cryptography for Resource-Constrained Devices"
authors:
- Daniel W. Engels
- admin
- Guang Gong
- Honggang Hu
- Eric M. Smith

date: "2010-01-25T00:00:00Z"
doi: "10.1007/978-3-642-14992-4_2"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Financial Cryptography and Data Security, FC 2010 Workshops, RLCPS, WECSR, and WLC 2010*"
publication_short: ""

abstract: Due to the tight cost and constrained resources of high-volume consumer devices such as RFID tags, smart cards and wireless sensor nodes, it is desirable to employ lightweight and specialized cryptographic primitives for many security applications. Motivated by the design of the well-known Enigma machine, we present a novel ultra-lightweight cryptographic algorithm, referred to as Hummingbird, for resource-constrained devices in this paper. Hummingbird can provide the designed security with small block size and is resistant to the most common attacks such as linear and differential cryptanalysis. Furthermore, we also present efficient software implementation of Hummingbird on the 8-bit microcontroller ATmega128L from Atmel and the 16-bit microcontroller MSP430 from Texas Instruments, respectively. Our experimental results show that after a system initialization phase Hummingbird can achieve up to 147 and 4.7 times faster throughput for a size-optimized and a speed-optimized implementations, respectively, when compared to the state-of-the-art ultra-lightweight block cipher PRESENT[10] on the similar platforms.
---