# CDBMM Causal Simulation
This repository contains the simulation study developed for my master's thesis to evaluate the performance of the Confounder-Dependent Bayesian Mixture Model (CDBMM).

The study investigates whether CDBMM can accurately estimate heterogeneous treatment effects and recover latent subgroup structures under a range of controlled simulation scenarios.
## Simulation Workflow
1. Generate synthetic datasets.
2. Estimate treatment effects using CDBMM.
3. Compare performance with BART and CART.
4. Evaluate model performance using Bias, MSE, Relative Error Ratio, and ARI.
## Simulation Design
Synthetic datasets were generated to mimic observational studies with confounding and heterogeneous treatment effects.

The simulation includes:

- Five covariates (continuous and binary)
- Three latent subgroups
- Potential outcomes under treatment and control
- Correlated treatment assignment and exposure
- Eight simulation scenarios
