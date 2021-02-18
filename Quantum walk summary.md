# Quantum Walk (QW)

Quantum walk is an quantum analog of classical random walks. It plays the part of building quantum algorithms.


## Problem definition

There are two types of quantum walk:
1. Continous time quantum walk (CTQW)
Given an quantum state $|\psi\rangle$ and an untitary operator $U$, rotate the quantum state $|\psi\rangle$ by the untitary operator $U$.





3. Discrete time quantum walk (DTQW)





## Application
### Continous time quantum walk

| ref | algorithm   |  Quantum Complexity | Classical Complexity|
| --- | ---- |  ------ |
| [1] | Exponential algorithmic speedup by a quantum walk  |  $\sqrt{n}$ |$n$ |
| [2] |   Unstructured Search |  $\sqrt{n}$ |$n$ |



### Discrete time quantum walk



| ref | algorithm   |  Quantum Complexity |Classical Complexity|
| --- | ---- |  ------ |
| [1] | Triangle Finding    |  $\sqrt{n}$ |$n$ |
| [2] | Unstructured Search |  $\sqrt{n}$ |$n$ |


## <a id="improvement" />Main improvement
Use the Gibbs sampling.
    
    
## Reference:
[1] [Fernando G.S.L. Brandao, Krysta Svore, Quantum Speed-ups for Semidefinite Programming](https://arxiv.org/abs/1609.05537)


## <a name="details" />Appendix
$$ \Vert\vec{x}\Vert_1=\sum_{i=1}^N\vert{x_i}\vert $$

$\bar{X} = \frac{\sum_{i=1}^n X_i}{n}$

$$ evidence_{i}=\sum_{j}W_{ij}x\_{j}+b\_{i} $$

$$
\operatorname{ker} f=\{g\in G:f(g)=e_{H}\}{\mbox{.}}
$$

Test a display math with equation number:
$$
  \begin{align}
    |\psi_1\rangle &= a|0\rangle + b|1\rangle \\\\
    |\psi_2\rangle &= c|0\rangle + d|1\rangle       
  \end{align}
$$
