# Lecture 9 · Variational Inference

📄 **[Handwritten notes](lecture09_variational_inference.pdf)** (11 pages)

## Outline

- Variational inference as optimization over a family q_φ(θ)
- Reverse vs forward KL divergence
- The evidence lower bound (ELBO) via Jensen's inequality
- Mean-field variational inference
- ADVI with a mean-field Gaussian family
- Monte Carlo (score-function) gradients of the ELBO
- Gaussian-mixture variational families

## Code

| Notebook | What it does |
|---|---|
| [`variational_inference`](code/variational_inference.ipynb) | Fits a Gaussian-mixture variational family to a banana-shaped posterior by maximizing a Monte Carlo ELBO, with gradients from JAX. |

---

← [Lecture 8: Markov Chain Monte Carlo](../lecture08_mcmc) · [Course map](../README.md#course-map) · [Lecture 10: Hierarchical Models](../lecture10_hierarchical_models) →
