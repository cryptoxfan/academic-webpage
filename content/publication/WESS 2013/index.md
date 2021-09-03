---
title: "Design Space Exploration of the Lightweight Stream Cipher WG-8 for FPGAs and ASICs"
authors:
- Gangqiang Yang
- admin
- Mark Aagaard
- Guang Gong

date: "2013-09-29T00:00:00Z"
doi: "10.1145/2527317.2527325"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The 8th Workshop on Embedded Systems Security (WESS 2013)*"
publication_short: ""

abstract: WG-8 is a lightweight instance of the Welch-Gong (WG) stream cipher family, targeting for resource-constrained devices like RFID tags, smart cards, and wireless sensor nodes. Recent work has demonstrated the advantages of tower field constructions for finite field arithmetic in the AES and WG-16 ciphers. In this paper we explore three different tower field constructions for WG-8. The first tower field is tailored to FPGA cells. The second tower field uses a Type-I optimal normal basis. The third tower field exploits algebraic properties of the WG permutation and trace functions. All of the methods use a parallel LFSR to provide data rates from one to eleven bits per clock cycle. Among the three tower fields, the Type-I ONB construction offers the best trade-off in area, speed, and power consumption. However, a plain monolithic look-up table implementation with 256 entries is smaller and faster than the tower field constructions. Our analysis of the tower field options and comparisons to each other and to the monolithic look-up table will provide lessons for future work in exploring novel tower field constructions for WG and other ciphers.
---