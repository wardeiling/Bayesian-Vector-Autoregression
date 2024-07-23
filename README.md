The repository contains two files
- `Report-Bayesian-Vector-Autoregression.pdf`: Provides the written report that covers (1) the introduction on why Bayesian VAR may be preferred over its frequentist counterpart, (2) the Bayesian person-specific VAR(p) model and two basic priors, (3) the methods of bayesian estimation and model selection, (4) the results in terms of convergence, posterior analysis and model selection, and (5) a discussion.
-  Analysis-Results-Script.qmd: this file contains the code for (1) the import and preparation of an example dataset (Kossakowski et al., 2017), (2) the simulation of data from a VAR process, (3) the frequentist estimator using matrix algebra, (4) an elaborate function for computing posterior probabilities, creating plots (trace, density, autocorrelation) and marginal likelihoods for one of the three different priors (two of which rely on M-C integration and one of which uses Gibbs-sampling), (5) the application of this function to the example data, and (6) the computation of Bayes factor to compare the three models
