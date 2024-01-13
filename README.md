# ProxMCMC Examples

This repository contains code for reproducing results from [(Zhou et al., 2022)](https://arxiv.org/abs/2205.07378). 

To use it, follow these steps:
- Install Julia 1.8.2.
- Start Julia from where the project folder is located.
- Install required packages by typing
```
]
activate .
instantiate
add IJulia
```
- Start Jupyter notebook
```
using IJulia
notebook(dir = pwd())
```

## Citation

If you use the code from this repository, please cite the following paper:

Zhou, X., Heng, Q., Chi, E., and Zhou, H. (2022). Proximal MCMC for Bayesian Inference of Constrained and Regularized Estimation. arXiv:2205.07378 [stat.ME] 

