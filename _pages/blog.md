---
layout: archive
Title: Some Legends of BQP Complexity Class
permalink: /blog/
author_profile: Manish Kumar
---

$\textbf{ Post-01:}$ $\textbf{BQP is growing young! Now it's BQP vs PH.}$

($\Psi$). "Oracle Separation of BQP and PH" by [Raz-Tal, 2018](https://dl.acm.org/doi/10.1145/3313276.3316315)

This paper is remarkable for two reasons:
> Under the "Oracle setting", there is a problem (named FORRELATION) that can be efficiently solved by Quantum Computer (BQP class). Still, this problem is shown to lie outside the entire classical Polynomial-time hierarchy (PH class)!!! Or, the problem is (probably) beyond the reach of classical computers, even if, in the future, someone proves or disproves P = NP.

> A breakthrough of such magnitude (in Quantum complexity theory) happened last time almost a decade ago. The progress in the field seemed to stagnate. But now, some quantum complexity theorists are calling the current research era the "post-Raz-Tal world".


---------------------------------

$\textbf{Post-02: Can you remove Quantumnesss from all Quantum algorithms?}$

($\Psi$). "Acrobatics of BQP" by [Aaronson-Ingram-Kretschmer, 2022](https://eccc.weizmann.ac.il/report/2021/164/)

Two awesome reasons to read the paper are as follows:

>There are some well-known heuristics to remove classical randomness powering classical complexity class BPP. However, it is poorly understood if some heuristics exist to remove "Quantumness" from the BQP class.

>The inability to remove quantumness from all quantum algorithms has astonishing (as well as whimsical) consequences. Perhaps the authors named the paper 'Acrobatics of BQP' for the same reason!


----------------------------------

$\textbf{Post-03: Quantum Algorithm Zoo: Here lie (classically) unseen monsters!}$

For a long time, I was searching for a website on Quantum Algorithm having the following features:
>
$\surd$ up-to-date content
> 
$\surd$ extensive collections of algorithms
> 
$\surd$ proper citations for the claims
>
I think our search ends with the below website maintained by Stephen Jordon (Google Quantum Research):
> $\Rightarrow$ [Quantum Algorithm Zoo](https://quantumalgorithmzoo.org/)

-------------------------------------

$\textbf{ Post-04:}$ $\textbf{An Algorithmic diaries: They worth being discussed}$

($\Psi.1$). Best and Worst way to solve an algorithm
> Problem-1: Multiplication of two integers:

> Problem-2: Minimum spanning tree:

> Problem-3: Discrete Fourier transform:

> Problem-4: Factoring Integers:

($\Psi.2$). "[Galactic Algorithms](https://en.wikipedia.org/wiki/Galactic_algorithm) and How to make them"
> As the story goes, an algorithm with complexity $\mathcal{O}(n^{100000000})$ for Travelling sales man problem(TSP) would be enough to prove $P=NP$. Although the same algorithm can't be used in practice to solve TSP. But it will make the life of theoretical computer scientists much easier(!)

> A good example of a galactic algorithm is the AKS-primality test; it decides if a number $n$ is prime or not with runtime complexity $\mathcal{O}(n^{7.5})$. It showed the problem $PRIME\ is\ in\ P$. But still, the most practical primality test used by our computers is Miller-Rabin, a randomised algorithm (BPP class).
