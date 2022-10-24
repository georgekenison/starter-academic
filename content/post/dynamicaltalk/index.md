---
title: Dynamical Systems and Program Analysis
date: 2022-04-06
math: true
diagram: true
tags:
- decision problems
- decidability
- holonomic sequences
- Positivity Problem
- dynamical systems
- program analysis


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 3
  focal_point: "Center"
  preview_only: false
### Tower of the Winds
---

James (Ben) Worrell gave a keynote talk on algorithmic analysis of dynamical systems at the 48th ACM SIGPLAN Symposium on Principles of Programming Languages (POPL 2021).
During his talk, Ben presented some of our ongoing work on inequality decision problems for low-order holonomic sequences ([see here]({{< relref "/publication/kenison-2020-positivity" >}})).  The abstract and recording for the talk are given below. Here are Ben's [slides](https://popl21.sigplan.org/details/POPL-2021-research-papers/69/Dynamical-Systems-and-Program-Analysis).

### Abstract
This talk is about the algorithmic analysis of dynamical systems and its relevance to the foundations of program analysis. A dynamical system is a state-based system that is specified by a rule specifying how the state changes over time (e.g., a swinging pendulum or a cobweb model of supply and demand in economics). While the study of dynamical systems permeates the quantitative sciences, in this talk we focus on computational aspects and their relevance to basic verification problems, such as termination and invariant synthesis. We highlight in particular certain problems that can be traced back to the program-analysis literature, e.g., concerning the decidability of termination for linear constraint loops and the computability of polyhedral and polynomial invariants for various classes of transition systems. In the talk we give some of the mathematical context of these problems, discuss recent progress, and highlight unsolved cases. The characteristic feature of the problems we consider is that they turn out to be much more challenging than they might first appear to the innocent-minded and in some cases have connections to problems at the frontiers of modern mathematics.

{{< youtube 9kUlHlvfU94 >}}