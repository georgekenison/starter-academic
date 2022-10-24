---
title: Markov Reachability for biased cycles
date: 2020-05-01
math: true
diagram: true
tags:
- decision problems
- decidability
- Markov Reachability Problem


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 3
  caption: 'Image credit: **Nicola Mastroddi**'
  focal_point: "Left"
  preview_only: false
### Doors leading off the quad of the Bodleian Library
(Image Credit: Nicola Mastroddi)
---

### The Markov Reachability Problem
We are interested in decision problems for Markov chains and in particular, the _Markov Reachability Problem_. Given a stochastic matrix $K\in\mathbb{Q}^{d\times d}$ and positive $r\in\mathbb{Q}$, determine whether there exist an $n\in\mathbb{N}$ such that $K^n(1,2)=r$.
That is to say, does there exist an $n\in\mathbb{N}$ such that the probability of travelling from state $1$ to state $2$ is exactly $r$.
The decidability of the Markov Reachability Problem is currently open.

We note the Markov Reachability Problem  is  more difficult than the process of determining whether there is a path of length $n$ originating at state $1$ and terminating at state $2$ with associated probability $r$.

### Cycle graphs

We shall consider the Markov Reachability Problem for a toy example.
Let us define the entries of an $m\times m$ stochastic matrix $K$ with rows and columns indexed by the states $\{1,2,\ldots, m\}$ as follows

\begin{equation*}
       K(i,j) = \begin{cases}
            p & \text{if } j=i+1 \pmod{m},\\\\
            1-p & \text{if } j=i-1 \pmod{m},\\\\
            0 & \text{otherwise}.
        \end{cases}
\end{equation*}

The Markov chain associated to $K$ is a directed graph with states $\{1,2,\ldots, m\}$ so that at each timestep the transitions  $\ell\mapsto\ell+1\pmod{m}$ and $\ell\mapsto\ell-1\pmod{m}$ occur  with probabilities $p$ and $1-p$, respectively.

We call the Markov chain associated to $K$ an _$m$-cycle_ and, in addition, if $p\neq 1/2$ we call the Markov chain a _biased $m$-cycle_.  Without loss of generality, we shall assume throughout that $p\in(0,1/2)$. 


### The biased $4$-cycle

Consider the decidability of the Markov Reachability Problem for the biased $4$-cycle.  It is clear that the only value of $r\in\mathbb{Q}$ that is not covered by stochastic asymptotic considerations is $r={1}/{2}$. 
We prove the following.

> __Proposition:__
> Let $K$ be the stochastic transition matrix 
>   \begin{equation*}
>    K := \begin{pmatrix}
>    0 & p & 0 & 1-p\\\\ 1-p & 0 & p & 0\\\\ 0 & 1-p & 0 & p\\\\ p & 0 & 1-p & 0
>    \end{pmatrix}
>\end{equation*}
>for the biased $4$-cycle with $p\in(0,1/2)$. There is no $m\in\mathbb{N}$ for which $K^m(1,2) = 1/2$.
>


> __Proof.__ Observe that a path originating at state $1$ and terminating at state $2$ on the $4$-cycle graph has odd length.
We can categorise such paths by the number of state transitions $\ell\mapsto\ell+1\pmod{4}$ and $\ell\mapsto\ell-1\pmod{4}$ made.
>
>Given that $K^{2m}(1,2)=0$ for each $m\in\mathbb{N}$. We need only consider two cases: paths with length $4m+1$ and those with length $4m+3$.  We can write the entries $K^{4m+1}(1,2)$ and $K^{4m+3}(1,2)$ in terms of sums of odd binomial coefficients such that
>    \begin{align*}
        K^{4m+1}(1,2) &= \sum_{j=0}^{2m} \binom{4m+1}{2j+1} p^{2j+1}(1-p)^{4m-2j}, \text{ and }\\\\  
        K^{4m+3}(1,2) &= \sum_{j=0}^{2m} \binom{4m+3}{2j+2} p^{2j+2}(1-p)^{4m-2j+1}.
    \end{align*}
>
>Using standard techniques for binomial expansions we can express $K^{4n+1}(1,2)$ as follows
>    \begin{align*}
        1- (1-2p)^{4m+1} &= (p + (1-p))^{4m+1} -(-p+(1-p))^{4m+1} \\\\
        &= \sum_{j=0}^{4m+1} \binom{4m+1}{j} p^j (1-p)^{4m+1-j} (1-(-1)^j) \\\\
        &= 2\sum_{j=0}^{2m} \binom{4m+1}{2j+1} p^{2j+1} (1-p)^{4m-2j} \\\\
        &= 2K^{4m+1}(1,2).
>    \end{align*}
>
>Suppose, for a contradiction, that there is an $m\equiv 1 \pmod{4}$ for which $K^m(1,2)={1}/{2}$.  Then  $0 = K^m(1,2) - {1}/{2} = -(2p-1)^{m}/2$, but this contradicts our assumption that $p\in(0,1/{2})$.  The fact that there is no $m\equiv 3 \pmod{4}$ for which $K^m(1,2) = 1/{2}$ follows by a similar argument.  Thus we determine there is no $m\in\mathbb{N}$ for which $K^m(1,2)=1/{2}$ as required.
>

The decidability of the Markov Reachability Problem for the fair $4$-cycle is trivial.  In fact, the problem is decidable for the general $m$-cycle.
It can be shown that the Markov Reachability Problem is decidable for biased cycles with $m$ states, but that is a post for another time.