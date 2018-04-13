# smirnoff-amortized-inference-testbed
Test container to display in-progress machinery for using amortized inference to refit the C-C LJ parameters (to scale up) from the `smirnoff99Frosst` forcefield. We are training solely on molar volume and heat of vaporization from cyclohexane.

# Repositories
- `/python-scripts`: contains all python scripts and ipython notebooks demonstrating making estimates of properties using `pymbar`, constructing Gaussian process regressions with `gpy` and implementing MCMC using `emcee` in order to sample from a posterior distribution of forcefield parameters.
- `/reference`: contains the state data and coordinate trajectories (for both liquid and gas phase simulations) for a sample reference state.
- `simulation-data`: contains observables calculated by simulation at ~120 different parameter states in order to compare to MBAR.
