---
title: "Speeding Up Multi-scalar Multiplications for Pairing-Based zkSNARKs"
authors:
- admin
- Veronika Kuchta
- Francesco Sica
- Lei Xu

date: "2025-04-03T00:00:00Z"
doi: "10.1007/s00145-025-09540-x"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Cryptology*"
publication_short: ""

abstract: Multi-scalar multiplication (MSM) is a fundamental component in many zero-knowledge succinct non-interactive argument systems (ZK-SNARKs) and a major performance bottleneck in proof generation for these schemes. One key strategy to accelerate MSM is through precomputation. Several algorithms, such as Pippenger’s and BGMW, along with their variations, have been proposed to address this. In this paper, we revisit the recent precomputation-based MSM method introduced by Luo et al. (IACR Trans Cryptogr Hardw Embed Syst 2023(2):358–380, 2023. https://doi.org/10.46586/tches.v2023.i2.358-380) and extend their approach. Specifically, we present a generalized construction for optimal buckets. Given a set of multipliers M, we propose an algorithm that identifies the optimal bucket set B to minimize the computation time. This new construction yields performance improvements over the original Pippenger’s MSM method, as demonstrated through both theoretical analysis and experimental results. Additionally, we correct Property 1 in the MSM method from Luo et al. (2023), providing the corresponding experimental validations. To further enhance run-time efficiency and reduce storage requirements, we propose the use of an efficient endomorphism, supported by theoretical and experimental analysis.
---