---
title: "EcoBoost: Efficient Bootstrapping for Confidential Transactions"
authors:
- Chenggang Wang
- Boyang Wang
- admin

date: "2020-05-02T00:00:00Z"
doi: "10.1109/ICBC48266.2020.9169416"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE International Conference on Blockchain and Cryptocurrency (ICBC 2020)*"
publication_short: ""

abstract: One of the major challenges of cryptocurrencies is the lack of confidentiality, Without confidentiality, the amount of each transaction on a blockchain is not private. While confidential transactions can hide transaction amounts, its storage overhead is extremely high (e.g., 10~20X). This substantial overhead significantly raises users' overheads in bootstrapping and impedes new nodes, especially for resource-limited devices.We devise a new method, referred to as EcoBoost, to advance the efficiency of bootstrapping for blockchains supporting confidential transactions. Specifically, we harness random sampling to verify the correctness of confidential transactions with high probability. As a result, the verification overhead is sublinear with regard to the number of transactions (compared to linear in current solutions). Our experiment results show that, if Bitcoin implements confidential transactions, EcoBoost can save over 86% storage and verification time in bootstrapping but still detect bogus transactions with a probability of 99%.
---