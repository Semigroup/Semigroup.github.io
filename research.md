---
title: Research
permalink: /research/
---
# Main Area
## Cryptanalysis
Cryptography decomposes into two halves.
The constructive half devises schemes and protocols.
The analytic half produces evidence that those schemes and protocols 
actually provide privacy, confidentiality, authenticity, integrity, etc.

## Algebraic Cryptanalysis
Algebraic solving algorithms based on Gröbner bases and Macaulay matrices
can be seen as the Swiss army knives of cryptanalysis, as they can be applied
to most cryptographic problems.
Despite their power and ubiquity, the performance of algebraic solvers
is not well understood.
To estimate their runtimes, questionable heuristics are still employed.

## Provability and a Theoretical Framework
As principal investigator of the FWF ESPRIT research project [ProvACAna: Provable Algebraic CryptAnalysis](https://www.fwf.ac.at/en/research-radar/10.55776/ESP1735525),
I aim to construct a framework for comparing different algebraic approaches
and rigorously bounding their time complexities, solving degrees, degrees of regularity, etc.
This framework aims to make assumptions like the semiregularity heuristic (Fröberg's conjecture)
obsolete and improve our understanding of algebraic cryptanalysis,
as a good understanding is a necessary foundation for new and faster attacks.

# Other Research
I am also working in other areas of cryptographic and cryptanalysis.
Selected Examples:

## Lattice-Based Cryptography
With [Erkan Tairi](https://erkantairi.com/), I proved impossibility results for lattice-based
functional encryption schemes 
[eprint](https://eprint.iacr.org/2020/163),
[eprint](https://eprint.iacr.org/2023/719).

With [Ivy K.Y. Woo](https://ivyw.ooo/) and [Chris Brzuska](https://www.aalto.fi/en/people/chris-brzuska),
I broke the very popular private-coin version of the evasive LWE assumption 
[eprint](https://eprint.iacr.org/2024/2000).

## Cryptanalysis of Lightweight Pseudorandom Number Generators
I did some algebraic cryptanalysis
on PRGs of low degree/locality 
[eprint](https://eprint.iacr.org/2023/119),
[eprint](https://eprint.iacr.org/2023/550).

With [Pierrick Méaux](https://pierrickmeaux.com/)
and Antonio Giulio D’Antona, I attacked the popular
class of THR-XOR PRGs and introduced the notion of common bias
[eprint](https://eprint.iacr.org/2026/880).

## Generic Group Lower Bounds
I am interested in lower bounds for group-based
primitives in ideal models.
[Julia Kastner](https://juliakastner.github.io/), [Nicholas Brandt](https://nicholasbrandt.de/),
[Bogdan Ursu](https://bogdanbear.github.io/) and [Dennis Hofheinz](https://people.inf.ethz.ch/dhofheinz/)
and I established lower bounds for VRFs and LTFs in the
generic group model [eprint](https://eprint.iacr.org/2022/762),
[eprint](https://eprint.iacr.org/2023/866).

I also like to work on constructions in the generic group model
[eprint](https://eprint.iacr.org/2025/1045).