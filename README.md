# ProxMCMC Examples

This repository contains code for reproducing results from [(Zhou et al., 2024)](https://doi.org/10.1080/00031305.2024.2308821). 

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

Zhou, X., Heng, Q., Chi, E. C., & Zhou, H. (2024). Proximal MCMC for Bayesian Inference of Constrained and Regularized Estimation. The American Statistician, 1–12. https://doi.org/10.1080/00031305.2024.2308821
