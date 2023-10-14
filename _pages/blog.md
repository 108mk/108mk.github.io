---
layout: archive
Title: Some Legends of BQP Complexity Class
permalink: /blog/
author_profile: Manish Kumar
---

$\textbf{ Post-01:}$ $\large{Some\ news\ from\ the\ battleground\ on\ FORRELATION:\ Score\ is\ 1-0\ for\ BQP\ vs\ PH}$

($\Psi$). "Oracle Separation of BQP and PH" by [Raz-Tal, 2018](https://dl.acm.org/doi/10.1145/3313276.3316315)

This paper is remarkable for two reasons:
>> Under the "Oracle setting", there is a problem (named FORRELATION) that can be efficiently solved by Quantum Computer (BQP class). Still, this problem is shown to lie outside the classical Polynomial-time hierarchy (PH class)!!!
>
>> This gives some intuition that there could be some problem that might be beyond the reach of classical computers, even if, in the future, someone proves or disproves P = NP.

>> It was a conjecture that [FORRELATION](https://arxiv.org/abs/0910.4698) is not in PH (in relativised world). This paper proved that this conjecture is indeed true. This is a non-trivial proof.
>
>> It requires proving the circuit lower bound for $AC^{0}$, (bounded depth circuit) in this context. The capability/limitation of a random walk to construct a pseudorandom generator has been partially used to build up the proof argument.

> 


---------------------------------

$\textbf{Post-02:}$ $\large{Can\ you\ remove\ Quantumnesss\ from\ all\ Quantum\ algorithms?}$

($\Psi$). "Acrobatics of BQP" by [Aaronson-Ingram-Kretschmer, 2022](https://eccc.weizmann.ac.il/report/2021/164/)

Two awesome reasons to read the paper are as follows:

>There are some well-known heuristics to remove classical randomness powering classical complexity class BPP. However, it is poorly understood if some heuristics exist to remove "Quantumness" from the BQP class.

>The inability to remove quantumness from all quantum algorithms has astonishing (as well as whimsical) consequences. Perhaps the authors named the paper 'Acrobatics of BQP' for the same reason!


----------------------------------

$\textbf{Post-03:}$ $\large{Quantum\ Algorithm\ Zoo:\ Here\ lie\ (classically)\ unseen\ monsters!}$

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

$\textbf{ Post-04:}$ $\textbf{Algorithmic Paradigms: Classical and Quantum}$

($\Psi.1$). $\large{Classical\ Paradigms}$

$\bullet$ A simple Wikipedia search will give you a list of such methods as:

⭐ Local search (iterative methods) 
⭐ Brute-force search
⭐ Divide and Conquer
⭐ Greedy approach
⭐ Dynamic Programming

$\bullet$ But one can nicely fit all of them into three major categories: 
> Local Search (LS): This is the inspiration for most of the gradient-based learning schemes and, in fact (almost) all computational optimization schemes like Newton's methods, BFGS, etc.

> Dynamic Programming (DP): DP gives a general foundation to 'greedy' and 'divide & conquer'. Perhaps this is what brings a unique sense of creativity to this field.

> Brute-force search: There is a popular joke in the algorithm community. There is an algorithm that guarantees to solve NP-complete problems and even harder problems than that. Its name is the Brute-force algorithm, but the only caveat is that it solves it in superpolynomial time(!)

 ($\Psi.1$). $\large{Quantum\ Paradigms}$

🎯 The three most important paradigms are: 
> (I) Amplitude Amplification-based algorithms: This uses the wave-ness of the quantum system to make (relatively) faster algorithms for certain special tasks like search and so on. [Grover Search Algorithms](https://learn.qiskit.org/course/ch-algorithms/grovers-algorithm) is a direct consequence of this.

> (II) Quantum Fourier transform-based algorithms: This is the foundation for several oracle-based algorithms like-

⭐Deutsch–Jozsa algorithm ⭐ Bernstein–Vazirani algorithm ⭐ Simon's algorithm ⭐ Quantum phase estimation ⭐ Fourier fishing and Fourier checking.

🎯 Some non-oracle-based algorithms giving superpolynomial speedups are-

🥳 Shor Integer Factoring algorithms algorithm and, 😄 HHL algorithm for a (sparse) system of Linear equation 

Note-1: Quantum Fourier transform(QFT) is extremely efficient compared to classical Fast Fourier transform (FFT). Asymptotic runtimes are as follows:

⭐ QFT (By Don Coppersmith): $\mathcal{O}(log(n)^2))$

⭐ FFT (By Cooley & Tuckey): $\mathcal{O}(n \cdot log(n))$


> (III) Quantum walk-based algorithms: Quantum walk can be used as a universal model of quantum computation. WELDED TREE PROBLEM is a highly studied case to explore an exponential separation between BQP and BPP/P.

-------------------------------------

$\textbf{ Post-04:}$ $\textbf{An Algorithmic diaries: Let's get puzzled by puzzles(!)}$

($\Psi.1$). Best and Worst way to solve an algorithm [Will be updated soon...]
> Problem-1: Multiplication of two integers:

> Problem-2: Minimum spanning tree in a graph:

> Problem-3: Shortest path in a weighted graph:

> Problem-4: Discrete Fourier transform:

> Problem-5: Factoring Integers:

> Problem-6: Maximum Flow Problem:

($\Psi.2$). "[Galactic Algorithms](https://en.wikipedia.org/wiki/Galactic_algorithm) and How to make them"
> As the story goes, an algorithm with complexity $\mathcal{O}(n^{100000000})$ for Travelling sales man problem(TSP) would be enough to prove $P=NP$. Although the same algorithm can't be used in practice to solve TSP. But it will make the life of theoretical computer scientists much easier(!)

> A good example of a galactic algorithm is the AKS-primality test; it decides if a number $n$ is prime or not with runtime complexity $\mathcal{O}(n^{7.5})$. It showed the problem $PRIME\ is\ in\ P$. But still, the most practical primality test used by our computers is Miller-Rabin, a randomised algorithm (BPP class).

------------------------------------
$\textbf{ Post-05:}$ $\textbf{Noam Chomsky: What does it mean to be truly educated?}$ [Link to video](https://youtu.be/eYHQcXVp4F4?si=rlu6LDVafcTyuqsU)
> My name is Noam Chomsky. I'm a retired professor at the Massachusetts Institute of Technology, where I've been for 65 years.

> I think, very plausibly, that the core principle and requirement of a fulfilled human being is the ability to inquire and create constructively independently without external controls.

> A leading physicist at MIT once told us in classes that it's not important what we cover in the class. It's important what you discover.

> To be truly educated from this point of view means to be in a position to inquire and create on the basis of the resources available to you, which you've come to appreciate and comprehend. To know where to look, to know how to formulate serious questions. Also, to question standard doctrine, to doubt if it is appropriate. It also includes finding your own way to shape the questions that are worth pursuing and developing the path to pursue them.

> This requires knowing and understanding many things. But it is also much more important than what you have stored in your mind to know where to look, what to look and how to question, and how to proceed independently to deal with the challenges that the world presents to you and that you develop in the course of your self-education and inquiry and the investigations in cooperation and solidarity with others.

> That's what an educational system should cultivate, from kindergarten to the high Graduate School, and in the best cases, sometimes does. And that leads to people who are, at least by my standards, well-educated.
