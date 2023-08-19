# Generative Modelling for Risk Management

We propose a novel TimeGAN (Time Generative Adversarial Network) based framework for synthetic multivariate time-series generation, combining both cross-sectional and temporal data. We use time-series of a combination of 26 fundametal ratios and 12 macro-economic variables to model the joint probability distribution. The TimeGAN model generates multivariate time-series projecting 8 quarters into the future.

We then sample from the modelled joint probability distribution to generate synthetic scenarios and obeserve the corresponding impacts on the fundamental ratios for different industries in the S&P 500. We used this framework to build a dashboard for portfolio managers, risk managers etc. to evaluate portfolio performance and risk metrics.

This was part of the capstone project under Bloomberg LP.
