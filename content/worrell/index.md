---
title: WORReLL'23
summary: Workshop On Reachability, Recurrences, and Loops
date: "2018-06-28T00:00:00Z"
show_date: false

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?


## Tagging your content helps users to discover similar content on your site. 
##    Tags can improve search relevancy and are displayed after the page content and also in the Tag Cloud widget.
tags: # (Core)
- Reachability
- Recurrences
- Loops
- Workshop


---

## Workshop On Reachability, Recurrences, and Loops
### Satellite Workshop at [ICALP 2023](https://icalp2023.cs.upb.de/)
#### Heinz Nixdorf MuseumsForum (HNF), Seminar Room 5
#### Paderborn, Germany 
#### Monday 10th July 2023
#### [Workshop Registration Link](https://icalp2023.cs.upb.de/registration/)

---



## Topic



Recursively defined sequences are foundational objects of study in the computational sciences; they arise naturally in areas such as: the analysis of algorithms, weighted automata, loop termination, and probabilistic models. 

---

## Aim




The aim of WORReLL'23 is to bring together researchers from the community and showcase cutting-edge research on the above topics.
The one-day workshop will also celebrate the research contributions of Professor James Worrell (also known as Ben). For context, Ben is giving an [invited talk](https://icalp2023.cs.upb.de/invited-speakers/) at ICALP this year.





Coincidentally, the workshop is a few days prior to Ben's birthday.
We plan to celebrate with a birthday dinner on Sunday 09th July (the evening before the workshop), so please take this into consideration for planning your travel to Paderborn.

{{< figure src="jbw.jpg" width="310" height="310" caption="Professor James Worrell" >}}

---

## Participation

To participate in-person, please register for WORReLL'23 through ICALP's [registration portal](https://icalp2023.cs.upb.de/registration/).  To participate remotely over Zoom, please contact the organisers for further details.



---

## Speakers and Talks

(Click on a talk title for the abstract.)


#### [Nikhil Balaji](https://sites.google.com/view/nikhilbalaji/home) (IIT Delhi)

{{< spoiler text="_On the Complexity of the Sum of Square Roots Problem_" >}}

Given positive integers $a_1, a_2, \dots, a_n$ and $b_1, b_2, \dots, b_m$, the Sum of Square Roots
problem (SSR) is the computational problem of checking if $\sqrt{a_1} + \sqrt{a_2} + \dots + \sqrt{a_n} >  \sqrt{b_1} + \sqrt{b_2} + \dots + \sqrt{b_m}$.
It is an essential primitive in Computational Geometry where efficient algorithms for several geometric problems are known relative to SSR. 
However the best-known complexity upper bound for SSR is in the Counting Hierarchy (CH), and no non-trivial lower bounds are known. Over the last two decades, SSR-hardness has emerged as a useful tool to capture the "numerical hardness" of problems, especially in Game Theory and Verification. In this talk, I will introduce a variant of SSR and show efficient "non-uniform" algorithms for this problem.

{{< /spoiler >}}
  
  
  
  
#### [Paul Bell](https://pcbell.github.io/) (Keele)

{{< spoiler text="_From Quantum Automata to Quaternions and Rational Pairing Functions_" >}}

We investigate some recent results on injectivity for Quantum Finite Automata. We call a QFA injective if the acceptance probability of every input word is unique. We show the undecidability of this problem by using tools and results from linear algebra, quaternions, number theory, and in particular rational polynomial pairing functions. We note a huge disparity in the number of required states to show undecidability depending on whether the initial state vector is rational or real algebraic. We will draw parallels with interesting questions for other matrix theoretic problems, and introduce some new research directions and open problems.

{{< /spoiler >}}



#### [Dmitry Chistikov](https://warwick.ac.uk/fac/sci/dcs/people/dmitry_chistikov/) (Warwick) 

_Globe Hopping_


#### [Valérie Berthé](https://www.irif.fr/~berthe/) (CNRS, Paris)

{{< spoiler text="_Recursive Sequences and Numeration_" >}}

In this lecture we revisit recursive sequences  from the view point  of numeration systems and their associated dynamical systems.
Linear recurrences allow indeed  the definition of  numerations for both integers and real numbers.
We focus on the so-called finiteness property  which  means that  the set  of elements having a finite  expansion   forms a ring, and on  its numerous applications in arithmetics, aperiodic order,  fractal geometry etc. 

{{< /spoiler >}}

#### [Florian Luca](https://www.wits.ac.za/staff/academic-a-z-listing/l/florianlucawitsacza/) (Witwatersrand) 


{{< spoiler text="_Twisted Rational Zeros of Linearly Recurrent Sequences_">}}

Let $( T_n )_{n} \\in \\mathbb{Z}$ be the Tribonacci numbers.
Marques and Lengyel (2014) obtained a formula relating the $2$-adic valuation of $T_n$ with the $2$-adic valuation of a linear function of $n$ (which might be constant) according to the residue class of $n$ modulo $32$ and optimistically conjectured that a similar formula holds true for every prime $p$. 
In the first part of the talk, we will see that their conjecture was indeed far too optimistic; in particular, it fails for all but seven primes below $600$. Along the way, we are led to consider a certain twisted rational zero of a linearly recurrent sequence. We prove that non-degenerate linearly recurrent sequences have only finitely many such twisted rational zeros, which may be seen as an extension of the Skolem--Mahler--Lech theorem. While our method is, in general, not effective, in some cases we can compute all such twisted rational zeros. In particular, returning to the Tribonacci sequence we show that its only twisted rational zeros are the integral ones $-17,-4,-1,0$ together with the rational non-integral ones $1/3$ and $-5/3$.


This is joint work with Y. Bilu, J. Nieuwveld, J. Ouaknine and J. Worrell.

{{< /spoiler >}}


#### [Joël Ouaknine](https://people.mpi-sws.org/~joel/) (MPI-SWS)

{{< spoiler text="_Universal Skolem Sets_">}}

The Skolem Problem asks to determine whether a given integer linear recurrence sequence (such as the Fibonacci numbers) has a zero term. This problem, whose decidability has been open for many decades, arises across a wide range of topics in computer science, including loop termination, probabilistic model checking, weighted automata theory, and dynamical systems, amongst many others. Recently, a new line of attack to the Skolem Problem was initiated via the notion of a Universal Skolem Set: a set S of positive integers such that it is decidable whether a given linear recurrence sequence has a zero in S. I will present an overview of this approach.

This is joint work with Florian Luca, James Maynard, Armand Noubissie, and James Worrell.

{{< /spoiler >}}

#### [Veronika Pillwein](https://risc.jku.at/m/veronika-pillwein/) (JKU) 

{{< spoiler text="_The Positivity Problem for Recurrent Sequences_">}}

Proving positivity of sequences that are defined by recurrences is very
hard. Even when restricted to the seemingly simple class of sequences
defined by linear recurrences with constant coefficients (C-finite
sequences), decidability of the positivity problem is only known for
orders up to five.

On the other hand, some computer algebra methods are able to tackle this
problem. Obviously, they do not succeed with all types of input and even
though correctness can be proven, termination is typically an issue. In
this talk, we will give an overview on this topic, present some
available methods and show cases where algorithmic proofs actually
succeeded.

{{< /spoiler >}}

#### [Igor Potapov](https://cgi.csc.liv.ac.uk/~igor/Igor_Potapovs_Home_Page/Home.html) (Liverpool) 

_tba_


#### [Mahsa Shirmohammadi](https://www.irif.fr/~mahsa/) (CNRS, Paris)


{{< spoiler text="_The Membership Problem for Hypergeometric Sequences_" >}}

This talk is on the Membership problem for rational-valued
hypergeometric sequences. Such sequences $\\langle u_n \\rangle_{n=0}^{\infty}$
satisfies a first-order linear recurrence relation with polynomial
coefficients; that is,  a recurrence of the form $f(n)u_n =
g(n)u_{n-1}$ where $f,g \in \mathbb{Z}[x]$.
The Membership Problem asks, given a hypergeometric sequence
$\\langle u_n \\rangle_{n=0}^{\infty}$ and a target value $t\in \mathbb{Q}$, determine whether
$t$ occurs in the sequence.
We give hints on recent decidability results of the Membership Problem
under the assumption that either (i) $f$ and $g$ have distinct
splitting fields, (ii) $f$ and $g$ split totally over
$\mathbb{Q}$, and (iii) $f$ and $g$ are monic polynomials that both
split over a quadratic extension of $\mathbb{Q}$.

This talk is based on two papers appearing in ISSAC'22 and ISSAC'23,
and are in collaboration with George Kenison, Amaury Pouly, Klara
Nosan, and  James Worrell.

{{< /spoiler >}}

---

## Schedule


09:00--09:45 Valérie Berthé <br>
09:45--10:30 Dmitry Chistikov 

_Coffee Break_

11:00--11:45 Mahsa Shirmohammadi <br>
11:45--12:30 Florian Luca

_Lunch_

14:05--14:25 Veronika Pillwein (Online) <br>
14:25--14:45 Nikhil Balaji  <br>
14:45--15:30 Paul Bell

_Coffee Break_

16:00--16:45 Igor Potapov <br>
16:45--17:30 Joël Ouaknine

_Workshop Ends. ICALP food and drinks event begins._

---

## Organisers



- [George Kenison](https://georgekenison.github.io/) (TU Wien)
- [Mahsa Shirmohammadi](https://www.irif.fr/~mahsa/) (CNRS, Paris)

---

## Acknowledgements


We gratefully acknowledge the financial support of both the CNRS and the ANR via the International Emerging Actions grant (IEA'22) and the VeSyAM grant (ANR-22-CE48-0005), respectively.



