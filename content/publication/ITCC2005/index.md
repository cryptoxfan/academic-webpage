---
title: "Inversion-Free Arithmetic on Genus 3 Hyperelliptic Curves and Its Implementations"
authors:
- admin
- Thomas Wollinger
- Yumin Wang

date: "2005-04-04T00:00:00Z"
doi: "10.1109/ITCC.2005.179"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Information Technology: Coding and Computing (ITCC 2005)*"
publication_short: ""

abstract: Recently, a lot of effort has been done to investigate all kinds of explicit formulae for speeding up group operation of hyperelliptic curve cryptosystem (HECC). In this paper, explicit formulae without using inversion for genus 3 HECC are given for the first time. When genus 3 HECC is defined over a prime field, our explicit formulae will cost respectively $122M + 9S$, $105M + 8S$ and $110M + 11S$ to perform a group addition, mixed addition and doubling. If we use special genus 3 hyperelliptic curves with $h(x) = 1$ over a binary field, our explicit formulae will need only $119M + 9S$, $102M + 8S$ and $42M + 15S$ for a group addition, mixed addition and doubling, respectively. In the second part of our contribution, we implement inversion-free arithmetic on genus 3 hyperelliptic curves defined over one prime field and three binary fields on a Pentium-M processor and compare the speed of explicit formulae in affine and projective coordinate system. The proposed explicit formulae show excellent performance on Pentium-M processors. We were able to get an increase in performance of over 40% compared to the affine coordinate case. Hence, our newly derived formulae are another step towards the use of HECC in practical applications.
---