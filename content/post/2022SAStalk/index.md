---
title: Solving Invariant Generation for Unsolvable Loops
date: 2023-05-23
math: true
diagram: true
tags:
- invariant generation
- unsolvable loops
- effective variables
- defective variables
- program analysis


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 3
  focal_point: "Center"
  preview_only: false
### heuriger
---

Marcel Moosbrugger presented our joint work ([see here]({{< relref "/publication/amrollahi-2022-invariant" >}}))
 on invariant generation for unsolvable loops at the ACM SIGPLAN 29th Static Analysis Symposium (SAS 2022).

### Abstract
Automatically generating invariants, key to computer-aided analysis of probabilistic and deterministic programs and compiler optimisation, is a challenging open problem. Whilst the problem is in general undecidable, the goal is settled for restricted classes of loops. For the class of solvable loops, introduced by Kapur and Rodríguez-Carbonell in 2004, one can automatically compute invariants from closed-form solutions of recurrence equations that model the loop behaviour. In this paper we establish a technique for invariant synthesis for loops that are not solvable, termed unsolvable loops. Our approach automatically partitions the program variables and identifies the so-called defective variables that characterise unsolvability. We further present a novel technique that automatically synthesises polynomials, in the defective variables, that admit closed-form solutions and thus lead to polynomial loop invariants. Our implementation and experiments demonstrate both the feasibility and applicability of our approach to both deterministic and probabilistic programs.

{{< youtube fZbGGx2ifho >}}
