## [Louis Zhu]([url](https://looloo-dot.github.io/))

Frontier model evaluations, and what AI does to work. Oxford Internet Institute,
University of Oxford.

Hi I'm [Louis](https://looloo-dot.github.io/)! I work on measurement problems, asking whether the benchmarks we use to rank AI systems actually
measure what we claim, and how automation propagates through labour markets. Mostly applied
econometrics and agent-based simulation, in Python and R.

### Selected work

| Project | What it asks | Approach |
|---|---|---|
| **[One Capability or Many?](https://github.com/Looloo-dot/frontier-ai-economic-validity)** | Do frontier AI benchmarks measure one capability or several — and does collapsing them cost you anything on economically relevant tasks? | Factor analysis and parallel analysis over 421 model configurations; leave-one-benchmark-out prediction with nested CV. Finds a dominant factor that is substantially explained by *release date*, yet a 3-factor representation still predicts economic benchmarks better than a single index. |
| **[Automation Workforce Simulation](https://github.com/Looloo-dot/abm-labor-market-automation)** | How do employment, wages, and skill composition co-evolve under an automation shock? | Agent-based model in R: 2,000 heterogeneous workers, configurable shock and retraining dynamics. Fully seeded and reproducible. |
| **[AI Risk and UK Wages](https://github.com/Looloo-dot/ai-risk-uk-wage-panel)** | Did occupations more exposed to automation see their pay diverge after 2016? | UK occupation-year panel, 2014 to 2023, 367 occupations. Occupation and year fixed effects, clustered by occupation. The risk-by-post-2016 interaction comes out positive and precise, which is the opposite of the naive prior and wants explaining. |
| **[Double Machine Learning](https://github.com/Looloo-dot/double-ml-causal-inference)** | Can ML nuisance estimators be used for causal inference without inheriting regularisation bias? | DML-PLIV with cross-fitting and the R-learner on simulated data with known ground truth, plus a policy-targeting evaluation. |
| **[ABM-ACE](https://github.com/Looloo-dot/abm-ace)** | How do adaptive agents, climate shocks, and inequality interact under different policy regimes? | An agent-based research sandbox with a fully parameterised CLI, so every run is reproducible and auditable. |
| **[Term Life Insurance Demand](https://github.com/Looloo-dot/term-life-insurance-demand)** | Which household characteristics predict life-insurance coverage, and does regularisation beat transparent OLS? | Two-margin design on 2004 SCF data; Ridge and Lasso against an interpretable benchmark over 30 repeated splits. |
| **[Marshall Investment Fund](https://github.com/Looloo-dot/MIF-Site)** | — | Site for a student-managed long-only equity fund, [live on GitHub Pages](https://looloo-dot.github.io/MIF-Site/). Static HTML/CSS/JS, no build step. |

### Currently

Working on frontier model evaluation at the Oxford Internet Institute, with a focus on
whether capability measurements hold up as economic indicators.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/yiven-z)
