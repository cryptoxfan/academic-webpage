---
title: "Efficient Doubling on Genus 3 Curves over Binary Fields"
authors:
- admin
- Thomas Wollinger
- Yumin Wang

date: "2006-02-13T00:00:00Z"
doi: "10.1007/11605805_5"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*The Cryptographer's Track at the RSA Conference (CT-RSA 2006)*"
publication_short: ""

abstract: The most important and expensive operation in a hyperelliptic curve cryptosystem (HECC) is the scalar multiplication by an integer k, i.e., computing an integer k times a divisor D on the Jacobian. Using some recoding algorithms for the scalar, we can reduce the number of divisor class additions during the process of computing the scalar multiplication. On the other side, the divisor doublings will stay the same for all kinds of scalar multiplication algorithms. In this paper we accelerate the divisor doublings for genus 3 HECC over binary fields by using special types of curves. Depending on the degree of h, our explicit formulae only require $1I + 11M + 11S$, $1I + 13M + 13S$, $1I + 20M + 12S$ and $1I + 26M + 11S$ for divisor doublings in the best case, respectively. Especially, for the case of deg $h = 1$, our explicit formula improve the recent result in [GKP04] significantly by saving $31M$ at the cost of extra $7S$. In addition, we discuss some cases which are not included in [GKP04].

By constructing birational transformation of variables, we derive explicit doubling formulae for special types of equations of the curve. For each type of curve, we analyze how many field operations are needed. So far no attack on any of the all curves suggested in this paper is known, even though some cases are very special. Our results allow to choose curves from a large variety which have extremely fast doubling needing only one third the time of an addition in the best case. Furthermore, an actual implementation of the new formulae on a Pentium-M processor shows their practical relevance.
---