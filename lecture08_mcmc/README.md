# Lecture 8 · Markov Chain Monte Carlo

📄 **[Handwritten notes](lecture08_mcmc.pdf)** (20 pages)

## Outline

- Why sample: posterior predictive integrals by Monte Carlo
- Inverse-CDF sampling (exponential) and Gaussian sampling via Cholesky
- Metropolis–Hastings: the algorithm and its formal derivation from detailed balance
- Hamiltonian Monte Carlo: momentum, kinetic and potential energy, Hamilton's equations
- The leapfrog integrator and the Metropolis acceptance step
- Convergence diagnostics: the Gelman–Rubin statistic R̂

## Code

| Notebook | What it does |
|---|---|
| [`metropolis_hastings`](code/metropolis_hastings.ipynb) | Inverse-CDF sampling of an exponential, bivariate normal sampling via Cholesky, then a Metropolis–Hastings sampler on a banana-shaped target. |
| [`hmc`](code/hmc.ipynb) | Hamiltonian Monte Carlo written from scratch, with gradients from JAX and a leapfrog integrator. |
| [`intro_pymc`](code/intro_pymc.ipynb) | A first PyMC model: NUTS samples for a Gaussian mean, checked against the closed-form posterior from Lecture 5. |

---

← [Lecture 7: Gaussian Processes](../lecture07_gaussian_processes) · [Course map](../README.md#course-map) · [Lecture 9: Variational Inference](../lecture09_variational_inference) →
