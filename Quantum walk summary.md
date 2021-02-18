# Quantum Walk (QW)

Quantum walk is an quantum analog of classical random walks. It plays the part of building quantum algorithms.


## Problem definition

There are two types of quantum walk:
1. Continous time quantum walk (CTQW)
Given an quantum state $|\psi\rangle$ and an untitary operator $U$, rotate the quantum state $|\psi\rangle$ by the untitary operator $U$.





3. Discrete time quantum walk (DTQW)





## Application
### Continous time quantum walk

| ref | Problem   |  Quantum Complexity | Classical Complexity|
| --- | ---- |  ------ |------ |
| [1] | decision tree problem  |  $\sqrt{n}$ |$n$ |
| [2] |   Unstructured Search |  $\sqrt{n}$ |$n$ |



### Discrete time quantum walk



| ref | Problem   |  Quantum Complexity |Classical Complexity|
| --- | ---- |  ------ |------ |
| [3] | Triangle Finding query complexity  |  $n^{5/4}$ |$n^\omega$, $\omega<2.3729$|
| [2] | Unstructured Search |  $\sqrt{n}$ |$n$ |


    
    
## Reference:
[1] [A. M. Childs, R. Cleve, E. Deotto, E. Farhi, S. Gutmann, and D. A. Spielman, in Proceedings of the 35th ACM Symposium on Theory ofComputing (ACM, New York, 2003),p.59.](https://arxiv.org/abs/quant-ph/0209131)

[2] [Thomas G. Wong, Unstructured Search by Random and Quantum Walk.](https://arxiv.org/abs/2011.14533)

[3] [François Le Gall, Improved Quantum Algorithm for Triangle Finding via Combinatorial Arguments](https://arxiv.org/abs/1407.0085)
