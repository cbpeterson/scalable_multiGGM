# shrinkage_prior_for_multiGGMs
## Author: Elin Shaddox

The Matlab files provided for Bayesian inference of multiple graphical models are associated with the following publication:
- Shaddox E, Stingo F, Peterson CB, Jacobson S, Cruickshank-Quinn C, Kechris K, Bowler R, Vannucci M. (2018). A Bayesian approach for learning gene networks underlying disease severity in COPD. *Statistics in Biosciences*. 10(1): 59-85. [[pdf](https://odin.mdacc.tmc.edu/~cbpeterson/Shaddox_SIB_2018.pdf)]

This work improves the computational scalability of our previous work on Bayesian inference of multiple Gaussian graphical models by utilizing a continuous shrinkage prior. This enables the current method to scale to \>100 nodes.

These scripts rely on code provided with the following prior publications:
- Peterson CB, Stingo FC, Vannucci M. (2015) Bayesian inference of multiple Gaussian graphical models. *Journal of the American Statistical Association*. 110(509): 159—174.
- Wang H. Scaling it up: stochastic search structure learning in graphical models. *Bayesian Analysis*. 10 (2015): 351-377

Please cite these publications if you use this code. Thanks!

## OVERVIEW OF FILES 

## Example_multiple_graphs_SSVS.m
Basic example of running the MCMC sampler and generating results summaries on a simple setting with 3 groups with identical dependence structure

## MCMC_multiple_graphs_SSVS_final.m
Code for running the MCMC sampler

## calc_mrf_C.m
Helper function for calculating the normalizing constant for the MRF prior

## generate_sim1_input.m
Script to generate matrices similar to those used as input to the first simulation
