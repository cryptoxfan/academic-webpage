---
title: "TPU as Cryptographic Accelerator"
authors:
- Rabimba Karanjai
- Sangwon Shin
- Wujie Xiong
- admin
- Lin Chen
- Tianwei Zhang
- Taeweon Suh
- Weidong Shi
- Veronika Kuchta
- Francesco Sica
- Lei Xu

date: "2024-11-02T00:00:00Z"
doi: "10.1145/3696843.3696844"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The 13th International Workshop on Hardware and Architectural Support for Security and Privacy (HASP 2024)*"
publication_short: ""

abstract: Cryptographic schemes like Fully Homomorphic Encryption (FHE) and Zero-Knowledge Proofs (ZKPs), while offering powerful privacy-preserving capabilities, are often hindered by their computational complexity. Polynomial multiplication, a core operation in these schemes, is a major performance bottleneck. While algorithmic advancements and specialized hardware like GPUs and FPGAs have shown promise in accelerating these computations, the recent surge in AI accelerators (TPUs/NPUs) presents a new opportunity. This paper explores the potential of leveraging TPUs/NPUs to accelerate polynomial multiplication, thereby enhancing the performance of FHE and ZKP schemes. We present techniques to adapt polynomial multiplication to these AI-centric architectures and provide a preliminary evaluation of their effectiveness. We also discuss current limitations and outline future directions for further performance improvements, paving the way for wider adoption of advanced cryptographic tools.
---