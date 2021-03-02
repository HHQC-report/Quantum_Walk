# Quantum Walk (QW)

Quantum walk is an quantum analog of [classical random walks](#classicalrandomwalk). It plays the part of building quantum algorithms.


## Problem definition

There are two types of quantum walk:
1. Continous time quantum walk (CTQW)
Given an quantum state $|\psi\rangle$ and an untitary operator $U$, rotate the quantum state $|\psi\rangle$ by the untitary operator $U$.
2. Discrete time quantum walk (DTQW)





## Application
### Continous time quantum walk

| ref | Problem   |  Quantum Complexity | Classical Complexity|
| --- | ---- |  ------ |------ |
| [1] | decision tree problem  |  $O(n)$ |$O(2^{n/6})$ |
| [2] |   Unstructured Search |  $O(\sqrt{n})$ |$O(n)$ |



### Discrete time quantum walk



| ref | Problem   |  Quantum Complexity |Classical Complexity|
| --- | ---- |  ------ |------ |
| [3] | Triangle Finding query complexity  |  $O(n^{5/4})$ |$O(n^\omega)$, $\omega<2.3729$|
| [2] | Unstructured Search |  $O(\sqrt{n})$ |$O(n)$ |
| [4] | Element distinctness | $O(n^{2/3})$ |$\Omega(n)$ |


    
    
## Reference:
[1] [A. M. Childs, R. Cleve, E. Deotto, E. Farhi, S. Gutmann, and D. A. Spielman, Exponential algorithmic speedup by quantum walk](https://arxiv.org/abs/quant-ph/0209131)

[2] [Thomas G. Wong, Unstructured Search by Random and Quantum Walk.](https://arxiv.org/abs/2011.14533)

[3] [François Le Gall, Improved Quantum Algorithm for Triangle Finding via Combinatorial Arguments](https://arxiv.org/abs/1407.0085)

[4] [Andris Ambainis, Quantum walk algorithm for element distinctness](https://arxiv.org/abs/quant-ph/0311001)



#### <a id="classicalrandomwalk" />Def : Classical random walk

Let {$X_1,X_2,...$ } is a sequance of $\mathbb{R}^{n}$ and this sequance are independent and identically distributed random variables. A random walk started at $z\in\mathbb{R}^{n}$ is a sequence ($S_t$) with $t\geq0$ 

$$\begin{cases} S_t=z& \text{t=0}\\ S_t=S_{t-1}+X_t& \text{t>0} \end{cases}$$ 

The quantities $X_n$ are  referred to the steps of the random walk.

A random walk is a mathematical object, known as a stochastic or random process, that describes a path that consists of a succession of random steps on some mathematical space such as the integers.

