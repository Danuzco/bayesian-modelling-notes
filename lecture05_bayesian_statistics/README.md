# Lecture 5 · Bayesian Statistics

📄 **[Handwritten notes](lecture05_bayesian_statistics.pdf)** (67 pages)

## Outline

- Bayes' rule for parameters: prior, likelihood, posterior
- Covariates and regression models
- Prior and posterior predictive distributions
- Bayesian modelling as a design problem
- Conjugate priors: Beta–Binomial; Gaussian–Gaussian with known variance; known mean (inverse-gamma); unknown mean and variance (Normal–Inv-χ²)
- The exponential family and its conjugate priors
- Multivariate normal model with known covariance, and its posterior predictive
- Linear Gaussian systems
- Mixtures of conjugate priors
- Model selection and the marginal likelihood

## Code

| Notebook | What it does |
|---|---|
| [`gaussian_2d_inference`](code/gaussian_2d_inference.ipynb) | Posterior of a 2D Gaussian mean with known Σ, as a special case of a linear Gaussian system (y = Wz + b + ε with W = I). Uses the Iris *setosa* measurements. |

---

← [Lecture 4: Classical Inference](../lecture04_classical_inference) · [Course map](../README.md#course-map) · [Lecture 6: Kalman Filters](../lecture06_kalman_filters) →
