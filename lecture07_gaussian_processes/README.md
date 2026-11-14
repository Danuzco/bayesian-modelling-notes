# Lecture 7 · Gaussian Processes

📄 **[Handwritten notes](lecture07_gaussian_processes.pdf)** (17 pages)

## Outline

- Bayesian linear regression: posterior of the weights and posterior predictive
- From linear to nonlinear regression
- Gaussian processes: mean and kernel functions, prior, likelihood and posterior
- Prediction at a new input: conditioning, then integrating over the latent function
- Kernels: the linear kernel recovers Bayesian linear regression; the Gaussian kernel

## Code

| Notebook | What it does |
|---|---|
| [`gp_linear_and_nonlinear`](code/gp_linear_and_nonlinear.ipynb) | GP regression on two examples: with a linear kernel it reproduces Bayesian linear regression exactly; with a Gaussian kernel it fits a nonlinear function. |

---

← [Lecture 6: Kalman Filters](../lecture06_kalman_filters) · [Course map](../README.md#course-map) · [Lecture 8: Markov Chain Monte Carlo](../lecture08_mcmc) →
