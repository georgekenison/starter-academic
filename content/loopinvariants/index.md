---
title: Loop Invariants and Algebraic Reasoning
summary: Workshop On Loop Invariants and Algebraic Reasoning
date: "2025-01-01"
show_date: false

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?


## Tagging your content helps users to discover similar content on your site. 
##    Tags can improve search relevancy and are displayed after the page content and also in the Tag Cloud widget.
tags: # (Core)
- Loops
- Loop Invariants
- Invariant Generation
- Invariant Verification
- Algebraic Methods
- Workshop


---

## Workshop On Loop Invariants and Algebraic Reasoning
### Satellite Workshop at [ICALP 2025](https://conferences.au.dk/icalp2025)
#### The Mathematics Canteen (Department of Mathematics, Aarhus Universitetsparken), at [Ny Munkegade 116, 8000 Aarhus C   <i class="fa-solid fa-map-location-dot"></i>](https://maps.app.goo.gl/qnPCqeHnFTTSovsF8)
#### Aarhus, Denmark 
#### Monday 07th July 2025
#### [Workshop Registration Link](https://conferences.au.dk/icalp2025/registration)

---

## Aim




Reasoning about loops is a fundamental task in program analysis and verification.  To this end, loop invariants are an indispensable tool.  They help both to establish safety properties (e.g., proofs of non-reachability) and liveness properties (e.g., as supporting invariants in termination proofs). Beyer et al. [[VMCAI 2007]](https://link.springer.com/chapter/10.1007/978-3-540-69738-1_27) go so far as to call the problem of automatic invariant generation ''the most important task in program verification. ''

 

There has been a resurgence of interest in computing the polynomial invariants for loops. In one direction, theoretical work has produced complete algorithms that will generate the invariant ideal for abstract classes of loops. In another direction, recent works have produced templates and heuristics aimed at generating some (but not necessarily all) the invariants of more general classes of loops with conditional branching, polynomial assignments, and probabilistic updates.

 

This workshop aims to span the divide between the aforementioned directions and bring together researchers from both communities.


---

## Participation

To participate in-person, please register for the workshop through ICALP's [registration portal](https://conferences.au.dk/icalp2025/registration).  To participate remotely over Zoom, please contact the organisers for further details.



---

## Speakers, Talks, and Slides

(Click on a talk title for the abstract.)

<!---{{< spoiler text="_On the Complexity of the Sum of Square Roots Problem_" >}}

Abstract: Given positive integers $a_1, a_2, \dots, a_n$ and $b_1, b_2, \dots, b_m$, the Sum of Square Roots
problem (SSR) is the computational problem of checking if $$\sqrt{a_1} + \sqrt{a_2} + \dots + \sqrt{a_n} >  \sqrt{b_1} + \sqrt{b_2} + \dots + \sqrt{b_m}.$$
It is an essential primitive in Computational Geometry where efficient algorithms for several geometric problems are known relative to SSR. 
However the best-known complexity upper bound for SSR is in the Counting Hierarchy (CH), and no non-trivial lower bounds are known. Over the last two decades, SSR-hardness has emerged as a useful tool to capture the "numerical hardness" of problems, especially in Game Theory and Verification. In this talk, I will introduce a variant of SSR and show efficient "non-uniform" algorithms for this problem.

{{% staticref "/uploads/Balaji_slides.pdf" %}} Slides: &#128462; {{% /staticref %}}


{{< /spoiler >}}
--->


* [Ride Ait El Manssour](https://ridaaitelmanssour.com/) (Oxford)
    {{< spoiler text="TBC" >}}

  {{< /spoiler >}}

  
* [Ruiwen Dong](https://sites.google.com/view/ruiwen-dong/home) (Magdalen College, Oxford) {{< spoiler text="**S-unit equations in modules**" >}}

  Abstract: Let $M$ be a finitely presented module over a Laurent polynomial ring $R$. We consider S-unit equations over $M$: these are equations of the form $x_1 m_1 + \cdots + x_K m_K = m_0$, where the coefficients $m_i$ are in $M$ and the variables $x_i$ range over the set of monomials of $R$. When the Laurent polynomial ring $R$ has the base ring $\mathbb{Z}$, (that is, $R = \mathbb{Z}[X_1^{\pm}, \ldots, X_N^{\pm}]$), we show that it is undecidable whether a given S-unit equation over a given module $M$ admits a solution. When $R$ has the base ring $\mathbb{Z}/T\mathbb{Z}$ for some integer $T > 1$, (that is, $R = (\mathbb{Z}/T\mathbb{Z})[X_1^{\pm}, \ldots, X_N^{\pm}]$), we show that the problem of deciding whether a given S-unit equation over a given module $M$ admits a solution is Turing equivalent to solving a system of linear-exponential Diophantine equations over $\mathbb{Z}$. <br> This talk is based on a paper in SODA'25 as well as ongoing work with Doron Shafrir.

  {{< /spoiler >}}


* Roland Guttenberg (TUM)

  <details>
  <summary>TBC</summary>
  </details>


* [Toghrul Karimov](https://toghrul-karimov.github.io/) (MPI-SWS)

  <details>
  <summary>TBC</summary>
  </details>


* [Nathan Lhote](https://pageperso.lis-lab.fr/~nathan.lhote/) (Aix-Marseille University) 

  <details>
  <summary>TBC</summary>
  </details>


* [Fatemeh Mohammadi](https://www.fatemehmohammadi.com/) (KU Leuven)

  <details>
  <summary><strong>Algebraic tools for computing polynomial loop invariants</strong></summary>
    Loop invariants are properties of a loop program that hold before and after each iteration of the loop. They are often employed to verify programs and ensure that algorithms consistently produce correct results during execution. Consequently, the generation of invariants becomes a crucial task for loops. I specifically focus on polynomial loops, where both the loop conditions and assignments within the loop are expressed as polynomials. Although computing polynomial invariants for general loops is undecidable, efficient algorithms have been developed for certain classes of loops. For instance, when all assignments within a while loop involve linear polynomials, the loop becomes solvable. In this talk, I will discuss the more general case where the polynomials exhibit arbitrary degrees. Applying tools from algebraic geometry, I present two algorithms designed to generate all polynomial invariants for a while loop, up to a specified degree. These algorithms differ based on whether the initial values of the loop variables are given or treated as parameters. <br> This talk is based on joint work with Erdenebayar Bayarmagnai and Rémi Prébet.
  </details>

* Mahsa Naraghi (Université Paris Cité)

  <details>
  <summary>TBC</summary>
  </details>

* [Mohab Safey El Din](https://www-polsys.lip6.fr/~safey/) (Sorbonne Université, CNRS, LIP6) 

  <details>
  <summary>TBC</summary>
  </details>

* [Sylvain Schmitz](https://www.irif.fr/en/users/schmitz/index) (Université Paris Cité) 

  <details>
  <summary>TBC</summary>
  </details>

* [Anton Varonka](https://informatics.tuwien.ac.at/people/anton-varonka) (TU Wien)

  <details>
  <summary>TBC</summary>
  </details>

---

## Schedule

(All times are CEST/UTC+02:00)

_08:30--09:00 Registration_


09:00--10:30 Talks 

_Coffee Break_

11:00--12:30 Talks

_Lunch_

14:00--15:30 Talks

_Coffee Break_

16:00--17:30 Talks

_Workshop Ends_

---

## Organisers



- [George Kenison](https://georgekenison.github.io/) (LJMU)
- [Mahsa Shirmohammadi](https://www.irif.fr/~mahsa/) (CNRS, Paris)





