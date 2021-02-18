# Quantum Walk (QW)

Quantum walk is an quantum analog of classical random walks. It plays the part of building quantum algorithms.


## Problem definition

There are two types of quantum walk:
1. Continous time quantum walk (CTQW)
Given an quantum state $|\psi\rangle$ and an untitary operator $U$, rotate the quantum state $|\psi\rangle$ by the untitary operator $U$.





3. Discrete time quantum walk (DTQW)





## Application
### Continous time quantum walk

#### Exponential algorithmic speedup by a quantum walk


### Discrete time quantum walk

#### Triangle Finding
#### Unstructured Search




For probelme definition, please see Equation \eqref{eq1}.
* complexity for the Arora-Kale framework

| ref | algorithm   |  complexity |
| --- | ---- |  ------ |
| [1] | classical  |  $\tilde{O}(nms(\frac{Rr}{\varepsilon})^4 + ns(\frac{Rr}{\varepsilon})^7)$ |
| [1] | QM   |  $\tilde{O}(\sqrt{mn}s^2 R^{32}/\delta^{18})$       |

The improvment for the QM approach to the Arora-Kale framework is the [Gibbs sampling](#improvement).
The details are listed in the [Appendix](#details)


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
