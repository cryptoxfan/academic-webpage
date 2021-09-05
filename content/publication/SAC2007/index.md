---
title: "Efficient Explicit Formulae for Genus 2 Hyperelliptic Curves over Prime Fields and Their Implementations"
authors:
- admin
- Guang Gong

date: "2007-08-16T00:00:00Z"
doi: "10.1007/978-3-540-77360-3_11"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The 14th Annual Workshop on Selected Areas in Cryptography (SAC 2007)*"
publication_short: ""

abstract: We analyze all the cases and propose the corresponding explicit formulae for computing $2D_1 + D_2$ in one step from given divisor classes $D_1$ and $D_2$ on genus 2 hyperelliptic curves defined over prime fields. Compared with naive method, the improved formula can save two field multiplications and one field squaring each time when the arithmetic is performed in the most frequent case. Furthermore, we present a variant which trades one field inversion for fourteen field multiplications and two field squarings by using Montgomery’s trick to combine the two inversions. Experimental results show that our algorithms can save up to 13% of the time to perform a scalar multiplication on a general genus 2 hyperelliptic curve over a prime field, when compared with the best known general methods.
---