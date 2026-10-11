# Stochastic & Deterministic SIR Epidemic Modelling

University of Warwick MA124 Maths by Computer group project

## Project Overview
Numerically solved the deterministic SIR system of ODEs in Python and extended the analysis to stochastic epidemic simulation. Focused on baseline parameter analysis, transmission-rate sensitivity and real-world model extensions.

## Tech Stack
- Python, NumPy, Matplotlib
- SciPy `odeint` for ODE numerical solving
- Gillespie-style stochastic event simulation

## Key Results
- Solved deterministic SIR ODEs and identified a peak infection count of 1,535 under the baseline specification (N=10⁴, β=2×10⁻⁵, μ=0.1)
- Ran a 50-value transmission-rate sensitivity analysis (β from 5×10⁻⁶ to 5×10⁻⁵), plotting peak infection size against β and revealing the R₀=1 epidemic threshold
- Reproduced stochastic vs deterministic comparisons and estimated major-outbreak probability via Monte-Carlo simulation (1,000 runs) against the analytic estimate p = 1 − 1/R₀
- Researched and summarised SEIR, SEIQR, SIS and vital-dynamics extensions, linking them to latent periods, isolation, reinfection and long-term population dynamics

## Files
- `*.ipynb`: full Jupyter notebook (code + figures)
- `*.pdf`: group project write-up
