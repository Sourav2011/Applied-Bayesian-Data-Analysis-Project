📘 Bayesian Analysis: Impact of International Shipping on Product Ratings
This project investigates whether international shipping influences customer product ratings using Bayesian ordinal regression.
The analysis uses cumulative logit models, hierarchical structures, prior sensitivity checks, and LOO model comparison.

🎯 Objectives
- Determine whether international shipping affects product ratings
- Fit Bayesian ordinal regression models
- Compare models using LOO cross‑validation
- Evaluate convergence using MCMC diagnostics
- Perform prior sensitivity analysis
- Explore hierarchical variation across product categories and product IDs

🧠 Statistical Methods
- Bayesian ordinal regression (cumulative logit)
- Weakly informative priors (Normal(0,5), Student‑t)
- Hierarchical random‑effects modeling
- Posterior predictive checks
- Convergence diagnostics:
- Trace plots
- Density plots
- Rhat
- Effective Sample Size (ESS)
- Leave‑One‑Out (LOO) model comparison
- Prior sensitivity analysis

📈 Key Findings
- International shipping shows no strong effect on product ratings
- Product category differences are small but present
- Hierarchical model captures product‑level variation
- All models show good convergence (Rhat ≈ 1.00)
- LOO comparison suggests the hierarchical model performs best
- Prior sensitivity analysis confirms model robustnes
  
🛠 Tools Used
- R (4.4.3)
- brms
- rstan
- loo
- ggplot2
- dplyr

👤 Authors
Sourav Poddar
TU Dortmund University
