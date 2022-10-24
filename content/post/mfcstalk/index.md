---
title: On minimality and positivity for second-order holonomic sequences
date: 2021-10-01
math: true
diagram: true
tags:
- decision problems
- decidability
- holonomic sequences
- Positivity Problem
- Minimality Problem


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 3
  focal_point: "Center"
  caption: 'Image credit: **WienTourismus / Christian Stemper**'
  preview_only: false
### WienTourismus / Christian Stemper
---

{{% staticref "files/202108MFCS.pdf" "newtab" %}}Slides{{% /staticref %}} on minimality and positivity for second-order holonomic sequences.  Variations given at Mathematical Foundations of Computer Science 2021 (MFCS, Tallinn),  the joint Forsyte (TU Wien) and Institute of Science & Technology Seminar, and the Open University Dynamical Systems Seminar.

### Abstract
An infinite sequence \$\langle u_n \rangle\$ of real numbers is holonomic if it  satisfies a linear recurrence relation with polynomial coefficients.  Such a sequence is positive if each $u_n \geq 0\$, and minimal if, given  any other linearly independent sequence $\langle v_n \rangle$ satisfying the same  recurrence relation, the ratio $u_n/v_n$ converges to $0$ as $n$ tends to  infinity.
In recent work, the speaker and collaborators establish a Turing reduction of the problem of deciding positivity of second-order  holonomic sequences to that of deciding minimality of such sequences.  More specifically, we give a procedure for determining positivity of  second-order holonomic sequences that terminates in all but an  exceptional number of cases, and we show that in these exceptional cases positivity can be determined using an oracle for deciding minimality.