---
title: "(Un)Solvable Loop Analysis"
date: 2023-06-06
publishDate:
authors: ["D. Amrollahi", "E. Bartocci", "G. Kenison", "L. Kovács", "M. Moosbrugger", "M. Stankovič"]
publication_types: ["3"]
featured: false
publication: ""

abstract: "Automatically generating invariants, key to computer-aided analysis of probabilistic and deterministic programs and compiler optimisation, is a challenging open problem. Whilst the problem is in general undecidable, the goal is settled for restricted classes of loops. For the class of solvable loops, introduced by Kapur and Rodríguez-Carbonell in 2004, one can automatically compute invariants from closed-form solutions of recurrence equations that model the loop behaviour. In this paper we establish a technique for invariant synthesis for loops that are not solvable, termed unsolvable loops. Our approach automatically partitions the program variables and identifies the so-called defective variables that characterise unsolvability. Herein we consider the following two applications. First, we present a novel technique that automatically synthesises polynomials from defective monomials, that admit closed-form solutions and thus lead to polynomial loop invariants. Second, given an unsolvable loop, we synthesise solvable loops with the following property: the invariant polynomials of the solvable loops are all invariants of the given unsolvable loop. Our implementation and experiments demonstrate both the feasibility and applicability of our approach to both deterministic and probabilistic programs.
"

doi: ""
tags : ["Invariant Generation", "Unsolvable Loops", "Loop Synthesis", "Probabilistic Programs"]
links:
  - name: arXiv
    url: https://arxiv.org/abs/2306.01597
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---


Extended version of the conference paper _Solving Invariant Generation for Unsolvable Loops_ published at SAS 2022 ([see here]({{< relref "/publication/amrollahi-2022-invariant" >}})).

