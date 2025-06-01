---
title: "Simple Linear Loops: Algebraic Invariants and Applications"
date: 2025-01-12
publishDate: 2025-01-12
authors: ["R. Ait El Manssour", "G. Kenison", "M. Shirmohammadi", "A. Varonka"]
publication_types: ["2"]
featured: false
publication: "*Proceedings of the ACM on Programming Languages, POPL'25*"

abstract: "
Automatic generation of loop invariants is a fundamental challenge in software verification. While this task is undecidable in general, it is decidable for certain restricted classes of programs. This work focuses on invariant generation for (branching-free) loops with a single linear update.

 Our primary contribution is a polynomial-space algorithm that computes the strongest algebraic invariant for simple linear loops, generating all polynomial equations that hold among program variables across all reachable states. The key to achieving our complexity bounds lies in mitigating the blowup associated with variable elimination and Gröbner basis computation, as seen in prior works. Our procedure runs in polynomial time when the  number of program variables is fixed. 

We examine various applications of our results on invariant generation, focusing on invariant verification and loop synthesis. The invariant verification problem investigates whether a polynomial ideal defining  an algebraic set  serves as an invariant for a given linear loop. We show that this problem is coNP-complete and lies in PSPACE when the input ideal is given in dense or sparse representations, respectively.
In the context of  loop synthesis, we aim to construct a loop with an infinite set of reachable states that upholds a specified algebraic property as an invariant. The strong synthesis variant of this problem requires the construction of loops for which the given property is the strongest invariant. In terms of hardness, synthesising loops over integers (or rationals) is as hard as Hilbert's Tenth problem (or its analogue over the rationals). When loop constants are constrained to bit-bounded rational numbers, we demonstrate that loop synthesis and its strong variant are both  decidable in PSPACE, and in NP when  the  number of program variables is fixed. 
"

doi: "10.1145/3704862"
tags : ["Algebraic Invariant", "Program Synthesis", "Loop Invariant", "Zariski Closure", "Polynomial Space", "Algebraic Reasoning"]
links:
links:
  - name: arXiv
    url: https://arxiv.org/abs/2407.09154
url_pdf: https://arxiv.org/pdf/2407.09154
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---



