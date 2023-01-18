---
layout: default
nav_order: 3.5
parent: Course Content
title: Recommended Problems
---

## Recommended Problems

### Standard Form

Problems 16-19 of Section 12.1 work through the reduction algorithm to standard form in the slightly simpler, but practically useful
case of $R$ being a Euclidean Ring.

### Torsion and Rank

Remember that $\Tor(M)=\lbrace m\in M : \exists r\in R, rm=0\rbrace$ and that the rank of a module is the maximal size of a linearly independent set of elements of $M$. 

1. (DF Section 12.1 problem 1) Let $M$ be a module over an integral domain $R$.  Show that the rank of $M$ (the maximal number of linearly independent elements of $M$) is zero. 
Then show that the rank of $M$ is the same as the rank of $M/\Tor(M)$. 

### More on Torsion and Rank

2. (DF Section 12.1 problem 2) Let $M$ be a module over an integral domain $R$.  

    a. Let $x_1,\ldots, x_n$ be a maximal linearly independent set of elements of $M$.  Let $N$
    be the submodule of $M$ generated by the $x_{i}$.  Prove that $N$ is isomorphic to $R^{n}$ and that $M/N$ is a torsion $R$-module. 

    b.  Conversely, suppose $M$ contains a free $R$-module $N$ of rank $n$ such that $M/N$ is torsion.  Prove that $M$ has rank $n$. 

3. (DF Section 12.1 Problem 4) So that if $M$ has rank $n$, $N\subset M$ has rank $r$, and $M/N$ has rank $s$, then $n=r+s$.

### Primary Decomposition

4. (DF Section 12.1 problem 11) Let $R$ be a PID and let $a\in R$ be a nonzero element.  Let $M=R/aR$.  For any prime $p$ of $R$, prove that, if $n$ is the power of $p$ dividing $a$ in $R$, then

$$
p^{k-1}M/p^{k}M=\begin{cases} R/pR & k\le n \\ 0 & k>n\end{cases}
$$



### More on primary decomposition (uniqueness part of main theorem)

5. (DF Section 12.1 problem 12) Let $R$ be a PID and let $p$ be a prime in $R$.  This problem gives an approach to proving uniqueness of the decomposition into cyclic modules of the form $R/p^{a}R$.

    a. Let $M$ be a finitely generated torsion $R$-module. Prove that $p^{k-1}M/p^{k}M$ is isomorphic to $F^{n_{k}}$ where $F$ is the field $R/pR$ and $n_{k}$ is the number
    of elementary divisors of $M$ which are powers of $p^{\alpha}$ with $\alpha\ge k$.


    b. Suppose $M_1$ and $M_2$ are isomorphic finitely generated torsion $R$-modules. Use part (a) to prove that, for all $k\ge 0$, $M_1$ and $M_2$ have the same number of elementary
    divisors $p^{\alpha}$ with $\alpha\ge k$. Show that this implies that $M_1$ and $M_2$ have the same set of elementary divisors.   



