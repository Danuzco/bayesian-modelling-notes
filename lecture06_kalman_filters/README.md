# Lecture 6 · Kalman Filters

📄 **[Handwritten notes](lecture06_kalman_filters.pdf)** (18 pages)  
📝 **[Typeset version (LaTeX)](lecture06_kalman_filters_typeset.pdf)** (10 pages, [source](latex/lecture06_kalman_filters_typeset.tex))

## Outline

- Probabilistic state-space models and the Markov assumptions
- The Bayesian filtering equations: initialization, prediction, update
- The linear Gaussian model
- Prediction step: mean and covariance
- Update step by completing the square
- From the information form to the usual gain form with the Woodbury identity
- Summary of the Kalman filter, inference and forecasting

## Code

| Notebook | What it does |
|---|---|
| [`nile_kalman`](code/nile_kalman.ipynb) | Local-level model (A = 1, H = 1) for the annual flow of the river Nile: filtering the hidden level and its uncertainty. |

---

← [Lecture 5: Bayesian Statistics](../lecture05_bayesian_statistics) · [Course map](../README.md#course-map) · [Lecture 7: Gaussian Processes](../lecture07_gaussian_processes) →
